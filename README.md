# Foundation for Emails & MailChimp

![devDependency Status](https://david-dm.org/jamesrwilliams/foundation-emails-with-mailchimp.svg)
[![GitHub issues](https://img.shields.io/github/issues/jamesrwilliams/foundation-emails-with-mailchimp.svg)](https://github.com/jamesrwilliams/foundation-emails-with-mailchimp/issues)

Built using [Foundation for Emails](http://github.com/zurb/foundation-emails/).

## Setup

To use this template, your computer needs [Node.js](https://nodejs.org/en/) 0.12 or greater.

**1. Install the Foundation CLI with this command**

```bash
npm install foundation-cli --global
```
**2. Install project packages**

```bash
npm install
```

## CLI Commands

Preview in development using live reload:
```
$ npm start
```
Output to production minified code with inline css:

```bash
npm run build
```

## Artwork Specs

Full column widths and padding the image dimensions needed for full-column graphics are as follows:

| Column Width | Image Size Width |
|--------------|------------------|
| 1/1          | 548px            |
| 1/2          | 264px            |
| 1/3          | ?                |
| 1/4          | ?                |
| 1/5          | ?                |
| 1/6          | ?                |


## Using MailChimp?

Run the following command instead to export any editable rules in `src/mailchimp/editable.css` to the `/dist` source file:

```bash
npm run mailchimp
```

Using MailChimp it is a good idea when setting up new email templates to make use of their templating language to make templates more editable using their interfaces. E.g:
```html
<p mc:edit="body"></p>
```

For more information and details see the MailChimp [Templating Language Guide](http://templates.mailchimp.com/getting-started/template-language/) and [Merge Tags Guide](http://templates.mailchimp.com/getting-started/merge-tags/basic-merge-tags/).
