# Image Encryption and Decryption Tool

## Overview

This project is a simple image encryption and decryption tool developed during my internship at Prodigy InfoTech. The tool manipulates image pixels through various operations such as swapping pixel values and applying basic mathematical transformations. Users can encrypt and decrypt images by providing the image path, and the processed images are saved with appropriate tags.

## Features

### Image Encryption:

The encryption process alters the pixel values of an image based on predefined operations, such as:

* Swapping pixel values within the image.
* Applying mathematical operations to each pixel value.

The encrypted image is saved with an "_encrypted" tag appended to its name.

### Image Decryption:

The decryption process reverses the encryption operations, restoring the original image. The decrypted image is saved with a "_decrypted" tag appended to its name.

### Usage:

*1. Encrypting an Image:*

* Provide the path to the image you wish to encrypt.
* The tool will process the image and save the encrypted version in the same location with "_encrypted" added to the file name.

*2. Decrypting an Image:*

* Provide the path to the previously encrypted image.
* The tool will process the image and save the decrypted version in the same location with "_decrypted" added to the file name.
