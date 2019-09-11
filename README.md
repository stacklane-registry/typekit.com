# typekit.com

## Import

/🔌.yaml

```
- https://github.com/stacklane-registry/typekit.com.git#!v1.0.0
```

## Tag Usage

Applies the correct Content-Security-Policy and includes the `<link>` for [TypeKit](https://typekit.com).

Accepts a single `id` parameter.  The `id` is the unique portion of the URL TypeKit provides, immediately before `.css`.

```
<head>
...
<typekit.com-css id="xyz123"/>
...
</head>
```
