OVERVIEW

This stylesheet overrides Seafile’s default UI with a consistent dark color scheme while preserving layout and functionality. It uses targeted selectors and CSS variables to avoid unintended side effects.

FEATURES

Full dark mode with balanced contrast
Orange accent color with dynamic hover/active states
Bootstrap variable overrides for seamless integration
Consistent styling across navigation, file views, admin panels, and modals
Improved readability for text, tables, and forms
Preserves media player and video components

WHAT'S STYLED 

Navigation bars, headers, and side panels
File browser, tables, and shared views
Forms, inputs, and dropdowns
Buttons and modals

DESIGN APPROACH

Targeted overrides instead of global resets
Minimal disruption to existing UI behavior
Uses !important where necessary for reliability

INSTALATION

Copy the CSS file:
seafile-13-dark.css
Add it to your Seafile custom styling setup
Refresh the browser (clear cache if needed)

Customization

Edit the primary color:

:root {
  --primary-color: #f5a700;
}
Notes

This theme is designed for everyday use, prioritizing clarity and stability over visual complexity.
