# Cellar door

[![Build Status](https://travis-ci.org/nilsnh/cellar-door.svg?branch=master)](https://travis-ci.org/nilsnh/cellar-door) [![dependencies Status](https://david-dm.org/nilsnh/cellar-door/status.svg)](https://david-dm.org/nilsnh/cellar-door) [![codecov](https://codecov.io/gh/nilsnh/cellar-door/branch/master/graph/badge.svg)](https://codecov.io/gh/nilsnh/cellar-door)

Login to services using your own website.

Inspired by the [IndieWeb movement](https://indieweb.org) I wanted to build a well-tested personal authorization server that implements the [IndieAuth protocol](https://indieweb.org/IndieAuth).

Features:

- IndieAuth support.
- [h-card](https://indieweb.org/h-card) support.

## Deploy your own authorization server using glitch.com

1.  [Remix my Glitch app](https://glitch.com/~cellar-door).
2.  Complete the .env file configuration.
3.  Add `<link rel="authorization_endpoint" href="https://your-glitch-app.com">` within the `<head></head>` portion of your personal site's html. This enables sites to discover the authorization endpoint.
4.  Test logging into a site, for example [indielogin.com](https://indielogin.com)

## Development

1.  Remix or git clone this project.
2.  Use command `npm test` to run tests. Or `npm test -- --watch` to start the tests in watch mode.

## License

Project is licensed under [AGPL-3.0](/license.md).
