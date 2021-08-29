# Lets-Chat

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
## Packages Used
### 1.cloud_firestore:
      A Flutter plugin to use the Cloud Firestore API.\
      To start using the Cloud Firestore package within your project, import it at the top of your project files:
        import 'package:cloud_firestore/cloud_firestore.dart';
        Before using Firestore, you must first have ensured you have initialized FlutterFire.
### 2.firebase_core:
      A Flutter plugin to use the Firebase Core API, which enables connecting to multiple Firebase apps.
      The firebase_core plugin is responsible for connecting your Flutter app to your Firebase project. The plugin must be installed and initialized before the usage of       any other FlutterFire plugins. It provides basic functionality such as:
            ->Initializing FlutterFire.
            ->Creating Secondary Firebase App Instances.
      Import the plugin by adding this to your file
       import 'package:firebase_core/firebase_core.dart';
 ### 3.firebase_auth:
      A Flutter plugin to use the Firebase Authentication API.
      Once installed, you can access the firebase_auth plugin by importing it in your Dart code:
      import 'package:firebase_auth/firebase_auth.dart';
 ### 4.image_picker
      A Flutter plugin for iOS and Android for picking images from the image library, and taking new pictures with the camera.
      In your Dart code, you can use:
        import 'package:image_picker/image_picker.dart';
 ### 5.firebase_storage:
      A Flutter plugin to use the Firebase Cloud Storage API.
      To start using the Cloud Storage package within your project, import it at the top of your project files:
        import 'package:firebase_storage/firebase_storage.dart' as firebase_storage;
 ### 6.firebase_messaging:
      A Flutter plugin to use the Firebase Cloud Messaging API.
      To start using the Cloud Messaging package within your project, import it at the top of your project files:
          import 'package:firebase_messaging/firebase_messaging.dart';
       
