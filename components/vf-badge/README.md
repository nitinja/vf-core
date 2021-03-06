# Badge component

[![npm version](https://badge.fury.io/js/%40visual-framework%2Fvf-badge.svg)](https://badge.fury.io/js/%40visual-framework%2Fvf-badge)

## About

The `vf-badge` component is used to denote if a page, section, or link has a production state of `alpha`, `beta` or other information.

## Usage

The `vf-badge` accepts a single text item of content.

| content type | variable | description |
| ------------ | -------- | ----------- |
| text         | `text`   |             |

### Links

The `vf-badge` component can also be a link using `<a class="vf-badge" href="">badge title</a>`.

### Nunjucks and yml options

#### Nunjucks and YML variables available

| variable       | options                                | default |
| -------------- | -------------------------------------- | ------- |
| text           |                                        |         |
| badge_href     |                                        | null    |
| theme          | 'primary', 'secondary', 'tertiary'     |         |
| style          | 'pill', 'rounded', 'square', 'outline' |         |
| override_class |                                        |         |
| id             |                                        |         |


#### Component Specific Variants

The `vf-badge` allows for two sets of variants

##### Theme Variants

There are three theme variants available for the component that are **primary**, **secondary**, and **tertiary**. To add a theme to the component you would need to add `theme: primary`, `theme: secondary`, or `theme: tertiary` to the `.yml` file.

##### Design Variants

There are four design variants for the component. We have `square`, `pill`, and `rounded` as well as `outline`. The `outline` variant can be used along with another variant so the way we write this in code is a little different. To only have a rounded button we should write `["rounded"]` but if we wanted to have a rounded button with the outline rather than filled colour we would have to write `["outline", "rounded"]`.

## Install

This repository is distributed with [npm](https://www.npmjs.com/). After [installing npm](https://www.npmjs.com/get-npm) and [yarn](https://classic.yarnpkg.com/en/docs/install), you can install `vf-profile` with this command.

```
$ yarn add --dev @visual-framework/vf-badge
```

### Sass/CSS

The style files included are written in [Sass](https://sass-lang.com/). If you're using a VF-core project, you can import it like this:

```
@import "@visual-framework/vf-badge/index.scss";
```

Make sure you import Sass requirements along with the modules. You can use a [project boilerplate](https://stable.visual-framework.dev/building/) or the [`vf-sass-starter`](https://stable.visual-framework.dev/components/vf-sass-starter/)


## Help

- [Read the Visual Framework troubleshooting](https://stable.visual-framework.dev/troubleshooting/)
- [Open a ticket](https://github.com/visual-framework/vf-core/issues)
- [Chat on Slack](https://join.slack.com/t/visual-framework/shared_invite/enQtNDAxNzY0NDg4NTY0LWFhMjEwNGY3ZTk3NWYxNWVjOWQ1ZWE4YjViZmY1YjBkMDQxMTNlNjQ0N2ZiMTQ1ZTZiMGM4NjU5Y2E0MjM3ZGQ)
