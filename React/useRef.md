useRef"  is part of React that allows us to get references to various elements.  

For example, in a "form", an "input" can be bound to  a reference which allows us to get reference to the current value. 

```html
const txtRef = useRef(); 

... 

<input type='text' ref={txtRef} /> 
```

The text input can be accessed as below: 

`txtRef.current.value`

> Ref does is considered as uncontrolled element, meaning that the value is determined based on external factors. e.g., user interaction. 