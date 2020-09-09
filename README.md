# Adyen Web

[![npm](https://img.shields.io/npm/v/@adyen/adyen-web.svg)](http://npm.im/@adyen/adyen-web)

Adyen Web provides you with the building blocks to create a checkout experience for your shoppers, allowing them to pay using the payment method of their choice.

You can integrate with Adyen Web in two ways:
* [Web Drop-in](https://docs.adyen.com/checkout/drop-in-web/): an all-in-one solution, the quickest way to accept payments on your website.
* [Web Components](https://docs.adyen.com/checkout/components-web/): one Component per payment method and combine with your own payments form logic.

## Prerequisites

* [Adyen test account](https://www.adyen.com/signup)
* [API key](https://docs.adyen.com/development-resources/how-to-get-the-api-key)
* [Client key](https://docs.adyen.com/development-resources/client-side-authentication#get-your-client-key)

## Installation

### NPM

Install [NPM](https://www.npmjs.com/package/@adyen/adyen-web) package:

```sh
npm install @adyen/adyen-web --save
```

And import in your application:

```js
import AdyenCheckout from '@adyen/adyen-web';
import '@adyen/adyen-web/dist/adyen.css';
```

### Script tag

Adyen Web can also be imported with a `<script>` tag, refer to [the documentation](https://docs.adyen.com/checkout/components-web#step-2-add-components) for instructions.

#### Please note: 
We only provide full support when using one of these methods of installation.
Modifications to the code base should be made via a pull request or by creating an issue.

## Rationale

We have open-sourced Adyen Web for the following reasons:
- Allowing developers to have easier access to the source code for quick and easy debugging
- Allowing developers to freely raise bugs/issues/feature requests
- Providing developers with a way to be informed and updated whenever a new release is made available (i.e. "Watching" the repository)

## See also

-   [Complete Documentation](https://docs.adyen.com/checkout/)

-   [API Explorer](https://docs.adyen.com/api-explorer/)

-   [Adyen Components JS Sample Code](https://github.com/Adyen/adyen-components-js-sample-code)


## Development environment

Follow these steps to run our development playground:

* Clone [this repository](https://github.com/Adyen/adyen-web) and navigate to the root of the project.
* Create a `.env` file on your project's root folder following the example on `.env.default` and fill in the necessary environment variables.
* Install all dependencies by running:
```
yarn install
```

* Start the development playground. This will start a local server on [http://localhost:3020](http://localhost:3020).
```
yarn start
```

### Branch organization

We merge every pull request to the `master` branch. We aim to keep `master` in good shape, which allows us to release a new version whenever we need to.

## Support

If you have a feature request, or spotted a bug or a technical problem, create an issue here. For other questions, contact our [support team](https://support.adyen.com/hc/en-us/requests/new?ticket_form_id=360000705420).

## License

This repository is available under the [MIT license](LICENSE).
