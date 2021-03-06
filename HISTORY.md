# History

## 10th April 2020

- Updated README.md for more/components example section

## 9th April 2020

- Updated CMakeLists.txt files to require CMake 3.15

## 7th April 2020

- Added example of using CMake Components in More section
- Added `%cd%` as well as `$(pwd)` to example install instructions

## 29th March 2020

- Updated guidance on CMake `--verbose` flag
- Updated info about `CMAKE_EXPORT_COMPILE_COMMANDS`
- Updated CMakeLists.txt files to require CMake 3.13
- Updated CMakeLists.txt files to use `target_sources`
- Added more CMake YouTube videos to the root README
- Updated Visual Studio examples to use 2019 instead of 2017
- A few other minor tweaks in the README files

## 24th October 2019

- Small updates to `shared` and `shared-export` libraries to include RUNTIME and ARCHIVE locations (CMake picks sensible defaults in later versions but this provides more customization points for users)
- Add link to new CMake video by Craig Scott from CppCon 2019
- Added new line at end of files

## 6th September 2019

- Added more info about installing to custom locations in Install section
- Added miscellaneous section to main README.md with some useful CMake techniques

## 16th June 2019

- Added a new example in `more` section titled `header-only-defines` with an example of using `target_compile_definitions` in the application and `target_compile_features` in the library

## 7th April 2019

- Added a few more links to the main README.md file

## 30th March 2019

- Added experimental `static-auto-install` example
- Reorganised folders to split up core examples from slightly more advanced cases
- Do a pass over READMEs to ensure they are up to date

## 28th March 2019

- Added README for `static-versioned` example and updated comments in `CMakeLists.txt` files for that project

## 24th March 2019

- Added a new example folder `static-versioned` to show an example of setting up a `CMakeLists.txt` file to handle installing multiple versions of the same library

## 15th March 2019

- Added an explanation for the flag `gtest_force_shared_crt` passed to CMake when building Google Test on Windows

## 12th March 2019

- Fixed `.gitattributes` file (finally) to correctly display languages in repo
- Merged PR by 0xflotus to fix a spelling mistake

## 11th March 2019

- Added LICENSE

## 10th March 2019

- Publish!
- Rename `dynamic` to `shared` for more standard naming
- Add `shared-export` example using CMake `GenerateExportHeader` instead of custom export file
