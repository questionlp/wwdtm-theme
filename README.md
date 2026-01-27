# Wait Wait Stats Project Theme

## Overview

This repository hosts the Sass CSS files that customize Bootstrap for use by the Wait Wait Stats project.

## Usage

The contents of this repository is intended to be used as a submodule for other projects. The projects that use this as a submodule would have the appropriate Node.js packages installed, including [Bootstrap](https://getbootstrap.com/), [Bootstrap Icons](https://icons.getbootstrap.com/), and [Sass](https://sass-lang.com/).

Previous versions of this project included copies of the [IBM Plex](https://github.com/IBM/plex/) fonts release package on GitHub should be stored the `fonts` directory located in the static assets directory for the application as `IBM-Plex-Mono/fonts` and `IBM-Plex-Sans/fonts`.

The current version would require the [@ibm/plex-sans](https://www.npmjs.com/package/@ibm/plex-sans) and [@ibm/plex-mono](https://www.npmjs.com/package/@ibm/plex-mono) fonts to be installed via NPM.

## Contributing

If you would like contribute to this project, please make sure to review both the [Code of Conduct](./CODE_OF_CONDUCT.md) and the [Contributing](./CONTRIBUTING.md) documents in this repository.

### AI Generated Code

Please note that this project does not accept pull requests or bugfixes that include code that has been partially or wholly generated using AI.

## Sponsoring

If you would like to help sponsor the continued development and maintenance of the Wait Wait Stats project, please consider sponsoring me on [GitHub](https://github.com/sponsors/questionlp).

## License and Acknowledgements

The current version of this project has been re-licensed to use the terms of the [MIT License](./LICENSE), unless otherwise noted.

Prior versions of this project had been licensed under the under the terms of the [Apache License 2.0](./LICENSE-APACHE), otherwise noted below.

Additional files that are derived from Bootstrap's `_variables.scss` and `_variables-dark.scss` located under `themes` as `_default.scss` and `_dark.scss` respectively, are licensed under the terms of the [MIT License](https://github.com/twbs/bootstrap/blob/main/LICENSE).

The IBM Plex SCSS files are from the Web font release for version 6.4.0, in which the IBM Plex fonts are distributed under the terms of the [SIL Open Font License, Version 1.1](https://github.com/IBM/plex/blob/v6.4.0/LICENSE.txt).
