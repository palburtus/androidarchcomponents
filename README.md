# TDD for MVVM and Databinding in Android
An Android application written in Kotlin built using Test Driven Development (TDD) focusing on MVVM and Databinding using LiveData

The purpose of this project is to demonstrate how Android architecture components can be used in conjunction with Test Driven Development (TDD) in order to provide greater test coverage to UI elements without having to rely and automated test scripts such as Espresso.  This is not to imply that I can or should try to replace automated testing scripts completly but rather how leveraging MVVM and Databinding to layout files can reduce the amount of automation tests that need to be written while also increasing test coverage for UI functionality.  

This project assumes you are at least farmiliar with the concepts TDD, MVVM as an Android architecture component, and LiveData.  I will however be walking you through setting up you project and using these concepts in conjunction with each other.  If you are unfamiliar with MVVM or Databinding in Android I suggest you start by checking out the [Android Developers Documentation for MVVM](https://developer.android.com/topic/libraries/architecture/viewmodel), the [Android Developer Documentation for Data Binding](https://developer.android.com/topic/libraries/data-binding).  If you are unfamiliar with TDD there are endless resources on the web regarding the subject but I personally recommend starting with [The Three Rules of TDD] written by Robert C. Martin (better known as "Uncle Bob" and one of the original authors of the _Agile Manifesto_ and _Design Principles and Design Patters_ which laid out what was later coined the SOLID principle).       

The end product will be a simple news aggregator but the product itself is simple a means to demonstrate the use of these components.  

## Project Setup
We will start by going through the steps to create a new Android project 
