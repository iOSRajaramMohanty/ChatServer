# A simple chat app with SwiftUI and WebSockets - (Swift in the back, Swift in the front!)

<img width="1103" alt="image" src="https://user-images.githubusercontent.com/13145442/237008645-1f122d0c-a779-4b95-b244-230e98313cbd.png">

# Introduction

In this tutorial we'll make a rather primitive, but functional chat app. The app will run on iOS or macOS - or both! The beauty of SwiftUI is how little effort it takes to make a multiplatform app.

Of course, a chat app will have very little use without a server to talk to. Hence we'll be making a very primitive chat server as well, utilizing WebSockets. Everything will be built in Swift and run locally on your machine.

This tutorial assumes you already have a bit of experience developing iOS/macOS apps using SwiftUI. Although concepts will be explained as we go, not everything will be covered in depth. Needless to say, if you type along and follow the steps, by the end of this tutorial you'll have a working chat app (for iOS and/or macOS), that communicates with a server that you also made! You will also have a basic understanding of concepts like server-side Swift and WebSockets.

If none of that interests you, you can always scroll to the end and download the final source code!

# Quick summary of what's to come

In short, we will start by making a very simple, plain, featureless server. We'll build the server as a Swift Package, then add the Vapor web framework as a dependency. This will help us setup a WebSocket server with just a few lines of code.

Afterwards we will start building the frontend chat app. Quickly starting with the basics, then adding features (and necessities) one by one.

Most of our time will be spent working on the app, but we'll be going back and forth between the server code and the app code as we add new features.

# Requirements

macOS 13.3+
Xcode 14.1+
