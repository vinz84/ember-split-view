<<<<<<< HEAD
=======
# ember-split-view
>>>>>>> 4223563 (v3.6.1...v4.4.1)

See it in action: http://bryanhunt.github.io/#/split

<<<<<<< HEAD
There is a demo app in [tests/dummy](https://github.com/BryanHunt/ember-split-view/tree/master/tests/dummy).
=======

## Compatibility

* Ember.js v3.24 or above
* Ember CLI v3.24 or above
* Node.js v12 or above

>>>>>>> 4223563 (v3.6.1...v4.4.1)

## Installation

```
ember install ember-split-view
```

## Configuration

<<<<<<< HEAD
You need to add the following to your `config/environment.js`:
```javascript
resizeServiceDefaults: {
  debounceTimeout    : 200,
  heightSensitive    : true,
  widthSensitive     : true,
  injectionFactories : [ 'view', 'component']
},
```
=======
## Usage
>>>>>>> 4223563 (v3.6.1...v4.4.1)

### Examples
Vertical SplitView example:

```
{{#split-view isVertical=true as |split| }}
  {{#split.child}}
    Content of the left view here.
  {{/split.child}}
  {{split.sash}}
  {{#split.child}}
    Content of the right view here.
  {{/split.child}}
{{/split-view}}
```

<<<<<<< HEAD
Horizontal SplitView example:

```
{{#split-view isVertical=false as |split|}}
  {{#split.child}}
    Content of the top view here.
  {{/split.child}}
  {{split.sash}}
  {{#split.child}}
    Content of the bottom view here.
  {{/split.child}}
{{/split-view}}
```

### Donating

All donations will support this project and keep the developer supplied with Reese's Minis.

[![Support via Gittip](https://rawgithub.com/twolfson/gittip-badge/0.2.0/dist/gittip.png)](https://www.gittip.com/BryanHunt/)
=======
## Contributing

See the [Contributing](CONTRIBUTING.md) guide for details.


## License
>>>>>>> 4223563 (v3.6.1...v4.4.1)

