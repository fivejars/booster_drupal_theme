# Page

A template for constructing the page layout.

## Key Features

- **Attribute Management**: Includes logic to handle page attributes, ensuring they are correctly applied even if not explicitly set.
- **Utility Class Integration**: Supports the addition of custom utility classes for further customization and styling of the page.
- **Modular Structure**: Divides the page into distinct sections such as header, content, and footer, allowing for easy customization and reuse.

## Customization Options

- **Dynamic CSS Classes**: Customize the appearance of the page with custom CSS classes and utility classes.
- **Flexible Content Blocks**: Utilize blocks for header, content, and footer, offering flexibility in content arrangement and design.

## Template Structure

- **Page Wrapper**: A `<div>` element serves as the main container for the page, with customizable attributes and classes.
- **Header Block**: A dedicated block for the page header, which can be customized or replaced as needed.
- **Content Block**: The main content area of the page, designed to be flexible for various types of content layouts.
- **Footer Block**: A separate block for the page footer, allowing for consistent footer content across the site.

## Usage

```twig
  {% include 'radix:page' with {
    page_attributes: create_attribute({'class': ['custom-class']}),
    page_utility_classes: ['utility-class']
  } %}
```
