# Snake Game

## Repository
<https://github.com/Gabriela-Montante/ANGM2305-Fall-2026-W1-final-project-Gabriela-Montante.git>

## Description
My Snake Game will allow the user to control a snake and "eat" food particles in order to get a high score. It's relevant because it's a game many people are fond of and it's also one of the classics. 

## Features
- The Snake
	- The user will be able to control a snake with inputs from their keyboard, such as arrows or wasd. The snake will be made by adding particles to a trail for every food eaten. The movement controls will be executed by using the pygame.key module. 
- The food
	- A particle will spawn on the screen at random. This will be executed by making a particle class for the particle. For the spawning, I will be using coordinates and the random module.
- Collisions 
	- The snake has to collide with the walls of the game and itself. This will be executed by using an event loop that contains the position of the snake. 

## Challenges
- I will need to research how I can have the snakes particles build onto its body while also following the main particle aka the head. 
- I will defintely need to learn more about the pygame.key works and its intricacies. 
- I will need to research how I can make it so that the snake dies when it runs into itself. 

## Outcomes
Ideal Outcome:
- I hope that the snakes successfully grows as it eats more food. I am also hoping to be able to let the user choose different types of particles for the food or the color of the snake. 
Minimal Viable Outcome:
- If I am not able to carry out the aesthetic aspects I was hoping for, the game should at least have a snake of one single color that eats a particle of one single drawing and dies if it runs into any of the collisions. 

## Milestones

- Week 1
  1. Make a snake that the user is able to move around
  2. Establish the walls of the game so that I can make it a collision

- Week 2
  1. Create a food particle and have it randomly spawn
  2. Have the snake die if it runs into itself
  3. Have a way to keep track of the users' score

- Week N (Final)
  1. Implement additional code for the snakes aesthetics 
  2. Implement additional code for the foods aestetics
  3. Make sure the game ends when the snakes dies 