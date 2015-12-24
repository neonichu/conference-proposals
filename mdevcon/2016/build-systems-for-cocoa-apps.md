# Build Systems for Cocoa Applications

In this talk, we will take a look at the different available systems for building applications for the various Apple platforms. For a while, some people have been unsatisfied with Xcode as a build system, leading to alternatives like Facebook's Buck being developed. With the open source release of Swift, llbuild has also entered the scene as a build system for applications written purely in Swift. Since the build system is not something most of us know too much about, but nevertheless can cause us to be unable to ship our apps if it breaks, it makes sense to take a closer look and learn how to conscientiously choose our tools and know better why they break and how to fix issues.

## Outline

- General introduction to build systems
- Compilation
- Linking
- Assembling a build product
- How do different build system implements this? (Xcode, Buck, llbuild)
- What is available on other platforms?
