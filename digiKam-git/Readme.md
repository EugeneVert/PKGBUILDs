PKGBUILD for digiKam master branch, current as of 2022-05-24 (fc2f44b4)
- Replace face detection OpenCV DNN with `lbpcascade_animeface.xml` cascade classifier
  - To use this face detector, copy `lbpcascade_animeface.xml` to subfolder `./facesengine` of digikam database directory
- Disable find_package for ImageMagick
- Disable find_package for Qt6
