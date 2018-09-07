react-ui-components
===================

> Controlled, stateless ui-components for use in React applications.

All the components are controlled from the outside, even form controls like checkboxes etc. This simplifies testing and debugging, as the store is the single source of truth.

We are in the process of migrating existing components from an internal Equinor project still under development, while new ones from this point onwards will be developed directly in this repository.

Install
-----

Using npm:

```sh
npm install --save-dev @equinor/react-button
```

Using yarn:

```sh
yarn add @equinor/react-button --dev
```

…in foo.js:

```js
import Button from '@equinor/react-button'

<Button>Submit</Button>
```

Store
-----

Since all components are stateless, you need a store for state management. We recommend Mobx.


Theming
-------

The components use Styled Components for styling, which has theme-support built in. However, while we have theme-support in the backlog it's currently not implemented. If this prevents you from using the components in your project, let us know, and we'll reconsider our priorities.


Colour pallette
---------------

The colour palette is based on the official Equinor pallette with a few exceptions, but instead of using a white background as recommended in the guidelines, we have created a subset of this palette suitable for a dark mode, which is easier on the eyes in the long run.

