react-ui-components
===================

> Controlled, stateless ui-components for use in React applications.

All the components are controlled from the outside, even form controls like checkboxes etc. This simplifies testing and debugging, as the store is the single source of truth.

We are in the process of migrating existing components from an internal Equinor project still under development, while new ones from this point onwards will be developed directly in this repository.

Usage
-----

```bash
yarn add --dev @equinor/react-button
```

```js
import Button from '@equinor/react-button'

<Button>Submit</Button>
```

Store
-----

Since all components are stateless, you need a store for state management. We recommend Mobx.
