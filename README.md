#### Imagemagick 7 Buildpack

Purpose

This buildpack is intended to add ImageMagick 7 with heic support to our heroku-16 stack. At this time the heroku-16 stack builds with Imagemagick 6.9 which does not allow for heic/heif support. HEIC/HEIF is a high efficiency image format which is now the default image format setting on new apple devices. This causes errors in our app because heic images cannot be processessed. With heic support we will be able to convert heic images to jpg. As heic/heif format increases in popularity this  issue will become more and more critical.

Things I have tried:

- tried to use existing buildpacks to install imagemagick 7, none of them "worked"
