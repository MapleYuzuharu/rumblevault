---
{"dg-publish":true,"permalink":"/notation-guide/"}
---

# Maple's RUMBLE Vault Notation
Wanting a robust, extremely clear notation system for my vault, I've modified the existing notation system, building on top of it.
Most rumblers will be able to understand my notation if they know the original notation, but incase you ever get confused, these are the exact specifics of Maple Notation.

**Table of Contents**
- [[NotationGuide#Basic Notation\|Basic Notation]]
- [[#Notation Order|Notation Order]]
- [[#Pre-Game Notation (Shiftstones)|Pre-Game Notation (Shiftstones)]]
- [[#Setup Notation|Setup Notation]]
- [[#! Notation|! Notation]]
- [[#Alternates Notation|Alternates Notation]]
- [[#Vocal Notation|Vocal Notation]]


Disclaimer: While this notation is robust and formal, it should not be expected to be used outside of this vault. It was made for formal documentation, not casual speech.
***
### Basic Notation

**Structures**
s - Any Structure
d - Disc
b - Ball
p - Pillar
c - Cube
w - Wall
o - Boulder

**Modifiers**
S - Straight
P - Parry
K - Kick
H - Hold
U - Uppercut
F - Flick
G - Ground
E - Explode

**Pre-Modified Structures**
where \* is a structure type (e.g \[w\] is a grounded wall).
\[\*\] - Grounded
(\*) - Free
|\*| - Any
{\*} - Moving/Incoming
<\*> - Explosive
^\*^ - Volatile
"\*" - Held
\%\*\% - Flicked
can be combined together:
\[{\*}\] - Moving and grounded.

**Movement**
R - Run
J - Jump
D - Dash
B - Bump yourself with a structure
M - Mount a structure
W - Walk
T - Pivot/Turn
U - Quick Turn (180-turn)
^ - Lock-on Turn

**Special**
g - Guard
JJ - Double Jump with Flowstone
-> - Next Notation Step
! - Placeholder for undocumented notation.
... - Wait
_ - Wait for charge stone proc.
= - Infinitely Repeatable (only at the end of a notation)

**Numbering**
Numbers after a structure during Setup Notation will assign that structure a number.
Numbers after a modifier during Combo Notation will denote which structure to modify.
Numbers after a ' ! ' refers to which note it is.

***
### Notation Order
The order in which notation is built is as follows, left to right:
Flowstones/ Setup -> Combo -> Vocal
' -> ' denotes the transition between these
' / ' after shiftstone notation denotes a game modifier (flowstones/mods/maps)

Using () for placeholders, notation should look something like this:
> [!note] Informal Example
> (Pre-game Specifics) **(Flowstone1)**-**(FlowStone2)**/ (Setup Specifics) -> (Combo) -> "(Vocal)"
***
### Pre-Game Notation (Shiftstones)

The beginning of the notation is usually the shiftstones needed to conduct the combo.
FL - Flowstone
VO - Volatile
CH - Charge
GU - Guard
ST - Stubborn
AD - Adamant
SU - Surge
VI - Vigor
/ - Shiftstones do not matter.
Each will be **bolded** and have a '\*' at the beginning if recommended and not required.
> [!note] Examples
> **CH**/ -> cSU
> Using Charge Stone. Cube then straight then uppercut.
> 
> \***SU**/ -> cSU
> Recommending Surge Stone. Cube then straight then uppercut.
> 
> \***VO**-**CH**/ -> cSU
> Recommending Volatile Stone, using Charge Stone. Cube then straight then uppercut.

You can also include other specific pre-game notations such as the map.
> [!note] Example
> Ring **VO**/ -> cSU

or a specific person (lmao).
> [!note] Example
> "lunamothh" **VO**/ -> dEdbS
> Against lunamothh using Volatile. Disc then explode then d then b then straight.

### Setup Notation

After shiftstone notation is the Setup Notation. This denotes what objects in what conditions should be expected before the combo starts.

Setup notation should include any structures and pre-modified structures to be expected in the combo.

> [!note] Examples
> **CH**/ "c" -> \_SU
> Using Charge Stone. With a held cube, wait for charge stone proc then straight then uppercut.
>
> **F**/ {c/w}1 -> D JJ F1 B
> Using Flowstone. With an incoming cube/wall, dash then double jump then flick the incoming cube/wall then bump.


**You do not ALWAYS need a setup notation!**
For simple combos like ' cSU ' or ' dEdbS ' you do not need to denote structure names since they are consecutive and happen without any waiting or moving.

When no setup phase is present, still put a ' -> ' to show that no setup is required.

> [!note] Example
> **/**/ -> dEdbS
> Disc then explode then d then b then straight.


### ! Notation
' ! ' is used for notes that cannot be annotated with normal notation.
Adding a number at the end will differentiate it from other notes.
> [!note] Example
> **/**/  -> s | c ... DJ F !
> 
> where ! is "move the structure behind and above you".
 

### Alternates Notation
As fun as it would be to have it built into the notation, multiple setups for one combo is too complicated and messy.

Instead, simply write  ' - or - ' and then copy the same combo but with a different setup.
> [!note] Example
> %b1% (s)2 -> S1!2
> \- or -
> %b1% {s}2 -> S1!2
> 
> where ! is "snag the flicked ball on structure 2".


### Vocal Notation
Vocal notation is for something that "must" be said after a combo.
It is a separate, optional transition step, so there must be a second ' -> ' in the notation.
> [!note] Example
> **/**/ -> pUKS -> "Magic Missile!"
> Pillar then uppercut then kick then straight. Say "`Magic Missile!`"
