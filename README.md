# Google Adsense for Vue
![npm version](https://badge.fury.io/js/vue-adsense.svg)

#### vue-adsense

A simple Vue component for handling Google Ads

## Installation

```bash
npm install --save-dev vue-adsense
```

and include the `adsbygoogle.js` file in your HTML

```html
<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
```

## Usage

Import the component

```js
import VueAdsense from 'vue-adsense'
```

Register the component

```js
Vue.component('adsense', VueAdsense)
```

And put into your DOM

```html
<adsense
  ad-client="ca-pub-xxxxxxxxxxxxxxxx"
  ad-slot="XXXXXXXX"
  ad-style="display: block"
  ad-format="auto">
</adsense>
</div>
```

## Values

* ad-client - Your Google Adsense publisher account
* ad-slot - The desired ad ID
* ad-style - Any special styling you want
* ad-format - Provided by Google, is usually 'auto'

#### Notes

Contributions welcome, enjoy the component

