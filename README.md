# ImportOK Javascript Example

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/importok/javascript-example?file=index.html)

## Installation

Execute the following commands to install the dependencies. Then you can visit [http://localhost:8080](http://localhost:8080) to access the demo project.

```
npm install
npm run start
```

## Available Examples

This repository includes three example pages demonstrating different use cases of importOK:

### 1. Basic Example (`index.html`)
The main entry point showcasing a simple contact import wizard. This example demonstrates:
- Basic field mapping (first name, last name, email, phone, country)
- Field validation and transformation
- Sample CSV file loading
- Simple callback handling for imported records

### 2. Multiple Resources (`example-multiple-resources.html`)
A comprehensive example demonstrating how to handle different resource types in an e-commerce platform:
- Resource selection cards (Products, Customers, Orders, Inventory)
- Customized field configurations for each resource type
- Modal-based importer interface
- Resource-specific validations and transformers

### 3. Wizard with Progress Bar (`example-wizard-progress-bar.html`)
An enhanced import experience featuring a visual progress indicator:
- Custom progress bar showing the current step (Upload → Map → Review → Import)
- Visual step indicators with active state highlighting
- Professional header and card-based layout
- Integration of the wizard with custom UI components

## FAQs

### Why there is a limit of 20 records?
There is a limit of 20 records for demo purposes. There are no limits in the paid versions, in fact you can enjoy unlimited records and imports.

### Is there a support for Excel?

Yes, there is support for Excel in the paid versions only.

### Can you access my data?

No, in fact we can't even see the data you upload. All operations are performed locally in your browser.

Have more questions? Please [send us a message](https://importok.io/chat)!

## License

This example uses a testing version of importOK, perfect for exploring features and trying things out. When you’re ready to move to production and unlock the full potential of importOK, simply purchase a license at https://importok.io/pricing. 