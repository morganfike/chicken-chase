# The Chicken Chase: Cade's 28th

A 3D animated pitch for hosting a Chicken Chase on the Lower East Side for Cade's birthday. It plays like a short film (about 2½ minutes): Cade puts on a chicken head at 3:00 PM and hides inside a bar from a secret list, the teams get released at 3:30 with the list, and the afternoon ends with fireworks at sunset around 6:00 PM.

## How to watch it

- **Easiest:** double-click `index.html`. It opens in your browser. (It needs an internet connection to load the 3D library and fonts.)
- **Local preview server:** in Terminal, run:

  ```
  cd ~/Desktop/Projects/chicken-chase
  python3 -m http.server 8028
  ```

  Then open http://localhost:8028 in your browser. Press `Ctrl+C` in Terminal to stop it.

## Changing the bars, teams, or times

Open `index.html` in any text editor. The settings are at the very top, in the block marked `EASY-TO-EDIT SETTINGS`:

- `meetingSpot`: where everyone meets at 3:00 PM
- `barList`: the bar list we pick ahead of time (up to 9). Cade hides at one of these.
- `teams`: team names and shirt colors
- `backupTime`: if nobody has found Cade by then, everyone gets the location

Every run picks a random hiding bar and plays out differently.

## Controls

Play/pause (or press Space), a speed slider (0.5x to 4x), Restart, mute, and camera buttons: Auto, Follow Cade, Follow a team (click again to switch teams), and Bird's-eye. You can also drag to orbit and scroll or pinch to zoom.
