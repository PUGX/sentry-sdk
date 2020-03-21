<p align="center">
    <img src="https://sentry-brand.storage.googleapis.com/sentry-logo-black.png" width="280" alt="sentry">
    <img src="https://avatars0.githubusercontent.com/u/2310209" width="280" alt="pugx">
</p>

# Sentry pre-configured PHP SDK

[![Monthly Downloads](https://poser.pugx.org/pugx/sentry-sdk/d/monthly)](https://packagist.org/packages/pugx/sentry-sdk)
[![Latest Stable Version](https://poser.pugx.org/pugx/sentry-sdk/v/stable)](https://packagist.org/packages/pugx/sentry-sdk)
[![License](https://poser.pugx.org/pugx/sentry-sdk/license)](https://packagist.org/packages/pugx/sentry-sdk)

This is a metapackage shipping [sentry/sentry](https://github.com/getsentry/sentry-php) with Symfony client instead of Guzzle.

See [issue #246 on gesentry/sentry-symfony](https://github.com/getsentry/sentry-symfony/issues/246) for reasons that lead to create this metapackage.

## Usage

This is an example of using this metapackage in your composer.json (other dependencies are omitted for the sake of simplicity):

```json
{
    "require": {
        "pugx/sentry-sdk": "^1.0",
        "sentry/sentry-symfony": "^3.4",
    }
}
```
