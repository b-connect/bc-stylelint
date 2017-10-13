# Default configuration for stylelint

## Default configuration

This configuration extends [stylelint-config-recommended](https://github.com/stylelint/stylelint-config-recommended).

The [stylelint-scss plugin](https://github.com/kristerkari/stylelint-scss) is included by default.

## Usage

Add following to your `.stylelintrc.json`.

```json
{
    "extends": "bc-default",
    // Add your rules
    "rules: {
        "my-rule": false
    }
}
```