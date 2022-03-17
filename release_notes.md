# Release Notes for Changes from Base Product to this Fork

## Steps for releasing/contributing
1. Clone the [repository](https://github.com/r-zane-spalding/react-calendar-timeline/tree/release)
1. Switch to the `release` branch
1. Run `npm install` to get all packages
1. Run `npm test` and 'npm build' to ensure starting point is clean
1. Make changes
1. Run `npm test` and `npm build` again
1. Make changes in change log below, and update version number in `package.json`
1. Run `npm publish --access public` to publish the package (may require `npm login` if first time publishing)

## 0.28.1
* Fixed broken npm package that was missing lib/ directory

## 0.28.0
* Fixed bug with group heights not being able to be set with `height` property.
* Upgraded to React 17
