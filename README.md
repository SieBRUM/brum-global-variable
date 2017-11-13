[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/SieBrum/brum-global-variable)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="brum-global-variable.html">
    <link rel="import" href="../paper-input/paper-input.html">
    <dom-bind>
        <template>    
            <next-code-block></next-code-block>
        </template>
    </dom-bind>
  </template>
</custom-element-demo>
```
-->
```html
<brum-global-variable key="value" value="{{first}}"></brum-global-variable>
<paper-input label="Will change others" value="{{first}}"></paper-input>

<brum-global-variable key="value" value="{{second}}" readonly></brum-global-variable>
<paper-input label="Will not change others" value="{{second}}"></paper-input>
```

# \<brum-global-variable\>

A component to easily define, edit and subscribe to global variables

# warning

DO NOT USE THIS ELEMENT TO STORE ANY SENSITIVE DATA
All data CAN be read and editted in/with the default browser console

## Install
```
bower install --save SieBrum/brum-global-variable
```

## How to use
Import brum-global-variable into your component.

```
<brum-global-variable key="x-foo" value="{{x-bar}}"></brum-global-variable>
<brum-global-variable key="x-foo" value="{{x-awesome}}"></brum-global-variable>

<brum-global-variable key="alpha" value="{{beta}}" readonly></brum-global-variable>

<brum-global-variable key="abc" value="{{xyz}}" value-changed="someCoolFunction"></brum-global-variable>
```
## DEMO
[webcomponents.org](https://www.webcomponents.org/element/SieBrum/brum-global-variable/demo/demo/index.html)

