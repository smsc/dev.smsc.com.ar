---
resource: auth_clients
permalink: /docs/3.0.0/resources/auth_clients/
version: 3.0.0
singular: resource
section: AuthFactor
attributes:
  -
    name: name
    crud: 'create, read, update'
    filter: StringFilter
    sortable: 'true'
  -
    name: redirect
    crud: 'create, read, update'
  -
    name: revoked
    crud: read
    sortable: 'true'
relationships:
  -
    resource: user
    alias: user
    crud: 'create, read, update'

---
