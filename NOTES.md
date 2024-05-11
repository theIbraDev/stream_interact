# Stream entertainment app

api's
[Youtube chat](https://developers.google.com/youtube/v3/live/docs/liveChatMessages)
[Twitch chat](https://dev.twitch.tv/docs/api/reference)
[Twitch irc](https://dev.twitch.tv/docs/irc/)

Research:
Tauri
Rocket
Rust ability for this

## Desired setup experience
1. Run the program
2. Terminal asks, 'what platforms do you stream on?'
3. One after one, you get asked to paste each relevant api token,
based on the choices made in #2
4. These tokens are remembered, and stored locally, in a readable file. (Allow user so edit this via editor)
5. Where does this now deploy? Locally on the browser? Browser might be a really good choice here....

## Features
1. Crossplatform chat
- Display yt, twitch, kick etc, in one terminal window.

2. Collect points.
- Normal coins, that can be collected via watchtime (channelpoints), following,
subscribing & gifting subs. (this might be a twitch exclusive)
- Premium coins, only from sub, gift, donation.
- This should be crossplatform, and not a twitch exclusive.

3. Store points
- Storage is going to be complicated. Local storage is risky but might be easier
for average users, cloud storage is easy, but expensive.

4. Dashboard
- Users need to use a website to redeem their points if this is infact cross platform.

5. Better giveaway system
- Collect followers, subs, gifter sub givers, donaters etc
- Collect "get chatters" to filter out only the people who are currently watching

6. Reward watch streak
- Collect current viewers, and give watch streaks.
- Based on days live, so if you don't stream, users will not lose streaks

7. Music request

8. Message board background transparent?
