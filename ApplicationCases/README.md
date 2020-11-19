# HMS ML Demo

[![License](https://img.shields.io/badge/Docs-hmsguides-brightgreen)](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides-V5/service-introduction-0000001050040017-V5)  ![Android CI](https://github.com/HMS-Core/hms-ml-demo/workflows/Android%20CI/badge.svg)

English | [中文](https://github.com/HMS-Core/hms-ml-demo/blob/master/README_ZH.md)

## Introduction
This project contains apps developed based on HUAWEI ML Kit. The project directory is as follows:

|-- ID-Photo-DIY // Uses the image segmentation function of HUAWEI ML Kit to synthesize static images of people into a certificate photo with a blue or white background.

|-- Smile-Camera // Uses the face detection function of HUAWEI ML Kit to identify whether a user is smiling and capture the smiling photos of the user.

|-- Photo-Translate // Uses the text recognition and translation functions of HUAWEI ML Kit to translate text in static photos into the required language.

|-- ASRSampleKotlin // Uses the automatic speech recognition function of HUAWEI ML Kit to convert speech into text in real time.

|-- TTSSampleKotlin // Uses the text to speech function of HUAWEI ML Kit to convert text into speech and allow users to choose the volume and speed.

|-- TranslatorKotlin // Use the automatic speech recognition, text translation, and  text to speech services of HUAWEI ML Kit to translate English speech into Chinese speech.

|-- PhotoReader // Use the text recognition, text translation, and TTS functions of the HUAWEI ML Kit to obtain text in photos and convert the text into audio output.

|-- Face2D-Sticker // Use the face detection function of the ML Kit to demonstrate 2D stickers.

|-- Receipt-Text-Recognition // ML Kit is used for text recognition and general text recognition.

|-- Skeleton-Camera // Use the bone detection function of the Huawei ML Kit to recognize human body movements and take snapshots.

|-- WoodenMan // The HUAWEI ML Kit supports human body bone detection, image segmentation, and face detection to segment faces and replace background images.

|-- Skeleton-Camera // uses the skeleton detection function of HUAWEI ML Kit to recognize the human movement and match the corresponding action to capture.

|-- CrazyRockets // Use the facial recognition and gesture recognition functions of Huawei ML Kit to move the rocket to avoid obstacles.

|-- CrazyShoppingCart // uses the key point recognition function of Huawei ML Kit to control the movement of the shopping cart to catch dropped items.

|-- Gesture-Change-Background // Use the key point recognition and image segmentation functions of Huawei ML Kit to switch the background by waving your arms.

## Precautions

The project contains multiple independent projects. After downloading code, open the root project and it
will load all sub projects into IDE, you can execute each project individually.

## Precautions

ApplicationCases project contains multiple independent projects. After downloading the code, you need to open the root project and load all nested projects to the IDE. You can run each project independently.

#### Add a project.

The root folder already contains a common build.gradle, which loads the latest Android Gradle plug-ins, AGConnect, and Kotlin to classpath. Therefore, if you add a new project, delete the project's build.gradle file unless you need to add a unique Gradle plug-in for the project. The same applies to `gradle.properties'.

All projects and nested modules are defined in the root `settings.gradle` setting file, new projects are added, all module entries are added to the external setting file, and then the configuration file of the project is deleted.

## Technical Support
If you are still evaluating HMS Core, obtain the latest information about HMS Core and share your insights with other developers at (https://www.reddit.com/r/HuaweiDevelopers/).

If you have any questions about using the HMS sample code, try:
- If you encounter any problem during the development, ask the [Stack Overflow](https://stackoverflow.com/questions/tagged/huawei-mobile-services) under the `huawei-mobile-services' tag. Huawei R&D experts can solve your problem online one-to-one.
- Communicate with other developers in the (https://developer.huawei.com/consumer/cn/forum/blockdisplay?fid=18) HMS Core section of the Huawei Developer Forum.

If you have problems trying the sample code, submit [issue](https://github.com/HMS-Core/hms-ml-demo/issues) to the repository, and you are welcome to submit [Pull Request](https://github.com/HMS-Core/hms-ml-demo/pulls).