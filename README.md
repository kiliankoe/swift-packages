# Swift Packages
A manually Curated List of Swift packages that build with the [Swift Package Manager](https://github.com/apple/swift-package-manager).  As described [here](https://github.com/apple/swift-package-manager/blob/master/Documentation/PackageManagerCommunityProposal.md#a-package-index), a package index for Swift packages is a long-term goal for the Swift Package Manager.  In the mean time, this temporary list of valid and maintained Swift packages can serve as something of an index.  Note that this index will *only* contain Swift projects that are packages that build using the Swift Package Manager.

## Contributing
At this time, finding Swift packages seems a bit slim.  Thus, contributions to this list are very welcome!
### To Add a Package:
Submit a pull request! Before submitting a pull request to add a packager, make sure that the repository you are linking to includes a `Package.swift` file, builds with the Swift Package Manager, and is useful to the community at large.
### If a Package Doesn't Build
In addition to creating an issue on the package's repository, feel free to also file an issue here, detailing under what conditions the package doesn't build for you.  Packages that do not build on a common platform for an extended period of time will be removed.
### To Remove a Package:
If you believe a package should not be on this list because it no longer serves a significant use to the Swift community, create an issue explaining your opinion.

## Packages
### Cross-Platform
*May or may not currently build cross-platform, but reasonably could be.*
- [Commander](https://github.com/kylef/Commander) - Great for making command line interfaces in Swift.
- [Punctual](https://github.com/harlanhaskins/Punctual.swift) - Extensions to NSDate APIs to make them friendlier.
- [Regex](https://github.com/sharplet/Regex) - Convenient regular expressions in Swift, making use of NSRegularExpression.
- [shuffle](https://github.com/glessard/shuffle) - Lazy shuffling of arrays.
- [SwiftFoundation](https://github.com/PureSwift/SwiftFoundation) - Cross-Platform, Protocol-Oriented Programming base library to complement the Swift Standard Library.
- [SwiftSequence](https://github.com/oisdk/SwiftSequence) - A framework of extensions for Sequences, inspired by Python's itertools, Haskell's standard library, and other things
- [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - JSON handling in Swift.
- [swift-parser-generator](https://github.com/pixelspark/swift-parser-generator) - Parser generator

### Darwin Specific (OS X, iOS, watchOS, tvOS)
- [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) - Swift wrapper around Keychain for iOS and OS X.
- [SwiftHEXColors](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor.

### Linux Specific
- [SwiftBlueZ](https://github.com/PureSwift/SwiftBlueZ) - Swift wrapper for Linux Bluetooth C API (BlueZ)
