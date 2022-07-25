# Introduction

Custom Widget for SAP Analytics Cloud based on UI5 Web Components.

These Custom Widgets expose the properties and events to the Analytic Application similar to UI5 Web Components.

# Getting Started

There is only 1 step you should do before using these Custom Widget:

* Upload the `json` files in this repository to your SAP Analytics Cloud.

Enjoy the Analytic Application with Custom Widget!


# Architecture

Custom Widgets are composed by: 

* json file. A manifest file which should be uploaded to SAP Analytics Cloud
* js file. Implementation JavaScript which is hosted on a gloabal cdn. https://dist.jimuu.dev/sac-jimu/jimu-ui5-webcomponents.bundle-main.js

Here is the high level architecture

![architecture](https://dist.jimuu.dev/sac-jimu/arch.png "architecture")

# Widgets list

| Widget | JSON | Wrapped UI5 Web Componens |
| --- | --- | --- |
| JimuUI5DatePicker | datepicker.json | DatePicker, DateRangePicker |
| JimuUI5DateTimePicker | datetimepicker.json | DateTimePicker |

# Reference

* [SAP Analytics Cloud Custom Widget Developer Guide](https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/0ac8c6754ff84605a4372468d002f2bf/75311f67527c41638ceb89af9cd8af3e.html?locale=en-US)
* [UI5 Web Components](https://sap.github.io/ui5-webcomponents/playground/components)

# About Us

Contact us by email support@jimuu.dev
