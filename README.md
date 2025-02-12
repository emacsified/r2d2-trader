![Cover Image](assets/cover.png)
# 🚀 Space Trader API 🛠️ [WIP]
[![Build Status](https://www.travis-ci.com/emacsified/r2d2.svg?branch=master)](https://www.travis-ci.com/emacsified/r2d2)
[![codecov](https://codecov.io/gh/emacsified/r2d2/branch/master/graph/badge.svg?token=4L7QO7TFDX)](https://codecov.io/gh/emacsified/r2d2)
[![Go Report Card](https://goreportcard.com/badge/github.com/emacsified/r2d2)](https://goreportcard.com/report/github.com/emacsified/r2d2)

Space Traders is an API game where players explore the stars in order to exploit for it's riches.

More info available [here](https://spacetraders.io/).

This project provides a golang wrapper for the api.

## 🛠️ Work In Progress
Notice this package is in it's alpha stage and is subject to api changes.

## 🔧 Documentation
- [Event Reference](EVENTS.md)
- [Go Docs](https://pkg.go.dev/github.com/emacsified/r2d2)

## 💾 Models
Most of the objects have been modelled and can be accessed through the model package.

The methods in this wrapper return the relevant model.

## 📔 Examples
- 🎓 [Quick Start](examples/QUICKSTART.md)

## 💻 Contribution
This project is open to contributions.

To contribute follow the standard go style as much as possible and try to achieve an 80% code coverage or higher, with unit tests for the code submitted / changed.

Contributors will be acknowledge in this readme.

## ❤️ Contributors
- [HOWZ1T](https://github.com/HOWZ1T/) - Project Author & Maintainer
- [Trescenzi](https://github.com/trescenzi) - Added Functionality & Fixed Documentation Typo
- [njfox](https://github.com/njfox) - Various fixes & tweaks

## ⚖️ License
This project is licensed under [GNU General Public License v3.0](LICENSE).

## 📝 TODO
- [ ] More Examples
  - [x] Quick Start
- [x] Continuous Integration
- [ ] Unit Tests (Reach at least 80% coverage)
- [x] Documentation
- [x] Event System
- [ ] Events:
  - [ ] Low Fuel
  - [ ] Out Of Fuel
  - [ ] Low Cargo Space
  - [ ] Cargo Full
  - [ ] Low Credits
  - [ ] Out Of Credits
  - [ ] Loan Due