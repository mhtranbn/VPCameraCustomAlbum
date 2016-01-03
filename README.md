# VPCameraCustomAlbum
The easiest way to save your image to the camera roll.

## Usage

```swift
        let image = UIImage(named: "imageName")!
        VPCameraCustomAlbum.sharedAlbum.saveImage(image)
```

Name of the album you can change here:

```swift
   VPCameraCustomAlbum -> static let albumName = "YOUR-ALBUM-NAME"
```

