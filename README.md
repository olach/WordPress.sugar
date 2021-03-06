# WordPress.sugar for Espresso
This is a plugin for the [Espresso](https://espressoapp.com) code editor with support for [WordPress](http://wordpress.org/).

## Features

### WordPress autocompletion
This Espresso plugin adds autocompletion and parameter hinting for all public functions in WordPress. Private and deprecated functions are excluded.

Start type the name of the desired function and press <kbd>tab</kbd> or <kbd>enter</kbd> to autocomplete the function.

Use <kbd>tab</kbd> and <kbd>shift</kbd>+<kbd>tab</kbd> to select the parameters. Optional parameters are wrapped in square brackets and can easily be deleted if not used.

![Demo](demo.gif)

### Look up function in WordPress Code Reference
Another handy feature is the ability to quickly look up a function in the WordPress Code Reference.

The action is found in the Espresso Action menu under the WordPress folder. Simply select or place the cursor on a WordPress function. Then, run the action to open the WordPress Code Reference in your browser.

## Installation
1. Download and extract the zip
2. Double click the WordPress.sugar file to install it

## Data source
The WordPress data for this plugin is gathered using the api from [wpseek.com](http://wpseek.com/). I will do my best to keep the plugin updated with every major WordPress update.

Current version is using data from WordPress 5.1.
