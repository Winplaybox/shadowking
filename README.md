# shadowking

Get prefect shadows every time for the non-desinger.

# Installation

`npm i shadowking --save`

Then...

```
import {shadowking} from 'shadowking;

shadowking({
    shadow_type:'soft',
    padding:false,
    margin:false
});
```

## Options

Shadowking supports 3 options, both of whihc are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)
* *margin* - _boolean_ (Defaults to false)