# What is this?

Get perfect shadows every time for the non-designer.

# Installation

`npm i shadowizerd --save`

Then...

```
import { shadowizerd } from 'shadowizerd';

shadowizerd({
    shadow_type: 'soft',
    padding: false
});
```

## Options

Shadowizerd supports 2 options, both of which are optional:

* *shadow_type* - _herd | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)