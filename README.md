wd# sc-interActive-openSrc-201111
This repository documents an open software development process from zero to basic prototype applying TDD.
Not strictly industry standard but rather casual. Intuitive and yet ordered.


##### Analysis

###### The Problem of Operational Blindness in Text Creation Processes

Diving deep into organizing ideas and thoughts can be a rabbit hole in which one quickly loses any ability to get a big picture of what one is working on and where gaps and flaws of new thought structures lie.

 ###### One Solution: The Separation of Modes

The standard solution of waiting to get a fresh eye works but consumes time.

The premise is that it isn't always necessary to sleep overnight to get a more accurate picture of one's work.
Instead, often it could be enough to put oneself in the recipient's situation just by sharing her reading environment.

This corresponds to the idea of the separation of modes Bret Victor talked about, i.a. here: https://www.youtube.com/watch?v=agOdP2Bmieg.

Consequently, it could make sense to separate the mode of creating and the mode of (proof-)reading physically by device.

Therefore, the software system's use case scenario is that the writing happens on a desktop/laptop computer and the proofreading on a mobile touch device.  

To build such a system seems to be of great use.

##### Definition

#### A software system consisting of two applications

1. Writer App

- Features:  

    - Basic Document Management
    - Basic Text Editor
    - Distraction-free write mode
    - Display and edit comments on text passages marked in the reader app  

- Platform: macOS
- Programming language: Swift
- UI framework: SwiftUI


2. Reader App

- Features:  

    - Basic gallery of texts
    - Display texts in a distinct and consistent design
    - Mark text passages with slide gestures
    - Write comments on text passages

- Platform: iOS  
- Programming language: Swift
- UI framework: SwiftUI




- Persistent Storage: Database (Core Data framework)
- Synchronization: iCloud


#### Data Model

![Pic](DataModelDraft201119a.png?raw=true "DataModelDraft201119a")




##### Design

(…)







