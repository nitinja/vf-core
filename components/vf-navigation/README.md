# Navigation component

[![npm version](https://badge.fury.io/js/%40visual-framework%2Fvf-navigation.svg)](https://badge.fury.io/js/%40visual-framework%2Fvf-navigation)

## About

The `vf-navigation` component is a horizontal lise of links to key pages of the website.

## Usage

### Global Navigation

This variant of the `vf-navigation` is to be used as part of the `vf-global-header` to give a few 'quick links' that will be on every page.

### Main Navigation

This variant of the `vf-navigation` can be used to link to sections of the site, or part of the site the parent section.

This is typically placde below the `vf-hero` component but can be also found below the `vf-global-header`.

There should be only one use of `vf-navigation--main` on a page.
## Install

This component is distributed with npm. After [installing npm](https://www.npmjs.com/get-npm), you can install the `vf-navigation` with this command.

```
$ yarn add --dev @visual-framework/vf-navigation
```

### Sass/CSS

The source files included are written in [Sass](http://sass-lang.com)(`scss`). You can point your Sass `include-path` at your `node_modules` directory and import it like this.

```
@import "@visual-framework/vf-navigation/index.scss";
```

Make sure you import Sass requirements along with the modules. You can use a [project boilerplate](https://stable.visual-framework.dev/building/) or the [`vf-sass-starter`](https://stable.visual-framework.dev/components/vf-sass-starter/)

## Help

- [Read the Visual Framework troubleshooting](https://stable.visual-framework.dev/troubleshooting/)
- [Open a ticket](https://github.com/visual-framework/vf-core/issues)
- [Chat on Slack](https://join.slack.com/t/visual-framework/shared_invite/enQtNDAxNzY0NDg4NTY0LWFhMjEwNGY3ZTk3NWYxNWVjOWQ1ZWE4YjViZmY1YjBkMDQxMTNlNjQ0N2ZiMTQ1ZTZiMGM4NjU5Y2E0MjM3ZGQ)
