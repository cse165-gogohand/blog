---
layout: post
title: "Progress Update #2"
date: 2024-06-06 16:29:40 -0700
categories: progress
---

Our team continued working on LifeSaver that focuses on Self-Contained
Breeathing Apparatus. Since the deadline is approaching, our team focuses on
critical features based on user story and service blueprint. Also, we are trying
to fit all techincal features in the user story as well.

### System Control

![warning message](/assets/2-warning.png)

Warning message will be displayed when user is near the hot spot. The index will
be calculated based on the distance of each sensors and it will reflect on the
screen.

![menu ui](/assets/2-menu-ui.png)

Menu UI provides multiple tabs so that user can access menu based on the needs.
The exmaple here is SCBA tutorial that we are working on. When the user press
the button, they will move from MR environment to VR and will learn about the
procedure of SCBA.

![sensor menu](/assets/2-sensor-menu.png)

Sensor menu displays sensors in the fields briefly.

We are working on another UI components since we only have a button.

### Travel and Wayfinding

![world miniature](/assets/2-world-in-miniature.png)

We are working on traveling method as world miniature. This feature will be
provided in virtual space so that user can walk around the space using mini
world in the screenshot.


We will work on wayfinding to display where is the nearest safe place when user
had a hazardous situation.

### Hand tracking

![Hand tracking](/assets/2-hand-tracking.png)

User can access the menu by simply seeing the left hand. There will be a timer
when user need to wear SCBA equipment so that they can track how much oxygen
is left in the tank.

### Selection

![selection](/assets/2-selection.png)

User can assess the distance of sensors using special hand gestures. Even though
the hand pose uses OVR Hand Gesture, we implement the viewing mesh by accessing
actual hand skeleton raw position and working as a sort of reversed
flashlight... (our team name is go-go hand though.)

### Manipulation

![manipulation](/assets/2-manipulation.png)

User can pinch and move the sensor. This part uses Occulus hand input data to
detch the pinch and handled in the anchor.

### Symbolic Input

We are researching what we can do for symbolic input especially voice
recognition using Meta SDK. Tentatively, we will apply symbolic input in sensor
name editing and possibly index value change for the presentation.

