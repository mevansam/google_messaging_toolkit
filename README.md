# Google Messaging Toolkit

This plugin implements API to access the following google messaging service via 
simple straight forward integrations. This plugin can be used to create solutions
that integrate with these APIs or simply for integration tests for test cases 
that require sending and receiving messages via email, SMS etc. This plugin 
creates flutter APIs for the following Google messaging APIS.

* Gmail
* Google Voice

## Getting Started

This project is a starting point for a Flutter
[FFI plugin](https://docs.flutter.dev/development/platform-integration/c-interop),
a specialized package that includes native code directly invoked with Dart FFI.

## Project structure

This template uses the following structure:

* `src`: Contains the native source code, and a CmakeFile.txt file for building
  that source code into a dynamic library.

* `lib`: Contains the Dart code that defines the API of the plugin, and which
  calls into the native code using `dart:ffi`.

* platform folders (`android`, `ios`, `windows`, etc.): Contains the build files
  for building and bundling the native code library with the platform application.

