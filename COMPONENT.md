### My first component

##### with single line render return
```js
var MyComponent = React.createClass({
    render: function (){
        return 'My First Component'; // single line return
    }
});
```

##### another way of creating component
```js
class MyComponent extends React.Component({
    render() {
        return 'My First Component'; // single line return
    }
});
```

##### with multiple line render return
```js
var MyFirstComponent = React.createClass({
    render: function (){
        return (
            <div>
                Hello World
            </div>
        ); // use paranthesis when mutliple line return
    }
});
```


##### with use of props
```js
var MyFirstComponent = React.createClass({
    render: function (){
        return (
           <div>
             {this.props.myfirstprop}
           </div>
       );  // use {} which acts as an expression
    }
});
```