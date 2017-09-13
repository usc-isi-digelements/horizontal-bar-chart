# horizontal-bar-chart

A Polymer Element showing a bar chart of horizontal-bar elements with optional selectable behavior.

### Example
```html
<horizontal-bar-chart
  show-checkboxes
  data="[[data]]"
  selected-ids="{{selected}}">
</horizontal-bar-chart>
```

### Styling

`<horizontal-bar-chart>` provides the following custom properties and mixins for styling:

Custom property                            | Description                                         | Default
-------------------------------------------|-----------------------------------------------------|--------
`--horizontal-bar-chart-color`             | The color of the bars.                              | --paper-grey-300
`--horizontal-bar-chart-count-color`       | The color of the count labels.                      | --paper-grey-900
`--horizontal-bar-chart-height`            | The height of the bars.                             | 20px
`--horizontal-bar-chart-title-color`       | The color of the title labels.                      | --paper-grey-900
`--horizontal-bar-chart-title-hover-color` | The color of the title labels on hover (if a link). | --paper-grey-600

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

