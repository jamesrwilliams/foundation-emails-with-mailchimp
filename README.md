# Foundation for Emails & MailChimp

[![devDependency Status](https://david-dm.org/jamesrwilliams/foundation-emails-with-mailchimp.svg)](https://david-dm.org/jamesrwilliams/foundation-emails-with-mailchimp)
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

**Preview in development using live**
```
$ npm start
```
**Output to production minified code with inline css**

```bash
npm run build
```

## Using MailChimp?

Run the following command instead to export any editable rules in `src/mailchimp/editable.css` to the `/dist` source file and use the merge tags for preview and title etc.

```bash
npm run mailchimp
```

### Templating

Using MailChimp it is a good idea when setting up new email templates to make use of their templating language to make templates more editable using their interfaces. E.g: `<p mc:edit="body">`

Quick Links to MailChimp guides:

- [Templating Language Guide](http://templates.mailchimp.com/getting-started/template-language/)
- [Merge Tags Guide](http://templates.mailchimp.com/getting-started/merge-tags/basic-merge-tags/)
- [Merge Tags Cheat Sheet](http://kb.mailchimp.com/merge-tags/all-the-merge-tags-cheat-sheet)
