# renovate-config

Contains shareable config [presets](https://docs.github.com/en/actions/using-workflows/reusing-workflows)
and [re-usable](https://docs.github.com/en/actions/using-workflows/reusing-workflows)
Github workflow for [renovate](https://docs.github.com/en/actions/using-workflows/reusing-workflows).

The [default.json](./default.json) file contains the shared presets.

## Usage
Add a `.github/renovate.json` file with the following content:

```json
{
  "extends": ["github>buildtool/renovate-config"]
}
```
