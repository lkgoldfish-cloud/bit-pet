# BIT Pet Project

## Project Goal

This repository contains a small Tamagotchi-style digital pet game called **BIT**.

The game should make the player feel that BIT is a small digital lifeform that continues to exist even when the player is away.

The main emotional goals are:

- attachment to the creature
- curiosity about what BIT did while the player was away
- visible personality differences caused by player behavior
- short, comfortable play sessions
- cute and friendly interactions rather than stressful pet management

## Current Platform

The current MVP is a browser game deployed with GitHub Pages.

Use:

- HTML
- CSS
- vanilla JavaScript
- localStorage for local save data

Do not introduce frameworks, servers, databases, accounts, or external dependencies unless they are clearly necessary.

This is primarily a **solo-development project**, so implementation complexity must remain small.

## Core Game Loop

The basic loop is:

FEED → PLAY → SYNC → player leaves → BIT lives automatically → player returns → OFFLINE LOG

Do not add features that weaken or distract from this loop without discussing them first.

## BIT

BIT is a cute digital lifeform.

Growth concept:

DATA CORE → BIT → NODE → final evolution

Player behavior should influence personality and future evolution.

BIT should feel alive through:

- idle movement
- spontaneous reactions
- facial expressions
- short signals
- offline behavior
- remembering recent player actions

## Visual Direction

BIT must always be cute and friendly.

Prefer:

- round shapes
- large simple eyes
- short limbs
- pastel colors
- pixels
- signals
- packets
- soft glow
- playful digital effects

Avoid:

- gore
- body horror
- disturbing glitches
- realistic teeth
- grotesque anatomy
- aggressive horror imagery
- excessively dark cyberpunk visuals

Even unusual evolutions such as NULL must remain cute.

## FEED

BIT consumes digital DATA rather than ordinary food.

Current DATA concepts include:

- PLAY.dat
- HEART.dat
- INFO.dat
- MUSIC.dat
- MYSTERY.dat

DATA may influence hidden personality values.

Possible personality axes include:

- ACT
- LINK
- LOGIC
- NULL

Do not expose every hidden value directly to the player.

## PLAY

The main current play interaction is DATA BALL.

PLAY should focus on BIT reactions rather than scores or difficult minigames.

Avoid adding unnecessary competitive systems.

## SYNC

SYNC is the main communication system.

Do not replace it with a generic petting system.

BIT communicates using digital signals and packets.

Typical player responses include:

- ♡
- ♪
- ?

There is no single correct response.

Repeated player choices should gradually influence BIT's personality.

BIT's communication ability may evolve from:

010 / symbols → words → short sentences

## Offline Life

There is no manual EXPLORE button.

When the player leaves, BIT continues its own life.

On return, show an OFFLINE LOG containing events such as:

- sleeping
- playing alone
- exploring
- finding DATA
- detecting strange signals

Long absence should not kill BIT or cause severe punishment.

The player should be curious to return, not afraid of returning.

## UI

Keep the main screen simple.

BIT should occupy most of the screen.

Primary actions:

FEED  
PLAY  
SYNC

Avoid turning the interface into a spreadsheet of stats.

When status information is needed, prefer a digital SYSTEM SCAN style over exact numbers.

## Tutorial

The current tutorial should teach the game through actual interaction.

Preferred flow:

FEED → PLAY → SYNC → free play

Avoid long mandatory explanations.

Help information may remain available separately.

## Development Rules

Before modifying code:

1. Inspect the existing implementation.
2. Understand how the requested feature interacts with current systems.
3. Make the smallest reasonable change.
4. Preserve existing working behavior unless a change is intentional.
5. Run or inspect the result after modification.
6. Check for JavaScript errors.
7. Check mobile layout.
8. Check localStorage compatibility.
9. Check that GitHub Pages can still run the project.

Do not perform large refactors unless there is a clear benefit.

Prefer working code over premature architecture.

## Scope Control

Do not add the following unless explicitly requested:

- multiplayer
- accounts
- login
- backend servers
- gacha
- ads
- monetization
- rankings
- combat
- large maps
- complex inventories
- social systems

Always consider implementation effort before suggesting new features.

## Current Development Priority

Current priority order:

1. Make BIT feel alive.
2. Improve FEED, PLAY, and SYNC.
3. Improve offline behavior.
4. Stabilize saving and elapsed-time calculations.
5. Add growth.
6. Add DATA CORE birth sequence.
7. Add naming.
8. Add personality-driven evolution.
9. Add final evolution forms.

Do not expand content significantly before the MVP loop feels enjoyable.

## When Completing a Task

Briefly report:

- what changed
- which files changed
- what was tested
- any remaining issues
- a sensible next step

If a requested feature would significantly increase project complexity, explain that before implementing it.
