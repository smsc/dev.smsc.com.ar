---
resource: message_statuses
permalink: /docs/3.0.0/resources/message_statuses/
version: 3.0.0
singular: resource
section: Messages
attributes:
  -
    name: status
    crud: 'create, read'
    sortable: 'true'
  -
    name: whatsapp_message_id
    crud: 'create, read, update'
  -
    name: created_at
    crud: read
    sortable: 'true'
relationships:
  -
    resource: message
    alias: message
    crud: 'create, read, update'

---
