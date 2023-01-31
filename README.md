# marriage-officiants-demo

A very fast demo of using data from the [Ontario Data Catalogue](https://data.ontario.ca/) to build a client-side application.

Built with:
* https://www.11ty.dev/
* https://alpinejs.dev/

No guarantees and not an official project of the Ontario Digital Service!

The demo is viewable online at https://aharnum-ods.github.io/marriage-officiants-demo/

## Instructions

Requires node and npm.

* `npm install`
* `npm run serve`
* Visit `http://localhost:8080` in your browser

## Notes

* `src/_data/weddingOfficiants.js`:
    * Fetches and caches the [marriage officiants dataset](https://data.ontario.ca/dataset/registered-marriage-officiants) using the [eleventy-fetch plugin](https://www.11ty.dev/docs/plugins/fetch/)
    * Parses and transforms the data, and makes it available to templates using Eleventy's [global data files](https://www.11ty.dev/docs/data-global/) feature
