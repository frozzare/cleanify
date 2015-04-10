# Cleanify

> Requires PHP 5.4

Simple plugin to remove slug from custom post types permalinks.

# Example

Before: `http://example.com/photograph/random-name`

After:  `http://example.com/random-name`

```php
add_filter('cleanify/cpts', function () {
  return 'photograph';
});
```

# Filters

#### cleanify/cpts

Return all post types where the slug should be removed.
Should be a string or array of strings.

## License

MIT © [Fredrik Forsmo](https://github.com/frozzare)
