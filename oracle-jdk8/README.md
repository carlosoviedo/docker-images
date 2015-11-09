# oracle-jdk8

## About this image
Docker file for creating images from debian jessie with oracle jdk8+. If built specifying no arguments (other than the *-t*), 
it will create an image that uses a version of Java 8. It allows building an image that uses any other versions of Java 
provided that you specify:

1. Java version that you want
2. Package version that you want to install

## Build details
Installation of **oracle-jdk8-installer** currently considers recommended packages, which for this package are:

* gsfonts-x11

Image size is of **574.9 MB** (virtual size).

## Tags
The following tags are available for this image:

1. **latest**: same as *0_66*. It exists just as a convenience (to ease pulling the image).
2. **0_66**: builds an image that uses java build version *1.8.0_66*. 
