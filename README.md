# Laravel CI Actions

Reusable actions for laravel.

## Example usage

### Prepare-App

Refer to the input variables in [the action](prepare-app/action.yml).

```yml
jobs:
  myJobName:
    steps:
      uses: michiruf/laravel-ci/prepare-app@main
      with:
        coverage: true
        php-version: ${{ matrix.php }}
```

For a full test example refer to [prepare-app.yml](example/prepare-app.yml)
