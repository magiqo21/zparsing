<img src="/docs/_static/phimpme-logo.png" align="left" hspace="1" vspace="1">

# Phimp.me iOS

Phimp.me is a Photo App for iOS that aims to replace proprietary photo applications. It offers features such as taking photos, adding filters, editing images and uploading them to social networks.

---

### Features
- [ ] Click beautiful images using the Phimp.me app. Use various advanced scene modes and variety of balance modes.

- [ ] Use your voice actions to invoke Camera, Just say "Hey Siri click a picture". You can also select front and rear camera based on voice.

- [ ] Browse the local gallery inside the app with folder and all photos mode. Copy, move and add a description to the images.

- [ ] Edit images with various cool filters with optimized performance, built using GPUImage framework.

- [ ] Enhance contrast, hue, satur, temp, tint, and sharpness of the image.

- [ ] Use 'Crop and rotate' features from Transform section to get your perfect image.

- [ ] Apply different stickers - facial, express, objects, comments, wishes, emojis, hashtag.

- [ ] Write anything on the images in your handwriting!.

- [ ] Easily go back and forth with 'redo' and 'undo'.

- [ ] Finally, after all this editing you can easily share the image to your favourite social media sites with our easy-to-use sharing feature.

- [ ] Facebook, Twitter, NextCloud, OwnCloud, Imgur, Dropbox, Box, Flickr, Pinterest, Instagram, Whatsapp, and Tumblr - You name it and we have it covered.

---

### Setting up the iOS Project

1. Clone the repo
```
$ git clone https://github.com/imjog/phimpme-iOS.git
```


2. Navigate to the project folder
```
$ cd phimpme-iOS
```

3. Open `Phimpme.xcodeproj` from the folder.

4. Build the project (⌘+B) and check for any errors.

5. Run the app (⌘+R).and test it.

### Screenshots
Following design is using for app development:
<table>
  <tr>
    <td><img src="docs/_static/SplashScreen.png" height = "480" width="270"></td>
    <td><img src="docs/_static/MenuScreen.png" height = "480" width="270"></td>
    <td><img src="docs/_static/GalleryScreen.png" height = "480" width="270"></td>
  </tr>
  <tr>
    <td><img src="docs/_static/CameraScreen.png" height = "480" width="270"></td>
    <td><img src="docs/_static/AccountsScreen.png" height = "480" width="270"></td>
    <td><img src="docs/_static/SettingsScreen.png" height = "480" width="270"></td>
  </tr>
  <tr>
    <td><img src="docs/_static/AlertScreen.png" height = "480" width="270"></td>
    <td><img src="docs/_static/EditingScreen.png" height = "480" width="270"></td>
    <td><img src="docs/_static/ShareScreen.png" height = "480" width="270"></td>
  </tr>
</table>

### Branch Policy

**Note:** For the initialization period all commits go directly to the master branch. In the next stages we follow the branch policy as below:

We have the following branches
* **ipa** - 
All the automatic builds generates, i.e., the ipas go into this branch
* **master** - 
This contains the stable code. After significant features/bugfixes are accumulated on development, we move it to master.
* **development** - 
All development goes on in this branch. If you're making a contribution,
you are supposed to make a pull request to _development_.

### Code practices

Please help us follow the best practice to make it easy for the reviewer as well as the contributor. We want to focus on the code quality more than on managing pull request ethics. 

* Single commit per pull request
* For writing commit messages please read the [COMMITSTYLE](docs/commitStyle.md) carefully. Kindly adhere to the guidelines.
* Follow uniform design practices. The design language must be consistent throughout the app.
* The pull request will not get merged until and unless the commits are squashed. In case there are multiple commits on the PR, the commit author needs to squash them and not the maintainers cherrypicking and merging squashes.
* If the PR is related to any front end change, please attach relevant screenshots in the pull request description.
* Please follow the guides and code standards: [Swift Style Guide](https://github.com/linkedin/swift-style-guide)
* Please follow the good iOS development practices: [iOS Good Practices](https://github.com/futurice/ios-good-practices)

### License

This project is currently licensed under the MIT. A copy of [LICENSE](LICENSE) should be present along with the source code.
