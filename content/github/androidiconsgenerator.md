+++
title="Android Icons Generator"
github_url="https://github.com/SarathBabu/android-icon-generator"
github_image = "/images/github_1.jpg"
+++

In Android application if we want to display an icon on it we need to provide different sized
image of the same icon. Generating those resized icons using Photoshop, Gimp or similar tools
are time consuming and when we need to change the size of the icon we need to redo the same
process again. There are online tools available but that also require uploading of the icon and
downloading the archive and extracting and copying to the project folder.

The Android Icons Generator is a handy tool for developers to create resized icons for Android
applications. The CLI can accept parameters like size (in dp), color (# code) and the name in
which the icon file should generate and it will generate the icons in android specific drawable
directories. The only thing that left for the developer is to copy these folders into the project
directory.

This script uses ImageMagick​ ®​ , so before using this script we need to install ImageMagick​ ®
in the system.