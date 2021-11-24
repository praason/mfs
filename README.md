## module federation sample demo

it's a demo using module federation plugin from webpack5 with vue2 & vue-router

### Quick Start

```
cd base
npm install && npm start

cd layout
npm install && npm start
```

### some info

When you need to use module federation with router, you must add `import('main.js')` for importing router files synchronously.


### what is microfrontends

Micro-frontends are small applications mostly divided by subdomain or functionality working together to deliver a larger application

### Advanatges

Each frontend represents a specific feature or subdomain of the entire application
Each frontend can be implemented with a separate team.
Each frontend can be implemented with different technology.
They cannot share logic and its independent of each other.
Each Frontend can be owned by a single team.
