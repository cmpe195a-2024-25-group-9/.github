# Vocast

SJSU, Spring 2025, Group #9 senior project.

Team members:
- Fardin
- Ayman
- Praveen
- Mohd

## Overview
Vocast is a audio streaming system meant for students in large lecture halls. Ever tried participating in a large lecture hall? It's often difficult to project your voice and hear others in a large halls. The only way to be heard is to pass around
a mic which is certainly not convenient. 
<br> <br>
So we developed Vocast to act as a distributed microphone system. Instead of having to pass around a mic, you can use your laptop as one. The Vocast system consists of a website and base station that are needed to hold sessions. Through the website, 
users are able to join sessions their professors host. Users in a session can now interface with the base station that serves audio streams and plays them out to speakers/ headphones. 

## Check Out the Code
the following [repositories](https://github.com/orgs/cmpe195a-2024-25-group-9/repositories) in this organization include:
- `vocast_web`: the Vocast website that users can interact with
- `vocast_backend`: the backend code used to handle admin operations, IoT networking, mic stream forwarding, etc.
- `vocast_embedded`: the embedded code running on the base station to serve audio stream requests
- `vocast_app`: the mobile app version of vocast
- `c195-group-9-vocast-pcb`: the pcb design for the base station
