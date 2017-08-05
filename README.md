# React Native Learning Guide

### Installation and Creating First React Native App

https://github.com/react-community/create-react-native-app#getting-started

#### Run application on Android simulator

npm run android

#### Run on IOS simulator

npm run ios

#### Expo
https://itunes.apple.com/app/apple-store/id982107779
https://play.google.com/store/apps/details?id=host.exp.exponent

### Hello World Tutorial

https://facebook.github.io/react-native/docs/tutorial.html

#### Components

A component can be pretty simple - the only thing that's 
required is a render function which returns some JSX to render.

#### Props

Most components can be customized when they are created, 
with different parameters. These creation parameters are 
called props.


#### State

There are two types of data that control a component: 
props and state. props are set by the parent and they are 
fixed throughout the lifetime of a component. For data that
is going to change, we have to use state.


#### Style

With React Native, you don't use a special language or syntax
for defining styles. You just style your application using
JavaScript. All of the core components accept a prop named
style. The style names and values usually match how CSS works
on the web, except names are written using camel casing, e.g
backgroundColor rather than background-color.

One common pattern is to make your component accept a style 
prop which in turn is used to style subcomponents. You can use
this to make styles "cascade" the way they do in CSS.



#### ES2015

https://babeljs.io/learn-es2015/
