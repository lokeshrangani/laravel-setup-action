# Laravel Setup Action

Reusable GitHub Action to setup Laravel in CI

## Inputs


| Name            | Description                                | Default                        |
|-----------------|--------------------------------------------|--------------------------------|
| php-version     | PHP version to install                     | `8.2`                          |
| extensions      | Comma-separated list of PHP extensions     | `"mbstring, dom, curl, json"`  |
| composer-token  | Composer GitHub auth token                 | _none_                         |

## Example

```yaml
- uses: lokeshrangani/laravel-setup-action@v1
  with:
    php-version: '8.2'
    composer-token: 'string'
    extensions: 'string'