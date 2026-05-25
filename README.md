<img width="1676" height="869" alt="jt-accordion-module" src="https://github.com/user-attachments/assets/0847d30b-4d9c-4588-8f07-9b5ec056c17e" />


# JoomTheme Image Accordion

**JoomTheme Image Accordion** is a responsive image accordion module for Joomla 6.x with Bootstrap 5 modal support.

It allows you to create hover-based image accordion cards with images, titles, descriptions, buttons, and modal content directly from the Joomla module manager.

Developed by [JoomTheme](https://joomtheme.com).

---

## Features

- Joomla 6.x compatible site module
- Responsive image accordion layout
- Hover and focus accordion animation
- Image grayscale-to-color hover effect
- Button-based Bootstrap 5 modal support
- Diagonal modal opening animation
- Repeatable card fields using Joomla subform
- Image, title, description, button text, button style, modal title, and modal content fields
- Bootstrap 5 button style options
- Turkish and English language files
- Joomla Web Asset Manager support
- Joomla update server support
- Changelog XML support

---

## Requirements

- Joomla 6.x
- PHP 8.3 or later
- Bootstrap 5 supported Joomla template

---

## Installation

Download the latest release package:

```text
mod_jt_image_accordion_v0.2.0.zip
```

Install it from Joomla Administrator:

```text
System → Install → Extensions → Upload Package File
```

After installation, create and publish the module from:

```text
Content → Site Modules → New → JoomTheme Image Accordion
```

---

## Module Fields

Each accordion item can be managed from the module settings.

Available card fields:

- Image
- Image alt text
- Title
- Description
- Button text
- Button style
- Modal title
- Modal content

---

## Button Styles

The module supports Bootstrap 5 button classes:

- Primary
- Secondary
- Success
- Danger
- Warning
- Info
- Light
- Dark
- Outline Primary
- Outline Secondary
- Outline Success
- Outline Danger
- Outline Warning
- Outline Info
- Outline Light
- Outline Dark

---

## Update Server

This extension includes Joomla update server metadata.

Update XML:

```text
https://raw.githubusercontent.com/joomtheme/mod-jt-image-accordion/main/updates/update.xml
```

Changelog XML:

```text
https://raw.githubusercontent.com/joomtheme/mod-jt-image-accordion/main/updates/changelog.xml
```

---

## Folder Structure

```text
mod_jt_image_accordion/
├── mod_jt_image_accordion.xml
├── services/
│   └── provider.php
├── src/
│   └── Dispatcher/
│       └── Dispatcher.php
├── tmpl/
│   └── default.php
├── media/
│   ├── joomla.asset.json
│   ├── css/
│   │   └── accordion.css
│   └── js/
│       └── accordion.js
├── language/
│   ├── en-GB/
│   │   ├── mod_jt_image_accordion.ini
│   │   └── mod_jt_image_accordion.sys.ini
│   └── tr-TR/
│       ├── mod_jt_image_accordion.ini
│       └── mod_jt_image_accordion.sys.ini
└── updates/
    ├── update.xml
    └── changelog.xml
```

## Support

For support, contact:

**Email:** support@joomtheme.com  
**Website:** [https://joomtheme.com](https://joomtheme.com)

---

## License

GNU General Public License version 2 or later.

See [LICENSE](LICENSE) for details.

---

## Credits

Developed by [JoomTheme](https://joomtheme.com).
