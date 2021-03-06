# Requirements and actions for application

**Reminder**

- Keep it simple until you cant
- dont solve problems you dont have
- dont optimize until you're done
- dont hide text for screen readers that others might use
- composition > inheritance
- functions > classes, but classes arent bad
- usability and scalability > clever code

## REQUIREMENTS

1. [x] All cards begin `face down`.
1. [x] WHEN the first turn begins, the [`Timer` component](../src/components/Timer/Timer.js) will begin counting
1. [x] A turn consists of turning one card face up, and then a second
    - If they match, the pair is removed from play
    - If they do not match, both cards turn back over
1. [x] WHEN no cards remain in play the game ends
1. [x] WHEN then game ends, the timer will stop
1. [x] card data will be fetched from [this url](https://web-code-test-dot-nyt-games-prd.appspot.com/cards.json)

## STAGE 1 completed (moved to COMPLETED.md)

## STAGE 2 completed (moved to COMPLETED.md)

## STAGE 3

- [x] fix bug where cards are clickable during revertDelay
- [x] leader board using persisted storage from stage two
- [x] improved scoring system
- [x] implement a better visual design for all interactions (just focus on mobile and use flexbox, desktop should be easy after) NOTE followup task added, only general blocking/flow was done
- [x] make the card flips animate
- [x] leaderboard now only holds top 3
- [x] cards have ~~dynamic~~ image backrounds (dynamic images from lorem picsum was just extra overhead without a benefit other than seeing cool pictures sometimes. downside was that i couldn't really control for image color or contrast)
- [x] make app look less shitty
- [_] TEST YOUR SHIT (write tests, run audits)
- [_] refactor State management (in progress)
- [_] revisit semantics (in progress)
- [x] refactor User experience
- [x] refactor Overall code clarity and organization

## STAGE 4 (probably not getting here)

- [ ] persist games and game state
- [ ] create unopinionated data format in services to only return requested data
- [ ] fullscreen mode
- [ ] get it on a ghpages site
- [ ] Beat the clock mode
- [ ] local head to head mode
- [ ] local head to head against computer mode

## STAGE 5 (lol, if i really want to push the "no time limit")

- [ ] online play vs person
- [ ] online play of the additional game types
- [ ] local unlimited game that gets harder (using reshuffles and scrolling maybe?)
- [ ] audio (toggle state and files maybe stored in db)
- [ ] social api interaction