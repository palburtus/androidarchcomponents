# TDD for MVVM and Databinding in Android
An Android application written in Kotlin built using Test Driven Development (TDD) focusing on MVVM and Databinding using LiveData

The purpose of this project is to demonstrate how Android architecture components can be used in conjunction with Test Driven Development (TDD) in order to provide greater test coverage to UI elements without having to rely and automated test scripts such as Espresso.  This is not to imply that I can or should try to replace automated testing scripts completly but rather how leveraging MVVM and Databinding to layout files can reduce the amount of automation tests that need to be written while also increasing test coverage for UI functionality.  

This project assumes you are at least farmiliar with the concepts TDD, MVVM as an Android architecture component, and LiveData.  I will however be walking you through setting up you project and using these concepts in conjunction with each other.  If you are unfamiliar with MVVM or Databinding in Android I suggest you start by checking out the [Android Developers Documentation for MVVM](https://developer.android.com/topic/libraries/architecture/viewmodel), the [Android Developer Documentation for Data Binding](https://developer.android.com/topic/libraries/data-binding).  If you are unfamiliar with TDD there are endless resources on the web regarding the subject but I personally recommend starting with [The Three Rules of TDD] written by Robert C. Martin (better known as "Uncle Bob" and one of the original authors of the _Agile Manifesto_ and _Design Principles and Design Patters_ which laid out what was later coined the SOLID principle).       

The end product will be a simple news aggregator but the product itself is simple a means to demonstrate the use of these components.  

## Project Setup

**Note:** Setting up DataBinding support to an existing project is often more diffucult than when starting a project from scratch.  For existing projects, please see **TODO add link to section** for details and common issues related to adding data binding to existing Android projects.  

1. Open Android Studio and create a new project, make sure to check the *include Kotlin support* box from the *Create New Project* window
2. From the *Target Android Devices* screen change the minimum Phone and Tablet API to *API 21: Android 5.0 (Lollipop)*.  (API 21 is not the required minimum API for data binding, I am targeting API 21 to reduce the amount of older devices this project needs to support.  If any part of this setup requires a workaround for sub-21 targeted apps I will attempted to point it out and address it.  



