# getbasis-margin-between-children
This is a css module for the Basis.

## Basis
* Repository: https://github.com/getbasis/basis/
* Documents : https://getbasis.github.io/

## Get Started

### Install
```
$ yarn add getbasis
$ yarn add getbasis-margin-between-children
```

### Stylus
```
// The bottom margin of HTML Elements is 0.
_margin-bottom: 0;

@import 'node_modules/getbasis/src/css/basis';
@import 'node_modules/getbasis-margin-between-children/src/css/core/mixin/margin-between-children';

.entry-content {
  _margin-between-children(1);
}
```

## Browser support
Modern Browser and IE10+

## License
MIT License
