# Bluff Card Game

A digital implementation of the classic **Bluff (Cheat/Liar)** card game where players attempt to get rid of all their cards by either telling the truth or bluffing about the cards they play.

## 🎯 Objective

Be the first player to get rid of all the cards in your hand.

## 🃏 Game Features

* Standard 52-card deck
* Single-player mode with AI bots
* Support for 2–5 players
* Bluff calling system
* Pass and round-flush mechanics
* Win validation through final bluff checks
* Clean and intuitive user interface

## 📜 Rules Overview

### Starting a Round

The starting player places one or more cards face down and declares a rank (Ace, King, Queen, Jack, or any numbered rank).

Example:

> "Two Kings"

The declared rank may be truthful or a bluff.

### Player Actions

On their turn, a player may:

#### Continue the Claim

* Play one or more cards face down.
* Declare them as the current round's rank.

#### Call Bluff

* Challenge the previous player's claim.
* The pile is revealed and evaluated.

#### Pass

* Skip the turn.
* Cannot play into the current pile again until a new round starts.
* Can still call Bluff later in the round.

### Bluff Resolution

#### If the challenged player lied:

* They take the entire pile.
* The player who called Bluff starts the next round.

#### If the challenged player told the truth:

* The player who called Bluff takes the entire pile.
* The challenged player starts the next round.

### Pile Flushing

If every eligible player passes and nobody calls Bluff:

* The center pile is flushed.
* Flushed cards are removed from play.
* The player who made the last successful play starts the next round.

### Winning

A player wins when they have no cards remaining.

#### Final Play Rule

The final play must survive any bluff challenge:

* If challenged and found to be a bluff, the player takes the pile and continues playing.
* If not challenged, or proven truthful, the player wins immediately.

## 🤖 AI Bots

The game supports AI-controlled opponents that can:

* Make strategic plays
* Decide when to bluff
* Evaluate bluff probabilities
* Call Bluff based on game state
* Adapt their behavior throughout the match

## 🚀 Future Plans

* Real-time multiplayer support
* Online matchmaking
* Player statistics
* Ranked games
* Custom rule variations
* Mobile version

## 🛠️ Tech Stack

* Python
* Object-Oriented Programming
* AI Decision Engine
* GUI Framework (Tkinter / PyQt / Web Frontend)
* Multiplayer Support (Future)

## 📄 License

This project is created for educational and entertainment purposes.
