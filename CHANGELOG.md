
## Master

###### Enhancements

* Xcodeproj will automatically utilize the
  [xcproj](https://github.com/0xced/xcproj) command line tool if available in
  the path of the user to touch saved projects. This will result in projects
  serialized in the exact format used by Xcode.


## 0.9.0

###### Enhancements

* Frameworks are added using the last sdks version reported by the xcodebuild if
  the target links against the last SDK.

* Improvements in the handling of file references to frameworks.

* Improvements to the schemes logic.

* Added support for resources bundle targets.

* Project::Group#new_file will now create XCVersionGroup for xcdatamodeld file.

###### Bug Fixes

* The file type of the frameworks file references has be corrected.
