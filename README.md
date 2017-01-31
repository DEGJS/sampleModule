# sampleModule
Module introduction goes here.

## Install
SampleModule is an ES6 module. Consequently, you'll need an ES6 transpiler ([Babel](https://babeljs.io) is a nice one) and a module loader ([SystemJS](https://github.com/systemjs/systemjs) will do the job) as part of your Javascript workflow.

If you're already using the [JSPM package manager](http://jspm.io) for your project, you can install SampleModule with the following command:

```
$ jspm install github:DEGJS/sampleModule
```

## Usage
Code sample of SampleModule usage.
```js
import sampleModule from 'DEGJS/sampleModule';

let element = document.querySelector('div');

let instance = sampleModule(element);
```


## Parameters

### parameter1
Type: `HTMLElement`   
Description of parameter1. 

## Methods

### .method1(options)
Parameters: `options`   
Description of method1 and the values specified in the `options` parameter:

#### options.property1
Type: `Number`   
Description of property1.

## Browser Support

SampleModule depends on the following browser APIs:
+ [Api.method](link-to-api-documentation)

To support legacy browsers, you'll need to include polyfills for the above APIs.
