# FlexiGrid

![GitHub Release Date](https://img.shields.io/github/release-date/AyupDigital/flexigrid.svg)
![GitHub issues](https://img.shields.io/github/issues/AyupDigital/flexigrid.svg)
![GitHub](https://img.shields.io/github/license/AyupDigital/flexigrid.svg)
![npm](https://img.shields.io/npm/dt/@ayup-digital/flexigrid.svg)
![Twitter Follow](https://img.shields.io/twitter/follow/Ayupdigital.svg?style=social)  
This project is a fully working flexbox grid system.
You can find documentation on how to use it [here!](https://ayupdigital.github.io/flexigrid/#) this package is based on [flexicution](http://keenanpayne.com/flexicution/).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing

To use this grid in your project install it via npm!

```
npm i @ayup-digital/flexigrid
```

Get started using the default classes by simply importing the classes file into your sass file.

```
@import "node_modules/@ayup-digital/flexigrid/flexigrid-classes"
```

For details on how to use the classes you can find the documentation [here](https://ayupdigital.github.io/flexigrid/)!

### Contribute!

To make changes to this grid heres how to get set up for developement.

Firstly run to install all of the dependencies:

```
npm install
```

To compile the sass run

```
npm run build
```

Make changes to the site (Built with tailwind)

```
npm run dev
```

Generate documentation site files

```
npm run prod
```

### Deployment

To release a new version to npm and update the tags on git use the below command

```
npm version [version number e.g. 1.0.1] && npm publish && git push --tags
```

## Built With

- [node sass](https://github.com/JeffreyWay/laravel-mix) - Sass build tool
- [Flexicution](http://keenanpayne.com/flexicution/) - Code used as basis
- [Tailwind](https://tailwindcss.com/) - Documentation site CSS framework
- [Webpack](https://webpack.js.org/) - Site build tool

## Authors

- [Elliot Morris](https://github.com/elliotrpmorris/) for [Ayup Digital](https://ayup.agency/)

## License

This project is licensed under the GNU License - see the [LICENSE.md](LICENSE.md) file for details.
