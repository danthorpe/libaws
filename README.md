Amazon iOS SDK
==============

This repository includes the official Amazon source code, https://github.com/amazonwebservices/aws-sdk-for-ios, as a submodule. Therefore to use it in your own project, first add this repo as a submodule, and then update its submodules, which will result in the 1800 odd source files getting downloaded.

Then add the library target as a dependency, and link to the workspace library in your app's build settings.

I'm going to see if I can work around removing the dependency on SBJSON in the future.