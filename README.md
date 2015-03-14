Resolver
========

[![Latest Version](https://img.shields.io/github/release/PACKED-vzw/resolver.svg?style=flat-square)](https://github.com/PACKED-vzw/resolver/releases)
[![Software License](https://img.shields.io/badge/license-GPLv3-brightgreen.svg?style=flat-square)](LICENSE.md)

## About

The Resolver application is a tool for creating, managing, and using *persistent URIs*. More information on the usage of the tool and its purpose can be found on the [wiki](https://github.com/PACKED-vzw/resolver/wiki).

## Installation

See `INSTALL.md` for detailed instructions.

## Contributing

Please fork this project. Contributions are welcome as pull requests.

You can file bug reports and questions in the [issue queue](https://github.com/PACKED-vzw/resolver/issues) of this project.

### Information for developers

The application was built using the [Flask](http://flask.pocoo.org/) microframework, using several common extensions such as `Flask-SQLAlchemy` for interaction with databases, and `Flask-WTF` for form validation. All code is contained inside the `resolver` directory, with all data models inside `resolver/model` and all controller/view functions inside `resolver/controllers`.

To contribute to the application, first follow the installation instructions to set up your development environment. The code is pretty straight-forward and mostly self-explanatory. Flask has some [great documentation](http://flask.pocoo.org/docs/) that should help you getting started in no time.

## License

The application is licensed under GPL3

