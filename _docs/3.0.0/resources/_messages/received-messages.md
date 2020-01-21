---
resource: received_messages
permalink: /docs/3.0.0/resources/received_messages/
version: 3.0.0
singular: resource
section: Messages
attributes:
  -
    name: date
    crud: 'create, read'
    sortable: 'true'
  -
    name: from
    crud: 'create, read'
    sortable: 'true'
  -
    name: text
    crud: 'create, read'
    sortable: 'true'
  -
    name: method
    crud: 'create, read'
    sortable: 'true'
relationships:
  -
    resource: line
    alias: line
    crud: 'create, read, update'

---
