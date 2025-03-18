# patch'd [TYPO3](https://typo3.org) extension [`fluid-styled-content`](https://github.com/TYPO3/typo3/tree/main/typo3/sysext/fluid_styled_content)

This extension provides Fluid templating for TYPO3 content elements.

## Compatibility

* `^10.4` incl. attr. `decoding` [[patch](https://github.com/TYPO3/typo3/commit/c0e99719e17b275a2a85a676ea9ed60c22999476)]
* https://github.com/typo3patch/cms-fluid-styled-content/blob/796d42b87a181a488210b98b6f76b1f27b35f336/composer.json#L18

## Installation

```bash
composer config repo.t3p-fluid git https://github.com/typo3patch/cms-fluid
composer config repo.t3p-fluid-styled-content git https://github.com/typo3patch/cms-fluid-styled-content
composer req typo3patch/cms-fluid-styled-content
```

## Patches

+ [x] add attr. `fetchpriority` @ `<f:media />` [[issue](https://forge.typo3.org/issues/97765)]
