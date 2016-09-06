# eslint-config-data-visuals

This package serves as the base for Data Visuals' JavaScript standards.

## Usage

First, install the package.

```sh
npm install --save-dev eslint-config-data-visuals
```

Then add an [eslint configuration file](http://eslint.org/docs/user-guide/configuring#configuration-file-formats) to your project and extend from this library.

```
{
  "extends": "data-visuals"
}
```

## Wait... isn't this just [`semistandard`](https://github.com/Flet/semistandard)?

You're right! It is. But that package tends to be a little behind [`standard`](https://github.com/feross/standard), and we wanted to keep things flexible if we decide to break away. But `standard` felt like a good starting point!

## License

MIT
