# grafxappsllc.github.io

Hosts the app-association files that let a Rolliant station tag open the Rolliant app:

- `.well-known/apple-app-site-association`: iOS Universal Links for `/t/*` (app `MB4Y5TQMM6.com.rolliant.rolliant`)
- `.well-known/assetlinks.json`: Android App Links for `com.rolliant.rolliant` (currently the debug-keystore signing certificate; add the release key's SHA-256 before shipping)
- `t/index.html`: what a phone without the app sees after tapping a station
- `.nojekyll`: stops GitHub's Jekyll build from dropping the `.well-known` folder
