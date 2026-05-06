# Configuration

!!! note "Fill this in"
    Document each configuration option your project exposes. The structure below
    is a starting point — adapt it to your actual config surface.

## Overview

gambit_demo can be configured via:

1. A config file (`gambit_demo.toml` or `.gambit_demo.toml` in the project root)
1. Environment variables prefixed with `GAMBIT_DEMO_`
1. Command-line flags (highest precedence)

## Options

### `option_name`

**Type:** `string`
**Default:** `"default_value"`
**Environment variable:** `GAMBIT_DEMO_OPTION_NAME`

Description of what this option controls and when you would change it.

```toml
# gambit_demo.toml
option_name = "custom_value"
```

______________________________________________________________________

### `another_option`

**Type:** `bool`
**Default:** `false`
**Environment variable:** `GAMBIT_DEMO_ANOTHER_OPTION`

Description of what this option controls.

```toml
another_option = true
```

## Example config file

```toml
# gambit_demo.toml
option_name = "custom_value"
another_option = true
```
