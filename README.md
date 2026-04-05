# DataScienceYT Project Structure

```
DATASCIENCEYT
│
├── index.html
├── README.md
│
├── assets
│   ├── css
│   │   ├── variables.css
│   │   ├── base.css
│   │   ├── layout.css
│   │   ├── styles.css
│   │   │
│   │   ├── components
│   │   │   ├── buttons.css
│   │   │   ├── cards.css
│   │   │   └── forms.css
│   │   │
│   │   └── sections
│   │       ├── about.css
│   │       ├── home.css
│   │       ├── members.css
│   │       ├── projects.css
│   │       └── research.css
│   │
│   ├── images
│   │   └── home1.jpg
│   │
│   └── js
│
└── sections
    ├── navbar.html
    ├── home.html
    ├── about.html
    ├── research.html
    ├── members.html
    ├── projects.html
    ├── reports.html
    └── join.html
```

## Architecture Overview

### Entry Point

* **index.html**
  * Main container of the application.
  * Dynamically loads sections into the page.

### Sections (HTML Components)
Located in `/sections`
Each file represents a **page module loaded dynamically**:

* `home.html`
* `about.html`
* `research.html`
* `members.html`
* `projects.html`
* `reports.html`
* `join.html`
* `navbar.html` (navigation component)

### Stylesheets

#### Global Styles

Located in:

```
css/
```

* `variables.css` → color palette and design tokens
* `base.css` → resets and typography
* `layout.css` → grid and layout rules
* `styles.css` → global overrides

#### Component Styles

```
css/components/
```

Reusable UI components:

* `buttons.css`
* `cards.css`
* `forms.css`

#### Section Styles

```
css/sections/
```

Page-specific styles:

* `home.css`
* `about.css`
* `members.css`
* `projects.css`
* `research.css`

### Assets

```
images/
```

Images used across the site.

### JavaScript

```
js/
```

Scripts responsible for:
* dynamic section loading
* navigation behavior
* interactivity

