# The Goal

- Pairing
- Test driving
- Refactoring

# The Format

We have a deck of features to implement:

1. A pair starts off on the first feature
2. We switch one member of the pair every X minutes
3. Go back to step 2

# Kata

Given a list of poker hands, figure out what they are worth and figure out the winner.

See [original kata](http://codingdojo.org/cgi-bin/wiki.pl?KataTexasHoldEm).

## Example Input / Output

Given this:

    Kc 9s Ks Kd 9d
    8c Ah Qs Qd 8d
    Ac Qc Js Jd 7d
    9h 5s 7c Qh 4h
    4d 2d 3d Ad Td
    7s Ts 6s 6d 9c

Your program should output this:

    Kc 9s Ks Kd 9d Full House (winner)
    8c Ah Qs Qd 8d Two Pair
    Ac Qc Js Jd 7d Pair
    9h 5s 7c Qh 4h High Card
    4d 2d 3d Ad Td Flush
    7s Ts 6s 6d 9c Pair

## Poker Hand Rankings
![](poker-rankings.png)

Source: [pokerlistings.com](http://www.pokerlistings.com/poker-hand-ranking)
