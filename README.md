# Note
This repo is a fork of sconxu/react-native-checkbox, the purpose of it is to allow for the checkbox label to wrap and to add more space between the items.  These two features are quite useful when using multiple checkboxes in a ScrollView component.

# react-native-checkbox
Checkbox component for React native


##Example:
```js
<CheckBox
  label='Label'
  checked={true}
  onChange={(checked) => console.log('I am checked', checked)}
/>
```

##Props:


- `label` : text that will be displayed along the checkbox
- `labelBefore` : position the label before the checkbox (boolean). The default
value is false
- `labelStyle` : style object that will be applied to the label
- `checked` : initial checked value
- `onChange` : callback function that will be invoked with the toggled checked property as argument.
