# SpoofGuard - Face Anti-Spoofing and Liveness Detection - architecture

A trained model that classifies presentation attacks in real time from the camera stream, distinguishing a live face from print, replay and mask attacks. It sits in front of recognition so a spoofed input is rejected before identity is ever considered.

## Components

### Capture

Real-time camera stream

### Detection model

Trained presentation-attack classifier

### Decision layer

Live or spoof classification before recognition

### Application

Demonstration interface over the model

## Stack

| Layer | Technology |
| --- | --- |
| Vision | Deep learning classification models |
| Runtime | Real-time inference |
| Interface | JavaScript demonstration application |
| Models | Packaged trained weights |

Designed and implemented by Muhammad Tanveer - Full-Stack AI Automation Engineer.