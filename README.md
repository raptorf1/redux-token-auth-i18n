# Redux Token Auth I18n

This is the `redux-token-auth` project as described and licensed [here](https://github.com/kylecorbelli/redux-token-auth).

The version on this repository is the same as the NPM version [here](https://www.npmjs.com/package/redux-token-auth) at the time of this commit.


## Differences

The 3 differences of this repository and the NPM version are the following:
* `Axios` version bumped from 0.16.2 to 0.19.2 after `dependabot` suggestion.
* `Codecov` version bumped from 2.3.1 to 3.6.5 after `dependabot` suggestion.
* You can add a `locale` variable when using the `signInUser` function, in case your API supports internationalization and would like to pass it as a param.