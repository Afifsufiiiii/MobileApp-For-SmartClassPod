# VESTA Mobile App

A Flutter-based mobile application for **VESTA – Smart Lecture Room**, a smart classroom system designed to monitor classroom conditions and provide manual control of connected features.

## Overview

The VESTA mobile application acts as the user interface for the smart lecture room system.

The application is designed to display classroom information such as:

- Student count and classroom occupancy
- Temperature
- Humidity
- Light level
- System connection status
- Lighting controls
- Music controls
- Classroom announcements

The mobile application will communicate with the Raspberry Pi through a REST API.

## System Flow

```text
Sensors / Camera
       ↓
 Raspberry Pi 5
       ↕
    REST API
       ↕
  Flutter App
       ↓
      User
