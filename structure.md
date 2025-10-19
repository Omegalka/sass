# Example of the Structure
There're different structures, it's just for example one of the popular. But any structures are built depending on project and its complexity. It can be mixed varieties and etc.
```
scss/
│
├── base/                 # Base stuff
│   ├── _reset.scss       # reset / normalize
│   ├── _variables.scss   # variables (colors, fonts, breakpoints)
│   ├── _mixins.scss      # functions and mixins
│   ├── _typography.scss  # common typography @font-face and etc
│   ├── _globals.scss     # global styles for body, html
│   └── _index.scss       # build base through @forward
│
├── layout/               # Layouts for re-using on different pages
│   ├── _header.scss
│   ├── _footer.scss
│   ├── _grid.scss        # grid (.container, .row, .col and etc)
│   └── _index.scss
│
├── components/           # Separated components for re-using
│   ├── _buttons.scss
│   ├── _cards.scss
│   ├── _forms.scss
│   └── _index.scss
│
├── sections/             # Sections for landing
│   ├── _hero.scss
│   ├── _features.scss
│   ├── _pricing.scss
│   ├── _testimonials.scss
│   ├── _faq.scss
│   └── _index.scss
│
├── utils/                # Utilities
│   ├── _helpers.scss     # helper classes (.text-center, .mt-20 и т.п.)
│   └── _index.scss
│
└── main.scss             # Main entry
```