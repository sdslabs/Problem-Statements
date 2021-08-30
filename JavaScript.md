# JavaScript Problem Statement

**Problem Statement:**

You have to create a game from scratch using the canvas2d API. Following are the expectations from the game:

1. Load any kind of game data using AJAX
2. There must be two types of data storage: A persistent data store (using localStorage) and a non-persistent data store (using sessions). You can figure out what data goes into what type of store, for eg: leaderboard in localStorage and current high score in session.
3. Use `requestAnimationFrame` for the render loop
4. At least one keyboard input

**Brownie points:**

1. Store game states separately allowing the user to pause and resume the game anytime
2. Use WebSockets for multiplayer support
3. Implement physics and use a separate loop to calculate physics at each frame
4. Add sounds
5. Use sprite-sheets to load the in-game assets(character animations, other objects, etc)

**Rules:**

1. Only vanilla JS is allowed 
2. try using free asset websites like [itch.io](http://itch.io/), [kenny.nl](http://kenny.nl/) to get free asset sprite-sheets instead of google images

**Resources:**

- Slides: https://slides.com/smithpereira/lecture-on-javascript
- Javascript by [fireship.io](http://fireship.io/) (very fun playlist, and a channel I definitely recommend): https://www.youtube.com/playlist?list=PL0vfts4VzfNixzfaQWwDUg3W5TRbE7CyI
- Playlist on the canvas element (watching all the videos in this playlist is neither recommended nor needed. Just watch the ones that interest you :)) : https://youtube.com/playlist?list=PLpPnRKq7eNW3We9VdCfx9fprhqXHwTPXL
- A nice little video on the internals of JS: https://youtu.be/8aGhZQkoFbQ
- Advanced JS concepts that everyone must know: https://hackernoon.com/12-javascript-concepts-that-will-level-up-your-development-skills-b37d16ad7104
- Basic JS game : https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript
- Cookies vs localstorage : https://medium.com/swlh/cookies-vs-localstorage-whats-the-difference-d99f0eb09b44
- Also, since you are making a game, We'd really recommend giving this video a watch: https://www.youtube.com/watch?v=Fy0aCDmgnxg

[Here](https://github.com/rohithvarma3000/pingpong) is a submission by a SDSLabs member that you could check out for reference.
