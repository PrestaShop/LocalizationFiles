# PrestaShop localization files

This repository contains the official localization files for PrestaShop.

## What's that?

Localization files specify which languages and currencies to install for a given country, as well as local taxes.

These files are bundled in packs and downloadable from your back office.

## Submitting changes

To update these files, you have to execute `bin/console prestashop:taxes:update-eu-tax-rule-groups` into the [PrestaShop project](https://github.com/PrestaShop/PrestaShop). Then, after the changes have been made, you can submit a Pull Request to this repository by copying the updated files from the PrestaShop project.

Embedding the localization files in the project allows users to benefit from localization files without having to download them.

## License

Files in this project belong to the PrestaShop open source project and therefore are released under the OSL-3.0 license.
