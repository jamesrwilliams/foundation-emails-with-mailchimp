# Fusion Marketing Emails

Built using [Foundation for Emails](http://github.com/zurb/foundation-emails/).

## Summary

The idea behind this repository is to have a centralized version of our marketing emails easily accessible for use either directly or via third party services. Using F4Email setup this is made up of the following:

**Partials** - Individual reusable components of all layouts

**Layouts ** - These are the core designs

**Pages** - Individual variations on the overall layouts which are ultimately imported into a service provider.

## Setup

To use this template, your computer needs [Node.js](https://nodejs.org/en/) 0.12 or greater. The template can be installed with the Foundation CLI, or downloaded and set up manually.

Install the Foundation CLI with this command:

```bash
npm install foundation-cli --global
```
Instal project packages

```bash
npm install
```

## CLI

Preview in development using LiveReload:

```bash
npm start
```

Output to production minified code with inline css):
```bash
npm run build
```

Using MailChimp templates? Run the following command instead to export any editable rules in `src/mailchimp/editable.css` to the `/dist` source file:
```bash
npm run mailchimp
```

### Templating with MailChimp

Using MailChimp it is a good idea when setting up new email templates to make use of their templating language to make templates more editable using their interfaces. E.g:
```html
<p mc:edit="body"></p>
```

For more information and details see the MailChimp [Templating Language Guide](http://templates.mailchimp.com/getting-started/template-language/) and [Merge Tags Guide](http://templates.mailchimp.com/getting-started/merge-tags/basic-merge-tags/).
