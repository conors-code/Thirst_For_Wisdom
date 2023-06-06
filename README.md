# Game Design Document Season - Thirst for Wisdom
Game Design built on Awesome Ajuna Avatars, for the Ajuna Bounty : Zink Team in The Encode x Polkadot Spring 2023 hackathon
## GAME OVERVIEW
### About
Aimed primarily at late primary & secondary school level (ages 11 – 17) with increasing difficulty,
to make learning competitive and so more interesting. There can be an 18+ for those who have
completed second level schooling too.
Within Awesome Ajuna Avatars (AAA) world, this sets up an incentivised learning gameplay with
forging success based on solving different challenges, quickly. The user selects an avatar to solve
timed challenges that can begin every 12 seconds. A challenge is a set of questions. The initial
library is Mathematics questions, in four topics:
1) arithmetic, i.e. speedwork in +, -, *, /,
2) geometry / trigonometry,
3) probability,
4) algebra.
Separate incentive and even initial introduction can be provided by a purchase (e.g. by parent /
guardian / the cool uncle or aunty) of a stream of claimable prizes, for use in the game. This does
not affect the leaderboard but can make it easier for an avatar to engage in a cross-chain sortie.
Can have centralised initial login, before creation of first keypair for subsequent wallet login.
### Genre
Learn & win
### Platform, Technology Stack
Same as existing Awesome Ajuna Avatars
### Concept Art
Based on the AAA websites style
### Game Flow
### Tiers
For this season, the tiers will be Common, Rare and Legendary (+ elevation to Mythic)
## Key Features
### Forging
Forging is similar to existing AAA, to ensure that the mechanism is familiar to existing users, with
the following specialisations:
* Challenges don’t have time limits (with one exception, see ending below). Higher speed
(lower time to completion) when completing prior challenges gives higher Soul Points when
next forging an AAA.
* “Neighbourliness” is determined by the challenge topics solved by the avatar.
  * Arithmetic is a neighbour of geometry / trigonometry and algebra
  * geometry / trigonometry is a neighbour of Arithmetic and probability
  * Probability is a neighbour of geometry / trigonometry and algebra
  * Algebra is a neighbour of probability and Arithmetic.
* Rare avatars gain one animal each that is associated with wisdom in different cultures: owl,
snake, tortoise, salmon, elephant or fox. These can be traded for other animals – with or
without supplementary BAJU going one way - but cannot be sold just for BAJU.
* Legendary avatars also gain cloaks with cowls and a long staff, reminiscent of herbalists or
wizards/witches. These are in a many colours.
* To attain Mythic status, a Legendary AAA can choose to do more challenges. A random one
will be picked to have a time limit of under the median time of similar challenges completed
by that player. If they complete within the time limit, the AAA evolves into mythic.
As before, the season ends after the 888th* Legendary AAA is forged, once the season ends, no
more minting of AAA is possible, except for free mints. A Legendary AAA is represented by having
each variation represented in its final tier.
Even a Legendary AAA can choose to continue to do more challenges. A random one will be picked
to have a time limit of under the median time of similar challenges completed by that player. If they
complete that challenge within the time limit, the AAA evolves into The Mythic AAA.
### Incentivisation
A “donor” can buy an incentive stream for the young player; a KSM transfer distributed over a
number of iterations that are released as certain block numbers are reached. For the first challenge
that the young person solves after the block, they are notified that they can claim the prize. Upon
claiming,
1) the donor’s address is notified
2) the avatar forays into a KSM world to stake their claim, and then return. For users who have
this, they will see a thin vertical bar on the right of the screen that brightens as the user leaves the
stake without withdrawing. Brightness is dependent on duration of staking without withdrawal, not
the amount staked. Hovering over the bar shows their staking gain and APY.
The donor sees that the person is making use of their present, and so learning.
### Leaderboard & Commendation Board
The leaderboard is led by the users card rarity and SoulPoints.
There is a secondary “Commendation” board for each age, showing the fastest completed set of
challenges for each user, i.e. adding the user’s fastest time for each of the four topics. Lowest time
is first on the Commendation board.
The following all follow the existing AAA mechanisms: Market/Trading, Minting, matching,
Premature Ending, stashing, entity matching score, and Free Mint
