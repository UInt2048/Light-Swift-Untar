# Light Untar
## Functionality
This is a utility written in only 149 lines of Swift to extract tar files with the standard 512-block size, or a multiple thereof, created with the GNU tar command: `tar -cf`.

**Warning:** This code does not support GNU ZIP (gzip) compression, such as `tar -czf`, or non-standard block sizes.

## Example
```swift
FileManager.default.createFilesAndDirectories(path: "file/path/extracted", tarPath: "file/path/42.tar")
```

## Objective-C
This code is a Swift port of [NSFileManager+Tar.m](https://github.com/mhausherr/Light-Untar-for-iOS/blob/b76f908f0a3b2d96ed5909938ab45a329f58cdf2/Light-Untar/NSFileManager%2BTar.m) from Octo's Light Untar for iOS written in Objective-C.

Since this code is NOT visible to Objective-C, if you are looking for an Objective-C version, check it out!
