---
resource: receipts
permalink: /docs/3.0.0/resources/receipts/
version: 3.0.0
singular: resource
section: Messages
attributes:
  -
    name: numero
    crud: read
    sortable: 'true'
  -
    name: enviado
    crud: 'read, update'
    filter: NumberFilter
    sortable: 'true'
  -
    name: whatsapp_message_id
    crud: read
    sortable: 'true'
relationships:
  -
    resource: line
    alias: line
    crud: read
  -
    resource: message
    alias: message
    crud: 'create, read'
  -
    resource: number
    alias: number
    crud: 'create, read'

---
