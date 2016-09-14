# Musculoskeletal Models -  Muscle Redundancy


## Abstract

### Musculoskeletal models are computational models for testing hypothesis about how humans and other extant vertebrates (animals with backbones or spinal columns) operate their limbs

### This paper explores the hypothesis of muscle redundancy

- Analysis of static muscle operation

- Analysis of dynamic muscle movement for real world tasks

- If sets of muscles are indeed redundant, complex movements such as throwing a frisbee would require an extremely precise synchronization of these muscles - a fact that makes it unlikely that these muscles are indeed redundant

## Introduction

### Trying to understand the interaction among 3 things:

- Model topology: the number and type of connectivity among elements of the model

- Model parameters: the values amount individual and specific numerical values assigned to various model parameters

- The Requirements of real-world tasks for tendon-driven biomechanical systems with many kinematic degrees of freedom and muscles

	- biomechanics systems such as a human arm, or hand

### The classical notion of Muscle Redundancy

- humans have many more muscles than degrees of freedom

	- Humans have many more muscles than seemingly necessary to adequately move their limbs

- The number of possible combinations of muscle tension is theoretically infinite - even the most subtle differences in muscle tension result in different movements of biological limbs

- Some researchers believe that when a human encounters a specific task, the Central Nervous System must solve an optimization problem to choose the BEST muscle activation set among a theoretically infinite set of possibilites

- Others (including this paper’s authors) believe that near- or sub-optimal solutions are good enough for most all tasks 

### The paradox of the redundancy

- Contradicts evolutionary biology

	- It is energetically expensive to develop and maintain muscle mass, so why would the human body waste this energy on maintaining redundant muscles?

- Contradicts the realities of motor dysfunction

	- injury to only a few arm muscles can cause seriously affect ones ability to move that arm

- If we have too many muscles in our limbs, which muscles would you like to donate or paralyze?

### The constraints on limb movement

- The requirements of the task to be accomplished by the limb

	- If you’re punching a punching bag thats 3 feet in front of you, there is a maximum speed and force that your arm muscles can deliver to the bag in one punch.

- The anatomical limits of limbs

	- If the bones from your shoulder to the tip of your middle finger extend out to 3 feet, you can’t punch a punching bag that is standing four feet away.

## Results and Discussion

### Visualizing FFS and FAS demonstrates muscle redundancy

## Kinematics of Muscle Movement

### A matrix of of moment arms r(theta)

- Matrix Rows are joints (i)

- Matrix Columns are muscles (j)

- r(theta)_ij is positive when pulling the jth tendon induces a counterclockwise rotation at the ith joint

### Postural chance is represented as a  change in theta values

- ∆theta = theta - theta0

## Analysis Methods

The purpose of the cat hindlimb analysis is to visualize the structure of the set of feasible muscle activations to produce all maximal and sub maximal force outputs in 3D space

### Feasible Force Set (FFS)

The feasible force set is the set of all possible static force that can be produced by the cat’s hindlimb

- Outputs

	- 3 Forces (FFS)

	- 3 Torques (feasible output torque set)

	- 6 degrees of freedom

- 

### Feasible Activation Set (FAS)

- n-dimensional, where n is the number of independently controlled muscles acting on a limb

- Visualization

	- To visualize the FAS, split up the FAS and visualize each muscle individually

	- For each muscle, a **vectormap** is represented as a colored sphere. This sphere shows the activation level of that muscle on every point in the FFS

		- Color represents the amount of activation

		- Each point on the sphere is a point in the FFS

	- For example, the cat hind limb has 31 muscles. Therefore, there are 31 vector maps of unique muscle activations

### The FFS is produced by the FAS

