# iOS app binary size comparison between classes and structs

This is a test project to comparing use of classes or structs on the app binary size. The test contains 250 entities numbered from 1 to 250. Each entity has a reference to the next one and has a mutating function.

- [Structs test file](https://github.com/TParizek/ios-Classes-vs-Structs/blob/2b3d154111d0ee96ce924241cb86371571158fcf/SizeTest/Test.swift)
- [Classes test file](https://github.com/TParizek/ios-Classes-vs-Structs/blob/cd5c74a998968d001409224f2f0c2c08366aba88/SizeTest/Test.swift)

### Results
- Structs IPA - **34KB**
- Classes IPA - **57KB**

Both IPAs are signed using a development certificate and provisioning profile.
