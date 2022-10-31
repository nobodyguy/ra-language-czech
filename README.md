# Czech Messages for React-Admin

Czech messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

## Installation

```sh
npm install --save @nobodyguy/ra-language-czech
```

## Usage

```js
import czechMessages from "@nobodyguy/ra-language-czech";
import polyglotI18nProvider from 'ra-i18n-polyglot';

const i18nProvider = polyglotI18nProvider(() => czechMessages, 'cs');

<Admin i18nProvider={i18nProvider}>
  ...
</Admin>
```

## License

This translation is licensed under the MIT License.
