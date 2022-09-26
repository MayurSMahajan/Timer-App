# timer_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Timer App

The Timer app is a very simple app that acts as a timer for 1 minute. I have created this app to learn more about clean architecture using Flutter BLOC pattern. This is an exercise app for learning Flutter BLOC. 

## About BLOC

### Introduction 
<ul>
<li>
BLoC stands for Business Logic Components. BLOC is widely accepted standard for external state management in Flutter Apps.
</li>
<li>
BLoC stands for Business Logic Components. The gist of BLoC is that everything in the app should be represented as a stream of events: Widgets submit events, and other widgets will respond. BLoC sits in the middle, managing the conversation.
</li>
<li>
It means that a developer must know the state of an app at any time. There should be something displayed on the screen for every interaction with the app to let users know what is happening. 
</li>
</ul>

<img src="assets\images\bloc.png">

### Anatomy Of BLoC

StreamControllers are manager objects that instantiate both a stream and a sink. A sink is the opposite of a stream. You add data to the StreamController using Sink and listen with the Stream.

<img src="assets\images\anatomy.png">









