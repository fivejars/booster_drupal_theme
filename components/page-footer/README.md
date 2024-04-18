# Page Footer

This template is specifically designed for creating a Page Footer component in your main Page template.

## Key Features

- **Attribute Management**: Facilitates handling footer attributes, ensuring they are correctly applied for customization needs.
- **Utility Class Integration**: Allows for the addition of custom utility classes to further tailor the footer's appearance and functionality.
- **Flexible Footer Content**: Supports dynamic content integration within the footer, making it adaptable to different types of footer designs.

## Customization Options

- **Dynamic CSS Classes**: Customize the appearance of the footer with custom CSS classes and utility classes.
- **Content Flexibility**: Easily integrate various types of content within the footer, allowing for a diverse range of design possibilities.

## Template Structure

- **Footer Wrapper**: A `<footer>` element serves as the main container for the footer, with customizable attributes and classes.
- **Content Container**: Encapsulates footer content within a flexible and responsive container, ideal for aligning and organizing footer elements.
- **Inner Footer Block**: A dedicated block for inner footer content, enabling the insertion of custom content and layout configurations.

## Usage

```twig
  {% include 'your-theme:page-footer-template' with {
    footer_attributes: create_attribute({'class': ['custom-footer-class']}),
    footer_utility_classes: ['utility-class'],
    page: {
      footer: footer_content  # Custom footer content
    }
  } %}
```
