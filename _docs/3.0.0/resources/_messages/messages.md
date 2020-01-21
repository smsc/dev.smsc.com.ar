---
resource: messages
permalink: /docs/3.0.0/resources/messages/
version: 3.0.0
singular: resource
section: Messages
attributes:
  -
    name: date
    crud: 'create, read'
    sortable: 'true'
  -
    name: fecha
    crud: 'create, read'
    filter: DateFilter
    sortable: 'true'
  -
    name: priority
    crud: read
    sortable: 'true'
  -
    name: text
    crud: 'create, read'
    sortable: 'true'
  -
    name: method
    crud: 'create, read'
    filter: EnumFilter
    sortable: 'true'
  -
    name: sent_status
    crud: read
    sortable: 'true'
  -
    name: sent_status_code
    crud: read
    filter: NumberFilter
    sortable: 'true'
relationships:
  -
    resource: receipts
    alias: receipts
    crud: 'create, read'
  -
    resource: line
    alias: line
    crud: 'create, read'
  -
    resource: number
    alias: number
    crud: 'create, read'

---
