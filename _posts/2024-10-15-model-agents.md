---
title: "Model Agents: Social Behavior Through the Formal Lens"
date: 2024-10-15 00:00:00 +0000
categories: [Course]
tags: [agent_based_models]     # TAG names should always be lowercase
toc: true
---

The course will offer a dive into the most prominent models for studying social behavior. 
As the saying goes, such models are wrong (i.e., simplifications of reality), but remarkably useful. 
We will study ways to model segregation, the spread of an idea, the dynamics of beliefs and opinions, 
the emergence of cooperation and coordination.

The course will mainly follow Paul Smaldino’s recent book Modeling Social Behavior, 
and will consist of weekly discussions around each chapter. 
The book doubles as a an introduction to agent-based modeling, 
but no coding experience is needed, or assumed, for the course. 
Our primary focus will be the models themselves and what they tell us about reality.

# Announcements
By popular demand, we will be starting the classes at 18:00 sharp, 
rather than with the customary 15 minute delay. 

# Lectures

## Week 1 (October 15, 2024)
We start out by introducing ourselves, followed by a breakdown of the logistics of the course.
Details are found on the slides, [here](/content/teaching/2024-2025-model-agents/00-logistics.pdf).

We followed with a discussion on models in science, and a glimpse of the Netlogo modeling language.
Slides are [here](/content/teaching/2024-2025-model-agents/01-why-model.pdf).

## Week 2 (October 22, 2024)
We covered Chapters 1 and 2 of Smaldino's book. 
The goal was to arrive at a working model for flocking in birds.
We saw how building a model involves starting simple (in Smldino's words, doing 'violence to reality') 
and building things up to the desired effect. 
We also saw how just a few rules can already deliver believable features from the real world.
The slides are [here](/content/teaching/2024-2025-model-agents/02-flocking.pdf).

Historically, one of the first examples of a working flocking algorithm was the Boids model.
For a quick and intuitive overview of this model, watch 
[this YouTube video](https://www.youtube.com/watch?v=4LWmRuB-uNU).

Beatrice pointed out that this is similar to the [Vicsek model](https://en.wikipedia.org/wiki/Vicsek_model) studied by physicists.

There is a great deal of research on how various animals (insects, fish) coordinate their movement.
Sumpter (2010) is a textbook-style work that covers a lot of this.
For brief overviews, see Couzin (2007, 2009).
For a nice glimpse into the research going on this topic in nearby Konstanz, 
check out [this talk](https://www.youtube.com/watch?v=LTVx93IV8Hs) by Iain Couzin himself.

## Week 3 (October 29, 2024)
We study Chapter 3 of Smaldino (2023), which covers the Schelling model of segregation.
This is a model that is more relevant to human social behavior, and provides a mechanism
for generating segregated communities based on local, individual actions rather than 
top-down decisions imposed by an authority.

Slides are [here](/content/teaching/2024-2025-model-agents/03-schelling-segregation.pdf).

If you want to play around with the Schelling model, check out Nicky Case's implementation 
[here](https://ncase.me/polygons/).


## Week 3 (November 5, 2024)
We get a brief glimpse into contagion models, covered in Chapter 4 of Smaldino (2023).
We start with a few simple models, and end with the famous SIR model.
Slides are [here](/content/teaching/2024-2025-model-agents/04-contagion-models.pdf).

For a nice series of simulations on contagions and various interventions, see 
the very nice [video](https://www.youtube.com/watch?v=gxAaO2rsdIs) by 3Blue1Brown.

## Week 4 (November 12, 2024)
We look at a couple of simple, but powerful models of opinion dynamics, 
presented in Chapter 5 of Smaldino (2023).
Simon leads the discussion, and his slides are here.

## Week 5 (November 19, 2024)
We continue our journey into opinion dynamics with a detour into the wisdom of crowds.
We start with Galton's adventures at the Plymouth country fair, where he got a first-hand glimpse into
a group of farmer's ability to guess the weight of an ox, as reported in Galton (1907). 

We then looked at the landmark result in this area, the Condorcet Jury Theorem (CJT).
The obvious question is: what happens if the stringent conditions of the CJT are not satisfied?
In particular, what happens if voters are not independent? This can happen if agents are in a 
social network and communicate with each other.
A particularly nice set of results on the DeGroot model of opinion dynamics comes from Golub & Jackson (2010).

Slides are [here](/content/teaching/2024-2025-model-agents/06-wisdom-of-crowds.pdf)

## Week 6 (November 26, 2024)
We are working towards Chapter 5 of Smaldino (2023), which covers models of the emergence of cooperation.
Before we delve into this topic, we familiarize ourselves with the problem of cooperation and its 
game-theoretic underpinnings.

Adrian presents.

# Bibliography
1. Galton, F. (1907). Vox populi. Nature, 75(7), 450–451.
2. Couzin, I. D. (2007). Collective minds. Nature, 445(7129), 715.
3. Couzin, I. D. (2009). Collective cognition in animal groups. Trends in Cognitive Sciences, 13(1), 36–43.
4. Sumpter, D. J. T. (2010). Collective Animal Behavior. Princeton University Press.
5. Golub, B., & Jackson, M. O. (2010). Naïve Learning in Social Networks and the Wisdom of Crowds. American Economic Journal: Microeconomics, 2(1), 112–149.
6. 3Blue1Brown (Mar 27, 2020). [Simulating an epidemic](https://www.youtube.com/watch?v=gxAaO2rsdIs). YouTube.
7. Smaldino, P. (2023). Modeling Social Behavior. Mathematical and Agent-Based Models of Social Dynamics and Cultural Evolution. Princeton University Press.
