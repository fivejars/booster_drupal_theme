# Nav

Documentation and examples for how to use Bootstrap’s included navigation components.

## Bootstrap Documentation

https://getbootstrap.com/docs/5.3/components/navs-tabs/

## Key Features

- **Flexible Alignment**: Supports multiple alignment options including left, right, center, and vertical.
- **Style Variations**: Offers styles such as tabs and pills for different visual appearances.
- **Fill Options**: Includes fill and justify options to control the distribution of navigation items.
- **Utility Class Integration**: Allows for the addition of custom utility classes for further customization.

## Customization Options

- **Alignment Classes**: Adjust the alignment of the nav items based on the provided configuration.
- **Style and Fill**: Customize the nav's appearance by choosing between tabs or pills styles and fill options.
- **Utility Classes**: Apply additional utility classes to enhance or modify the styling and functionality of the nav component.

## Template Structure

- **Dynamic Class Application**: Automatically applies classes based on the specified alignment, style, and fill settings.
- **Item Rendering**: Iterates over navigation items, rendering each with appropriate classes based on its state (active, expanded, etc.).
- **Dropdown Support**: Includes logic for rendering dropdown menus for items with sub-navigation.

## Usage

```twig
  {% include 'radix:nav' with {
    alignment: 'right',
    style: 'pills',
    fill: 'justify',
    items: links,
    container: 'fixed',
    color: 'light',
    navbar_utility_classes: ['bg-light'],
  } %}
```
