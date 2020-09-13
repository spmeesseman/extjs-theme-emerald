# ExtJs Theme - Emerald (Green/White)

[![Version](https://vsmarketplacebadge.apphb.com/version-short/spmeesseman.extjs-theme-emerald.svg)](https://marketplace.visualstudio.com/items?itemName=spmeesseman.extjs-theme-emerald)
[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/spmeesseman.extjs-theme-emerald.svg)](https://marketplace.visualstudio.com/items?itemName=spmeesseman.extjs-theme-emerald)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/spmeesseman.extjs-theme-emerald.svg)](https://marketplace.visualstudio.com/items?itemName=spmeesseman.extjs-theme-emerald)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/spmeesseman.extjs-theme-emerald.svg)](https://marketplace.visualstudio.com/items?itemName=spmeesseman.extjs-theme-emerald&ssr=false#review-details)
[![authors](https://img.shields.io/badge/authors-scott%20meesseman-6F02B5.svg?logo=visual%20studio%20code)](https://www.littlesm.com)
[![PayPalDonate](https://img.shields.io/badge/paypal-donate-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=YWZXT3KE2L4BA&item_name=taskexplorer&currency_code=USD)

[![GitHub issues open](https://img.shields.io/github/issues-raw/spmeesseman/vscode%2dtaskexplorer.svg?logo=github)](https://github.com/spmeesseman/extjs-theme-emerald/issues)
[![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/spmeesseman/vscode%2dtaskexplorer.svg?logo=github)](https://github.com/spmeesseman/extjs-theme-emerald/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/spmeesseman/vscode%2dtaskexplorer.svg?logo=github)](https://github.com/spmeesseman/extjs-theme-emerald/pulls)
[![GitHub last commit](https://img.shields.io/github/last-commit/spmeesseman/vscode%2dtaskexplorer.svg?logo=github)](https://github.com/spmeesseman/extjs-theme-emerald)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

## Description

> This package provides a Neptune based, ulta-vilot purple flavored ExtJS theme (ExtJS 7.0+).

## Install

To install this package, run the following command:

    npm install @perryjohnson/extjs-theme-emerald

## Usage

For an open tooling build, add the node_modules path to the workspace.json packages path array:

     "packages": {
        "dir": "...${package.dir}/node_modules/@perryjohnson/extjs-theme-emerald"
    }

Simply use the theme in app.json as you would any other theme:

    "builds":
    {
        "emerald":
        {
            "toolkit": "classic",
            "theme": "theme-emerald"
        }
    }
