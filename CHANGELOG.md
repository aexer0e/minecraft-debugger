# Changelog

## Version 0.1.0 (September 2021)

- Initial release, connect to Minecraft Bedrock Edition to debug GameTest scripts.

## Version 0.1.2 (March 2022)

- Fixed bug where stale JavaScript threads were not being removed from the UI.

## Version 0.2.0 (April 2022)

- Support for TypeScript debugging.

## Version 0.3.0 (April 2022)

- Better TypeScript support.

## Version 0.3.1 (August 2022)

- Fix bug in source path comparison on Windows due to drive letter capitalization.

## Version 0.4.0 (August 2022)

- Add support for source maps that contain absolute paths.

## Version 0.5.0 (September 2022)

- Changes to the source path location in Minecraft require that localRoot points to a directory with sources, not the pack root. Update your launch.json 'localRoot'.

## Version 0.6.0 (September 2022)

- Add support for external modules while debugging. For JS modules built into Minecraft, stack will be visible but listed as "unknown". Add configuration support for module name mapping.

## Version 0.6.1 (December 2022)

- Better error messaging when source files cannot be discovered.
