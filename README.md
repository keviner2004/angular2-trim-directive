# ng2-trim-directive
[![Build Status](https://travis-ci.org/anein/angular2-trim-directive.svg?branch=master)](https://travis-ci.org/anein/angular2-trim-directive)
[![npm](https://img.shields.io/npm/v/ng2-trim-directive.svg)](https://www.npmjs.com/package/ng2-trim-directive)

>The directive trims whitespaces from the end of an input text value.


## Usage 

1. Install `ng2-trim-directive`.

  ```bash
    npm i ng2-trim-directive
  ```

2. Import `InputTrimModule` to your Angular module.

```typescript
import { InputTrimModule } from 'ng2-trim-directive';
@NgModule({
  imports: [
    ...
    InputTrimModule,
    ...
  ],
  ...
```

3. Add the "trim" attribute to a text input element.
  ```html
     <input type="text" trim />
  ```

  or with an option: trim value only on the blur event.

  ```html
     <input type="text" trim="blur" />
  ```


---
Good luck. 
