
# auth0-header

  Auth0's website and landings header

## Installation

~~~html
<link href="https://cdn.auth0.com/styleguide/latest/index.css" rel="stylesheet" />
<link href="https://cdn.auth0.com/web-header/latest/standalone.css" rel="stylesheet"/>
<script type="text/javascript" src="//cdn.auth0.com/web-header/latest/standalone.min.js"></script>
~~~

## API

```
// TODO


```

## Development

### Demo run

Run:

```
npm install
grunt dev
```

And point your browser at `http://localhost:9999`.

### Release

Make sure you have [bump](https://github.com/ianstormtaylor/bump) and [git-extras](https://github.com/tj/git-extras)
Follow the next steps:

``` bash
  # Once finished your changes and commit them, run:
  bump {patch,minor,major,VERSION}

  # Then create the changelog for the release, using
  # the retrieved version by last command:
  git changelog --tag <version>

  # Then, just run:
  git add . && git release <version>

  # Done!
```

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
