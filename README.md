# Learning React native <!-- omit in toc -->

# Table of content <!-- omit in toc -->

- [1. Introduction](#1-introduction)
  - [1.1. Why react native?](#11-why-react-native)
  - [1.2. Other solutions](#12-other-solutions)
  - [1.3. Pros and cons](#13-pros-and-cons)
- [2. Setup a React native project](#2-setup-a-react-native-project)
- [3. Views](#3-views)
  - [3.1. Components](#31-components)
  - [3.2. APIs](#32-apis)

# 1. Introduction

## 1.1. Why react native?

To develop for ios, we need to use Objective C or swift
To develop for android, we need to use Java or Kotlin

So, we needed create code 2 times to have our apps working on both.

React Native is a cross platform solution that allows us to use Javascript to target all devices at the same time.

## 1.2. Other solutions

1. Xamarin
2. Flutter
3. Cordova
4. PWA
5. Ionic

## 1.3. Pros and cons

+: We only have one codebase
-: Will always be slower than a native app built on native device code

# 2. Setup a React native project

# 3. Views

Views are the building block of the UI in React native.
They are equivalent to our Html elements, but are specialized for mobile.

Instead of this:

```jsx
<div>
  <p>Hello world</p>
</div>
```

We will have

```jsx
<View>
  <Text>Hello world</Text>
</View>
```

In React Native, we will for example use the component `<Image></Image>`, but under the hood:

1. When exporting in IOS RN will make it a `<UIImageView></UIImageView>`
2. When exporting to Android, it will make it s `<ImageView></ImageView>`

![Alt text](image.png)

## 3.1. Components

Views are essentially components.
There are several types:

1. Core components
2. Community components
3. Custom components

https://reactnative.dev/docs/components-and-apis

Basic components:
![Alt text](image-1.png)

User interface components:
![Alt text](image-2.png)

There are also components that are android and ios specific,

## 3.2. APIs

React Native APIs are functions/tools that allow us to add special functionality.
For example:
1. 