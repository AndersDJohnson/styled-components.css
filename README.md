# styled-components.css
Possible hybrid styled-components + CSS syntax.

```css
@import '';
@import foo from './file';
@import { bar, baz } from './other';

.myClass {
  color: red;
  background: ${props => props.red};
}
```
