# Entermedia SCSS Base Project Styles

> This is the official SCSS base project styles for Entermedia. The purpose behind it is to improve the quality of the experiences we build as well as to standardize in order to facilitate more effective collaboration.

[![Support Level](https://img.shields.io/badge/support-active-green.svg)](#support-level) [![MIT License](https://img.shields.io/github/license/Entermedia-LLC/scss.svg)](https://github.com/Entermedia-LLC/scss/blob/main/LICENSE)

## Directory Structure

```
.
├── app                   # Application-specific styles
│   └── themes            # Application-specific themes (ex. light, dark)
│   └── _core.scss        # Should be included in every application-specific stylesheet
│   └── _mixins.scss      # Application-specific Sass mixins
│   └── _variables.scss   # Sass variable overrides & application-specific Sass variables
│   └── base.scss         # Application-specific base HTML stylesheet
├── core                  # Core styles, should never be edited directly!
│   └── themes
│       └── default.scss  # Core application theme
│   └── _core.scss        # Imports core Sass variables & mixins
│   └── _mixins.scss      # Core Sass mixins
│   └── _variables.scss   # Core Sass variables
│   └── _base.scss        # Core base HTML stylesheet
```

## Contributions

We don't know everything! We welcome pull requests and spirited debates :)

## Support Level

**Active:** Entermedia is actively working on this, and we expect to continue work for the foreseeable future including keeping tested up to the most recent Sass & browser versions. Bug reports, feature requests, questions, and pull requests are welcome.
