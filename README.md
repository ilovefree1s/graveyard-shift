# Grave Shift

A spooky 1-vs-3 voxel game for phones: one robber digs up graves and banks the loot before dawn, while three guards hunt him through a pitch-black graveyard with flashlights.

**Play:** https://ilovefree1s.github.io/graveyard-shift/

## Online with friends
1. Open the link on your phone and tap **Play online with friends**.
2. One person taps **Create a room** and reads out the 4-letter code.
3. Everyone else types the code and taps **Join room**, then picks a seat (the robber or one of the three guards). Empty seats are played by bots.
4. The person who created the room taps **Start the night**.

The room creator's phone runs the match, so it should stay on the game (not in the background) while you play.

Online play uses Supabase Realtime (broadcast and presence, no database tables). The project URL and publishable key are in `index.html` under `SUPA`.

## Offline
Play as the robber or a guard against bots without an internet connection to the game server.
