# Boiled Page skiplink singleton

Skliplink SCSS singleton for Boiled Page frontend framework. It is intended to provide a link at the the top of the page that jumps to the main content. The link becomes visible when it receives keyboard focus to help keyboard and screen reader users to go directly to the main content.

## Install

Place `_skiplink.scss` file to `/assets/css/singletons` directory, and add its path to singleton block in `assets/css/app.scss` file.

## Usage

### Classes

Class name | Description | Example
---------- | ----------- | -------
`skiplink` | Applies skiplink. | `<a class="skiplink"></div>`

### Examples

#### Example 1

The following example shows a skiplink. Do not forget to add `main` id to the wrapper of main content to make skiplink working properly.

```html
<a class="skiplink" href="#main">Skip to main content</a>
```
