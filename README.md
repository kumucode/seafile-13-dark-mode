# seafile-13-dark-mode
A clean, fully dark UI theme for Seafile 13 that overrides default styles with a consistent, eye-friendly color scheme while preserving core functionality.

🎯 Key Features
🖤 Full Dark Mode
Deep background tones (#1a1a1a, #2d2d2d)
Soft, readable text (#e0e0e0)
Designed for long sessions without eye fatigue

🎨 Accent Color System
Primary color: orange (#f5a700)
Uses color-mix() for smooth hover and active states
Applied consistently across buttons, links, and highlights

🧩 Bootstrap Integration
Overrides core Bootstrap variables:
--bs-body-bg
--bs-body-color
Borders and UI elements
Keeps layout behavior intact while changing appearance

🧱 What Gets Styled
🧭 Navigation & Layout
Top bars, headers, and side panels
Admin dashboards (system + organization)
File navigation and toolbars

📂 File Browser & Content
Tables and file lists
Shared file views
File preview areas

🧾 Forms & Inputs
Text fields, dropdowns, textareas
Focus states with accent color highlight
Improved contrast for better visibility

🪟 Modals & Popups
Account menus
Dropdowns
Dialog windows

🔘 Buttons
Primary + secondary styles
Hover, active, and disabled states
Consistent dark-friendly behavior

⚠️ What It Doesn’t Touch

To avoid breaking functionality, this theme intentionally skips:

Video players
Audio controls
Media-related UI components

These remain in their default styles for compatibility.

🛠️ Design Approach

This theme uses a targeted override strategy:

No blanket resets
Specific selectors to avoid side effects
Heavy use of !important where necessary to override Seafile defaults

Result: stable and predictable styling

📦 Installation

Copy the CSS file:

seafile-13-dark.css
Add it to your Seafile custom CSS setup (depending on your deployment):
Inject via reverse proxy
Add to custom branding/theme config
Or include in your frontend build
Refresh your browser (clear cache if needed)

💡 Customization

You can easily tweak the theme via CSS variables:

:root {
  --primary-color: #f5a700;
}

Change this to adjust the entire accent system.
