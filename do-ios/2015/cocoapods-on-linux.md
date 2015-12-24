# Bringing CocoaPods to Linux

## Abstract

With Swift coming to Linux, it was clear that we also wanted to be there with CocoaPods, ideally offering a solution for managing dependencies of Swift projects on Linux as early as possible. The main major challenge of this is CocoaPods' historic entanglement with Xcode, a topic which we wanted to resolve for other reasons already (see https://github.com/CocoaPods/CocoaPods/issues/2729). In this talk, we'll learn a lot about Xcode's build system and how we are replacing it with a more direct connection to the build toolchain to break our dependance on Xcode. This talk will also discuss two alternatives to using Xcode as the build system, GNU Makefiles and Facebook's Buck, considering the pros and cons. 

Note: as this project will be tackled over the coming months, some specifics of the talk might have to change in the meantime.

## Outline

- Xcode's build system
- How does CocoaPods interact with it?
- Breaking the strong coupling with a new abstraction
- Discussion of replacement build systems:
	- GNU Makefiles
	- Buck
- Notes on the concrete implementation inside CocoaPods
