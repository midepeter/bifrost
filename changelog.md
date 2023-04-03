# v0.0.6

## Changed

- Refactored the entire package to use structs as input as opposed to an enumerated list of arguments.
- Updated test cases across all currently supported providers

## New

- added documentation links for each provider to the readme.
- added `doc.md` files to each cloud service provider's package folder to the readme.
- added a comparison of the conventional method with Bifrost's methods for uploading files to GCS and Pinata to the readme.
- Added support for `UploadMultiFiles` function to all currently supported providers.

# v0.0.5

## Changed

- Updated test cases across all currently supported providers
- Updated structs and interfaces as well as their documentation

## New

- added support for uploading single files to Pinata Cloud via the rainbow bridge using the UploadFile function.
- added support for creating a rainbow bridge to link with Pinata Cloud.

# v0.0.4

## Changed

- renamed acl options constants to be more descriptive
- made rainbow bridge interface into an exported component

## New

- added support for passing options to the UploadFile function.
- added support for uploading single files to S3 via the rainbow bridge using the UploadFile function.
- added support for creating a rainbow bridge to link with S3

# v0.0.3

## Changed

- added 'Opt' prefix to options constants to avoid naming collisions and make them more descriptive.

## New

- added contributors section to readme.
- added this changelog file.
- added contributing guidelines.

# v0.0.2

## New

- added Done and Quit channels to UploadedFile struct.
- added UseAsync option to BridgeConfig to allow for async uploads.

# v0.0.1

## New

- added support for passing options to the UploadFile function.
- added support for uploading single files to Google Cloud Storage via the rainbow bridge using the UploadFile function.
- added support for custom bifrost errors.
- added support for creating a rainbow bridge to link with Google Cloud Storage.
