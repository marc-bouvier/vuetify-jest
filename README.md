# vuetify-jest

Run unit test with Jest

```
npm run test:unit
```

Console output : 

```
> vuetify-jest@0.1.0 test:unit D:\Projets\vuetify-jest
> vue-cli-service test:unit

PASS tests/unit/example.spec.js
  HelloWorld.vue
    v matches snapshot (83ms)

  console.error node_modules/vuetify/dist/vuetify.js:22968
    [Vuetify] Multiple instances of Vue detected
    See https://github.com/vuetifyjs/vuetify/issues/4068

    If you're seeing "$attrs is readonly", it's caused by this

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   1 passed, 1 total
Time:        1.811s
Ran all test suites.

```

The test runs fine but there is a message I cannot get rid of : 

```
  console.error node_modules/vuetify/dist/vuetify.js:22968
    [Vuetify] Multiple instances of Vue detected
    See https://github.com/vuetifyjs/vuetify/issues/4068

    If you're seeing "$attrs is readonly", it's caused by this
```
