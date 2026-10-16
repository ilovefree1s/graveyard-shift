# Grave Shift

A spooky 1-vs-3 voxel game for phones: one robber digs up graves and banks the loot before dawn, while three guards hunt him through a pitch-black graveyard with flashlights.

**Play:** https://ilovefree1s.github.io/graveyard-shift/

## Online with friends
1. Open the link on your phone and tap **Play online**, then **Find a game**.
2. You join any room with a free seat, or open a new one that the next player joins automatically.
3. Pick a seat (the robber or one of the three guards), or tap **Random robber** to spin everyone's names through the seats and let the wheel decide. Empty seats are played by bots.
4. The person who opened the room taps **Start the night**.

The room creator's phone runs the match, so it should stay on the game (not in the background) while you play.

Online play uses Supabase Realtime (broadcast and presence, no database tables). The project URL and publishable key are in `index.html` under `SUPA`.

## Offline
Play as the robber or a guard against bots without an internet connection to the game server.
