# Page Content

This template is tailored for the content section of a web page, designed to provide a structured and customizable layout for displaying main content.

## Key Features

- **Content Area Styling**: Includes pre-set and customizable classes to style the main content area.
- **Header and Content Blocks**: Features dedicated blocks for page headers and content, allowing for easy customization and content management.
- **Utility Class Support**: Supports the integration of utility classes for additional styling flexibility.

## Customization Options

- **Main Content Classes**: Customize the styling of the main content area with CSS classes and utility classes.
- **Modular Content Blocks**: Utilize blocks for headers and inner content, offering flexibility in designing and structuring the content layout.

## Template Structure

- **Main Content Wrapper**: A `<main>` element serves as the primary container for the page's content, with customizable attributes and classes.
- **Header Section**: An optional header section within the main content area, useful for titles, breadcrumbs, or introductory content.
- **Content Section**: The core content block of the page, designed to be versatile for various content types and layouts.

## Usage

```twig
  {% include 'radix:page' with {
    content_attributes: create_attribute({'class': ['custom-content-class']}),
    page_main_utility_classes: ['utility-class'],
    page: {
      header: header_content,
      content: main_content
    }
  } %}
```
