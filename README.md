# t2e2t [![Build Status](https://secure.travis-ci.org/GreMendes/t2e2t.png?branch=master)](https://travis-ci.org/GreMendes/T2E2T)

Transform Text to HTML Entity and HTML Entity to text

## Install

```bash
npm install --save t2e2t
```

## Examples

See `examples/` for different use cases.

Transform textToEntity("Têxt tõ entitîes") => "T&ecirc;xt t&otilde; entit&icirc;es
Transform entityToText("T&ecirc;xt t&otilde; entit&icirc;es") => "Têxt tõ entitîes"

## License

MIT
