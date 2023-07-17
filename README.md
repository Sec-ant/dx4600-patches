# dx4600-patches

```js
// ==UserScript==
// @name         DX4600 Patcher
// @namespace    https://github.com/Sec-ant/dx4600-patches
// @version      0.1.1
// @description  Apply patches to UGREEN DX4600
// @author       Sec-ant
// @match        http*://nas.lan:9999/*
// @match        http*://10.10.10.6:9999/*
// @match        https://fastly.jsdelivr.net/*
// @webRequest   {"selector":"*://*/home/static/js/app.9c86d878.js","action":{"redirect":"https://fastly.jsdelivr.net/gh/Sec-ant/dx4600-patches/home/static/js/app.9c86d878.min.js"}}
// @webRequest   {"selector":"*://*/home/static/js/app.9c86d878.js","action":{"redirect":"https://fastly.jsdelivr.net/gh/Sec-ant/dx4600-patches/home/static/js/app.9c86d878.min.js"}}
// @icon         https://cloud.ugnas.com/logo.ico
// @run-at       document-start
// @grant        none
// ==/UserScript==

(function() {
    'use strict';
})();
```
