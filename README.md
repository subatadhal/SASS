#SASS Architecture

sass/<br />
|<br />
|– abstracts/<br />
|   |– _variables.scss    # Sass Variables<br />
|   |– _functions.scss    # Sass Functions<br />
|   |– _mixins.scss       # Sass Mixins<br />
|   |– _placeholders.scss # Sass Placeholders<br />
|<br />
|– base/
|   |– _reset.scss        # Reset/normalize
|   |– _typography.scss   # Typography rules
|   …                     # Etc.
|
|– components/
|   |– _buttons.scss      # Buttons
|   |– _carousel.scss     # Carousel
|   |– _cover.scss        # Cover
|   |– _dropdown.scss     # Dropdown
|   …                     # Etc.
|
|– layout/
|   |– _navigation.scss   # Navigation
|   |– _grid.scss         # Grid system
|   |– _header.scss       # Header
|   |– _footer.scss       # Footer
|   |– _sidebar.scss      # Sidebar
|   |– _forms.scss        # Forms
|   …                     # Etc.
|
|– pages/
|   |– _home.scss         # Home specific styles
|   |– _contact.scss      # Contact specific styles
|   …                     # Etc.
|
|– themes/
|   |– _theme.scss        # Default theme
|   |– _admin.scss        # Admin theme
|   …                     # Etc.
|
|– vendors/
|   |– _bootstrap.scss    # Bootstrap
|   |– _jquery-ui.scss    # jQuery UI
|   …                     # Etc.
|
– main.scss              # Main Sass file


#Template Architecture

template/
├── images/
├── assets/
│   ├── sass/
│   ├── js/
│   └── css/
└── index.html

#Reference
https://sass-guidelin.es/
https://teckstack.com/how-to-configure-sass-for-html-projects
