# cadence/m2cachebust
Magento 2 Module For RequireJS Cache Busting

Magento 2 utilizes RequireJS to load client-side assets, in both the admin and the frontend. You may have noticed, but even with your app in developer mode it still seems like the javascript and .html template files are being cached. It gets old having to clear your browser’s cache everytime you make an update to your store’s view code.

This module provides a quick fix to add cache busting to the RequireJS configuration, which should resolve the problem for you.

See the official documentation and usage example here: https://www.cadence-labs.com/2016/09/magento-2-clear-disable-javascript-template-cache/
