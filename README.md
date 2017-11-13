[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/SieBrum/brum-global-variable)

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
```
Import brum-global-variable into your component.

<brum-global-var key="x-foo" value="{{x-bar}}"></brum-global-var>
<brum-global-var key="x-foo" value="{{x-awesome}}"></brum-global-var>

<brum-global-var key="alpha" value="{{beta}}" readonly></brum-global-var>

<brum-global-var key="abc" value="{{xyz}}" value-changed="someCoolFunction"></brum-global-var>
```
## DEMO
[webcomponents.org](https://www.webcomponents.org/element/SieBrum/brum-global-variable/demo/demo/index.html)

