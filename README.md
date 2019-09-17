# mmm-wordoftheday

This is a module for the [MagicMirror²](https://github.com/MichMich/MagicMirror/).

Dutch word of the day (http://wordoftheday.nl) module for MagicMirror

## Using the module

To use this module, add the following configuration block to the modules array in the `config/config.js` file:

```js
var config = {
  modules: [
    {
      module: "mmm-wordoftheday",
      config: {
        // See below for configurable options
      }
    }
  ]
};
```

## Configuration options

| Option    | Description                                                                                                     |
| --------- | --------------------------------------------------------------------------------------------------------------- |
| `option1` | _Required_ DESCRIPTION HERE                                                                                     |
| `option2` | _Optional_ DESCRIPTION HERE TOO <br><br>**Type:** `int`(milliseconds) <br>Default 60000 milliseconds (1 minute) |
