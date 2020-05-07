# pikalytics-dark
A Stylish script which provides dark mode for Pikalytics. This is an open source stylesheet with the intention of iterating on until it's ready to go live as a permanent fixture on Pikalytics.

## Requirements

- Stylish
  - [Chrome](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en)
  - [Firefox](https://addons.mozilla.org/en-CA/firefox/addon/stylish/)

## Setup

- Create New Style in Stylish
- Copy `dark.css` from this repo into the new Stylish script

## Usage

- Enable new Stylish script for https://www.pikalytics.com
- Inspect Elements in your browser, and add the class `dm` to the body, after `pokedex`,`team`, etc. so it looks like:
```html
<body onload="onLoad()" class="pokedex dm">
```
- You should see the dark theme take effect.
- Feel free to iterate, and submit pull requests here if you'd like!
