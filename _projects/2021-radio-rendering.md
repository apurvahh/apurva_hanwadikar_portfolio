---
layout: project
title: Electrical Core for Mars Rover
description: Electrical Integration CAD Project
technologies: [Autodesk Inventor]
image: /assets/images/Screenshot 2025-05-13 at 19.15.45.png
---



Goals: Making sure all the boards are accessible (easy to plug in and pull out), don't move around when the rover moves, protects all the cables, and prevents dust from coming in. The entire ecore should also be easy to pull out and adjust and it should be well protected in the frame. 

1	Outside frame should be waterjettable/laser cuttable - must be a plane
2	Outside frame should fit in the rover frame	less than 24 in by 24 in
3	All support components should be thick enough to be 3d printable (thickness greater than 0.1 in)
4	Should have connections going outside for all subsystems that need it
5	Ecore must be easy to lift and pull out
6	Wiring should be well organized and things that need to be wired together should be kept close together
7	Nothing is lose when the rover is in motion

Version 1:
- Polycarbonate outer box connected like puzzle pieces
- All the boards slide into the slots
- Base has a pegboard design
- More supports to prevent the box from breaking easily
- Minimal holes on the outside - suspension connectors are the only parts exposed on the sides

Changes from CDR/Things I’ve Learned Since Building Version 1
- Supports could be better designed because they are hard to line up
- Box can be sized down and the height can be reduced a little
- Make the box one part file

Integration
- With the frame: 
- Fits within the frame width, length, and height
- With suspension:
- Connectors for each part
- Opening for camera mast
- Through the side of the frame
- Astrotech: Mixing will have an opening on the side 
    - Everything else will have an opening from the bottom 


Testing
- Ecore needs to stay together without any electrical components moving - this requires making sure that mounting stays together when the rover is in motion. 
- Managing overheating - this would just include turning everything on and observing how the components are doing
- Testing relies on other subsystems being assembled and ready to electrically connect


