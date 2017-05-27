<h1>SASS Architecture</h1>

sass/<br />
|<br />
|– abstracts/<br />
|   |– _variables.scss    # Sass Variables<br />
|   |– _functions.scss    # Sass Functions<br />
|   |– _mixins.scss       # Sass Mixins<br />
|   |– _placeholders.scss # Sass Placeholders<br />
|<br />
|– base/<br />
|   |– _reset.scss        # Reset/normalize<br />
|   |– _typography.scss   # Typography rules<br />
|   …                     # Etc.<br />
|<br />
|– components/<br />
|   |– _buttons.scss      # Buttons<br />
|   |– _carousel.scss     # Carousel<br />
|   |– _cover.scss        # Cover<br />
|   |– _dropdown.scss     # Dropdown<br />
|   …                     # Etc.<br />
|<br />
|– layout/<br />
|   |– _navigation.scss   # Navigation<br />
|   |– _grid.scss         # Grid system<br />
|   |– _header.scss       # Header<br />
|   |– _footer.scss       # Footer<br />
|   |– _sidebar.scss      # Sidebar<br />
|   |– _forms.scss        # Forms<br />
|   …                     # Etc.<br />
|<br />
|– pages/<br />
|   |– _home.scss         # Home specific styles<br />
|   |– _contact.scss      # Contact specific styles<br />
|   …                     # Etc.<br />
|<br />
|– themes/<br />
|   |– _theme.scss        # Default theme<br />
|   |– _admin.scss        # Admin theme<br />
|   …                     # Etc.<br />
|<br />
|– vendors/<br />
|   |– _bootstrap.scss    # Bootstrap<br />
|   |– _jquery-ui.scss    # jQuery UI<br />
|   …                     # Etc.<br />
|<br />
– main.scss              # Main Sass file<br />
<br />
<br />
<h2>Template Architecture</h2><br />
<br />
template/<br />
├── images/<br />
├── assets/<br />
│   ├── sass/<br />
│   ├── js/<br />
│   └── css/<br />
└── index.html<br />
<br />
<h3>Reference</h3><br />
https://sass-guidelin.es/<br />
https://teckstack.com/how-to-configure-sass-for-html-projects<br />
