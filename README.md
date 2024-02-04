# Cosmic Comparison

**Cosmic Comparison**, first and foremost, is a 3D-simulation to explore the size of objects in the universe. It also calls the OpenAI API, which takes in a user-inputted object (e.g., “Castle”) and asks GPT to return an estimated size for the object. 

## Inspiration


### A Few Core Tenets We Believe In:

- Learning is optimized when play and exploration is encouraged.
- Interactivity is a core principle supporting the joy of learning.
- Programs that look cool are memorable and meaningful!

Also, education in astronomy is undervalued and underdeveloped: we wanted to create a program that inspired a joy for learning that followed these core principles.

## What it does

The API, which we affectionately call “Cosmic Companion,” then returns an estimated size for the object (e.g., 50m) that is used in creating a sphere that matches the size of the object relative to the reference spheres.

- **"Infinite" Zoom**: A unique way to display scale on an enormous level
- **Interfacing with AI**: Allows for an adaptive user experience
- **Size Comparison**: Putting objects seen in our nighttime sky in perspective

## How we built it

- A base 10 logarithmic scaling enables easy traversal across magnitudes.
- Calling the OpenAI API to communicate with Chat GPT; then, using the measurement to create a sphere to add to our model.
- We used Three.js to render 3D models into the simulation.

## Challenges we ran into

3D Modeling and working with Three.js, as well as integrating the OpenAI API.

## Accomplishments that we're proud of

Everything! We worked very hard on this project and it came together in a satisfying way.

## What we learned

A lot - for all of us, it was our first hackathon, so the entire experience was novel and educational.

## What's next for Cosmic Comparison

The stars
