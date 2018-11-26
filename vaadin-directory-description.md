[![Build Status](https://travis-ci.org/vaadin/incubator-spreadsheet-light.svg?branch=master)](https://travis-ci.org/vaadin/incubator-spreadsheet-light)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/vaadinincubator-spreadsheet-light)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinincubator-spreadsheet-light.svg)](https://vaadin.com/directory/component/vaadinincubator-spreadsheet-light)
[![Latest Version](https://img.shields.io/vaadin-directory/v/vaadinincubator-spreadsheet-light.svg)](https://vaadin.com/directory/component/vaadinincubator-spreadsheet-light)

# &lt;incubator-spreadsheet-light&gt;

[&lt;incubator-spreadsheet-light&gt;](https://vaadin.com/directory/component/vaadinincubator-element) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/incubator-spreadsheet-light/master/screenshot.png" width="200" alt="Screenshot of incubator-spreadsheet-light">](https://vaadin.com/directory/component/vaadinincubator-element)

## Example Usage

```html
  <incubator-spreadsheet-light header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </incubator-spreadsheet-light>
```
