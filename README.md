# flutter-test


## Before you begin

Read this README completely before starting. There whole content of this document is relevant for the test.

Before you begin, create a new private repository. Once you have finished the test, invite @dmitry-grechko @antero10 as collaborators.


## Introduction

This is the technical test for `flutter` front end developer. It's focused on connecting to `Firebase`, remote sources with a `REST API`, `UX` implementation and `state` managment

## UX 

The wireframe of the app it's located in  https://www.sketch.com/s/5110e2d7-4867-456b-bb88-99ed6b3da378. Ideally, the app should look as it's shown in the wireframe


## State Managment

For the state managment, we don't have any preference for any technology. However, we strongly recommend to use any of theses options: `Redux`, `BLoC` or `Rx`. 



## Description

The idea of the test it's create an app to show our repos `issues`, the app should show all public repositorios that belong to the group `deskree-inc` and should be able to create an issue with the API https://us-central1-deskree-interviews.cloudfunctions.net/api.  This `API` belongs to us, so you're not required to create issues in the github repo. **NOTE**: The `body` of the `issue` it's not predefined. You have the freedom to create your own `issue` object.


For this test, we are going to test our most common features we have for every application we select. The app *MUST* have the following features:

* Login with `Firebase`
* Get `repo` information using `Github API`
* Create `issues` using our `API` 




## General considerations

If you feel the `UX` need more information, feel free to add  any important `feature` you think it's important. We encourage people to do things in their own way.
