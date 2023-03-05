1. build the lib
2. import it in a webpack project

```
import {yolo} from "polyfill-lib";
console.log(yolo)
```

3. `npm run build` in project

Resulting issue:

> Warning: Critical dependency: require function is used in a way in which dependencies cannot be statically extracted
