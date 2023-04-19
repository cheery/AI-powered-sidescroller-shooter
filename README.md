# AI-powered sidescroller shooter

Final project for the Building AI course

## Summary

Maximum difficulty that a human player can pass through.
AI-generated levels, AI-controlled enemies for a challenging gameplay.

## Background

I've gotten bored to sidescroller shooters.
I love that genre, but they've become too easy to win.
I play computer games once in a week these days,
but there's not really too many games to play.

Sidescrolling shooters improve motor skills.
People who play action video games learn new sensorimotor skills more
quickly than non-gamers do, [source](https://magazine.scienceconnected.org/2021/05/action-video-games-boost-sensorimotor-skills/).

## How is it used?

The player starts a game, the AI generates a level, using certain rules
and conventions to create an engaging scenery.
Enemies are premade, but they're introduced as game progresses.
Each is controlled by AI, according to certain constraints.
Enemies are taught to learn player's movement patterns,
such that he must vary his playing style constantly.

## Data sources and AI methods

I construct data myself, by playtesting the game and constructing reference
levels for the game to train on.

The project would likely use generative adversarial networks
and some form of reinforcement learning.

## Challenges

Game should not be too hard for human to play.
This have been the stumbling block for this kind of projects for a long time.

Game should have a playtime limiter and a save state system,
to ensure the player keeps proper breaks and curb videogame addiction.

Game needs some sort of basic gameplay elements such as powerups,
and rules on what is destructible and what is not.
And a scoring system.

I doubt there are any negative consequences from releasing such a game,
at least when it's been equipped with aforementioned features.

## What next?

When the project is finished,
I could make generative music tracks that adjust to the gameplay.
Also could try my hand on auto-generating the enemies to the game.

To finish the project, I'd need more knowledge about AI generators.

## Acknowledgments

* Sources of inspiration: RType, Galaga, Gradius, Air fortress
