# Changelog

## Unreleased

- Move the repository to the GitHub organization `cars-world` and
  rename the package to `@cars-world/cars-client`
- Rename the package to `@rljson/cars-client` and the repo to
  `cars-client`: the build writes `dist/cars-client.js`, the page loads
  it, the container is `cars-client`, and `carsUiRuntimeVersion` is now
  `carsClientVersion`
- Add the page that shows the hello lines: `helloLines()` and
  `showHello()`
- Add the nginx container `cars-ui`; it forwards `/api` to `BFF_URL`
- Keep the package private, off npm
