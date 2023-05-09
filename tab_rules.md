---
title: Rules
layout:  null
tab: true
order: 1
tags: rules-tag
---

## Rules of the game

Cumulus ist trick-taking card game, similar to spades.

The objective is to collect as many points as possible, either by taking a trick or by finding threats.
At the end of the game the winner is the player with the most points.

In preparation of the game an architectural overview is generated.
Ideally, this is in the form of a data flow diagram, but in the end every overview which is understood by the players is fine.
Additionally, the players agree on a starting suit, i.e.
a threat category.

After distributing the cards amongst the players, the game starts.
The first dealer is the player holding the lowest card in the starting suit.
The dealer plays a card in the starting suit.Each other players has to follow the suit during that round.
If that is not possible, the player can choose any card on hand.
The winner of the round takes the trick and is the one who played the highest value card in the round's suit or the highest trump card.

Trumps are cards from the suit *resources*.

The winner then receives a point, starts a new round and chooses the new suit.
Each time a new card is played, all players are asked to think about whether that particular threat, mentioned on the current card, applies to their system in some form.
If a threat is found (and the team agrees that this is a topic to look at),it is written down and the finder receives an extra point.

As Cumulus shares the same rules as Elevation of Privilege and Cornucopia, you can find alternative explanations of the rules [here](https://owasp.org/www-project-cornucopia/) or [here, chapter 2](http://download.microsoft.com/download/F/A/E/FAE1434F-6D22-4581-9804-8B60C04354E4/EoP_Whitepaper.pdf)
