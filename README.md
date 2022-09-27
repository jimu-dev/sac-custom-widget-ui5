# Introduction

**Jimu UI5 Widgets** is a set of Custom Widget for [SAP Analytics Cloud](https://www.sap.com/products/technology-platform/cloud-analytics.html).
These Widgets wrap the implementation of [UI5 Web Components](https://sap.github.io/ui5-webcomponents/).
These Widgets expose the properties and events to the SAP Analytics Cloud similar to UI5 Web Components.

List of Widgets in latest version 1.0.0

| Jimu UI5 Widget | UI5 Web Component |
| --- | --- |
| JimuUI5DatePicker | DatePicker |
| | DateRangePicker |
| | DateTimePicker |

# Getting Started

**Upload** the `json` files in this repository to your SAP Analytics Cloud. You can get json files from this github repository, or download directly in [Widgets](#Widgets) Section.

![upload](https://dist.jimuu.dev/sac-jimu/wiki/upload.png "upload")

**Enjoy** the Analytic Application with Jimu UI5 Widgets !

![canvas](https://dist.jimuu.dev/sac-jimu/wiki/canvas.png "canvas")

# Architecture

### Implementation

![implementation](https://dist.jimuu.dev/sac-jimu/wiki/canvas.png "implementation")

Version of UI5 Web Components is [1.7.1](https://www.npmjs.com/package/@ui5/webcomponents/v/1.7.1)

### Deployment

Jimu UI5 Widgets is deployed on a global CDN powered by Alibaba Cloud.
The url and content is fixed, will not change forever.

Released Versions


* 1.0.0 https://dist.jimuu.dev/sac-jimu/jimu-ui5-webcomponents-1.0.0.js

![deployment](https://dist.jimuu.dev/sac-jimu/wiki/canvas.png "deployment")

# Widgets

## JimuUI5DatePicker

A Date Picker widget based on UI5 web components. Integrated the capabilities of DatePicker, DateTimePicker, DateRangePicker in one.

### Install

<https://dist.jimuu.dev/sac-jimu/jimu-ui5-datepicker-1.0.0.json>

### Properties

| property | type | default | description |
| --- | --- | --- | --- |
| width | integer | 256 |  |
| height | integer | 32 |  |
| type | string | datePicker | The type of widget. Enum: datePicker, dateRangePicker, dateTimePicker |
| value | string |  | equivalent to property in ui5-webcomponents |
| formatPattern | string |  | equivalent to property in ui5-webcomponents |
| minDate | string |  | equivalent to property in ui5-webcomponents |
| maxDate | string |  | equivalent to property in ui5-webcomponents |
### Methods

| method | params | type | description |
| --- | --- | --- | --- |
| setValue |  |  | Sets the value |
| | value | string |  |
| getValue |  | string | Returns the value |
| getDateValue |  | Date | Returns the date value |
| getStartDateValue |  | Date | Returns the start date value. When type is dateRangePicker |
| getEndDateValue |  | Date | Returns the end date value. When type is dateRangePicker |
### Events

| event | description |
| --- | --- |
| onChange | equivalent to event in ui5-webcomponents |

# About Us

Contact us by email <support@jimuu.dev>
