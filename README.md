# react-native-pagarme-card-hash

> ⚠️ **IMPORTANT: this repository will no longer get updates.**
> I have created a new library which supports React Native, Expo, browser and Node: [pagarme-card-hash](https://github.com/franzon/pagarme-card-hash).

React Native module for generating pagar.me card hashes

![npm](https://img.shields.io/npm/v/react-native-pagarme-card-hash)

## Support

Works on iOS 10+ and Android 4.1+ 

## Installation

```sh
yarn add react-native-rsa-native react-native-pagarme-card-hash
```

## Usage

```js
import generateCardHash from 'react-native-pagarme-card-hash';

// ...

const hash = await generateCardHash(
    {
        number: '5315084062046316',
        holderName: 'John Doe',
        expirationDate: '0921',
        cvv: '560',
    },
    '<your encryption key>'
);
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
