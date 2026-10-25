# CS330-3D-Scene

## Design

My design work on this project started with breaking a complex picture into basic shapes. I looked at each part of the figure, chose the simplest shape that matched it, and grouped the parts by body part: head, torso, arms, and legs. Shades of blue and one shared texture kept the parts distinct from each other.

## Development

I developed the scene incrementally and tested after each change. Each object followed the same sequence in the code being: scale, rotate, translate, then apply color, texture, material, and draw. I grouped the code by body part and added comments so each section could be read and changed on its own. A huge issue came from shape sizes and pivot points that did not match the mesh, and reviewing the mesh source code resolved it.

## Goals

Computational graphics gave me a working understanding of transformations, coordinate systems, cameras, and lighting. These ideas carry into my hobbies such as game development and simulation.
