# PHPStan extension for neos/flow

## What does it do?

* [x] Bootstrap Flow to resolve undefined constants
* [x] Provide Stub files 

## Installation

```shell
composer require --dev networkteam/flow-phpstan
```

Include the `extension.neon` in you `phpstan.neon`.

```
includes:
    - %currentWorkingDirectory%/Packages/Libraries/networkteam/flow-phpstan/extension.neon
```
