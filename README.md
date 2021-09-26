# Web components example
This is basic tab component implemented by web components api. It has some aspects of acessibility(focus, switching active tab by using arrows on keyboard).

### Demo
[Here you can see demo](https://xxndr.github.io/web-components-example/)

### Usage 
```html
<my-tabs>
    <div role="tablist">
        <button aria-selected="true" tabindex="0" role="tab">One</button>
        <button role="tab" tabindex="-1" aria-selected="false">Two</button>
    </div>
    <div
        aria-selected="true"
        role="tabpanel"
        aria-controls="panel-1"
        tabindex="0"
    >
        One
    </div>
    <div hidden role="tabpanel" aria-controls="panel-2" tabindex="-1">
        Two
    </div>
</my-tabs>
```
