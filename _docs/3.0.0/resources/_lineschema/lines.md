---
resource: lines
permalink: /docs/3.0.0/resources/lines/
version: 3.0.0
singular: resource
section: LineSchema
attributes:
  -
    name: numero
    crud: read
    sortable: 'true'
  -
    name: whatsapp_web_qr
    crud: read
    sortable: 'true'
relationships:
  -
    resource: number
    alias: number
    crud: read

---
