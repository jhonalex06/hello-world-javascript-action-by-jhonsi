# Bonjour le monde JavaScript Action by Jhonsi

This action prints "Bonjour le monde" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@v1.0
with:
  who-to-greet: Mona the Octocat
```
