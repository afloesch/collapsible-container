# \<collapsible-container\>

Polymer 1.X and 2.X collapsible container

## Install

```shell
bower install --save polymer-collapsible-container
```

## Usage
### collapsible-container
<!--
```
<custom-element-demo height="100">
  <template>
    <link rel="import" href="collapsible-container.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<collapsible-container header="Test">
  Content goes here
</collapsible-container>
```

### accordion-container
<!--
```
<custom-element-demo height="150">
  <template>
    <link rel="import" href="collapsible-container.html">
    <link rel="import" href="accordion-container.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<accordion-container>
  <collapsible-container header="Test">
    Content goes here
  </collapsible-container>
  <collapsible-container header="Test 2">
    Content goes here
  </collapsible-container>
  <collapsible-container header="Test 3">
    Content goes here
  </collapsible-container>
</accordion-container>
```

## Viewing This Element

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve element locally.

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
