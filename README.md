# Foundation for Emails & MailChimp

## Summary

Built using [Foundation for Emails](http://github.com/zurb/foundation-emails/). The idea behind this repository is to have a centralized version of our marketing emails easily accessible for use either directly or via third party services. Using F4Email setup this is made up of the following:

- **Partials** - Individual reusable components of all layouts
- **Layouts** - These are the core designs
- **Pages** - Individual variations on the overall layouts which are ultimately imported into a service provider.

## Setup

To use this template, your computer needs [Node.js](https://nodejs.org/en/) 0.12 or greater.

**1. Install the Foundation CLI with this command **

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

## Ideas

- [ ] Add more consistent mc:edit labels with `mc:label=""`
- [ ] Strip mc:edit and other mc tags if not using the MC flag
- [ ] Better support for titles and previews.
