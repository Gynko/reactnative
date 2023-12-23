# Learning React native <!-- omit in toc -->

# Table of content <!-- omit in toc -->

- [1. Introduction](#1-introduction)
  - [1.1. Why react native?](#11-why-react-native)
  - [1.2. Other solutions](#12-other-solutions)
  - [1.3. Pros and cons](#13-pros-and-cons)
- [2. Setup a React native project](#2-setup-a-react-native-project)
- [3. Components and views](#3-components-and-views)

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

# 3. Components and views

Views are the building block of the UI.
They are equivalent to our Html tags, but are specialized for mobile.

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

In React Native, we will use `<Image></Image>`, but under the hood, when exporting in IOS or Android, it will translate in a view that these devices can understand:
![Alt text](image.png)
