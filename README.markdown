# Hunt the Wumpus

## Intro

You're the 10x programmer everybody in Acme Corp turns to when things go wrong.

"Hunt the Wumpus" is Acme Corp's most popular CLI game, but the original author
[Pistacchio][1] has since left the company to follow their dreams of being in
a band.

Github is warning that the `lodash` dependency in "Hunt the Wumpus" is outdated
and has a few vulnerabilities.

## Challenge

Can you update "Hunt the Wumpus" to the latest version of `lodash`? Please?

## Dependencies
* `npm`

## Installation

```
git clone git@github.com:MattHeard/hunt_the_wumpus_node.git hunt
cd hunt
npm ci
```

## Testing
A simple [Jest][2] test suite has been set up, but there are no meaningful tests, yet...

```
npm test
```

## Run the game
The game itself explains how to play.

```
npm run hunt
```

[1]: https://rosettacode.org/mw/index.php?title=Hunt_The_Wumpus/Javascript&oldid=203235
[2]: https://jestjs.io/
