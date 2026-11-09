# Maya-Stretchy-Limb

## Repository
<Link to your project's public GitHub repository>

## Description
This script will add the ability to squash and stretch a rigged ik limb and maintain volume of the mesh.

## Features
- Feature 1
	- Identifying wrist, shoulder, hip, and knee joints by name
- Feature 2
	- measuring values of joints and controls distance in worldspace
- Feature N 
	- creating math nodes, and using a formula to calculate the squash and stretch and put them into the mesh scale

## Challenges
- Learning Maya specific commands
- Assuring it is usable with a variety of rigs and scenarios

## Outcomes
Ideal Outcome:
- Maintains the fk rig hierarchy
- Adds squash and stretch attribute to the attribute editor

Minimal Viable Outcome:
- adds either squash or stretch capability

## Milestones

- Week 1
  1. Identify joints to add measure locators to and parent
  2. Skin mesh to rig with Python

- Week 2
  1. Create nodes in the node editor using Python
  2. Add squash and stretch attribute to attribute editor

- Week N (Final)
  1. Ensure script works with other rigs and substitute names for non-humanoid rigs with squash and stretch
