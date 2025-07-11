# Shared-Piano-Playbot
🎵 Play MIDI files on Google Shared Piano 🎹

## Play Demo
Please click the gif below to watch full video :)
[![playbot_demo](https://user-images.githubusercontent.com/77003554/184627712-c3ebbe96-7f9f-4f0c-a312-c6143e20d4cc.gif)](https://drive.google.com/file/d/1zJCgLY74Kt_SCeB8_HkQp3melCtlrFpe/view?usp=sharing)

## Main Features
- Auto-play midi files
- Transpose (Pitch Shifting)
- Auto sustain & sustain controls

## How to Install
1. Install [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) chrome extension.
2. Create a new script in Tampermonkey, copy the Playbot script, and paste it in.
3. Follow these [instructions](https://www.tampermonkey.net/faq.php#Q209) to enable User Scripts. (Developer mode might be needed too)
4. Tampermonkey will automatically run Playbot script if you visit Shared Piano webpage.

## How to Use
1. Open Shared Piano webpage and press `ctrl + m`.
3. Select your midi file from the file explorer.
4. Hit `Enter` to start playing. (please wait for a second)

## Shortcuts
### Main control
- Open file explorer: `ctrl + m`
- Start playing: `Enter`

### Transpose
No need to press `shift` key.
- Pitch +1: `+` 
- Pitch -1: `-`

### Sustain
Sustain will automatically be turned on.
- Turn off: `←`
- Turn on with minimum interval: `→`
- Longer interval: `↑`
- Shorter interval: `↓`

## Reminder
- Too much amplitude will cause **audio clipping**.
  - Try *Night of Nights black midi* if you're curious.😉
- Too long sustain interval will trigger Tone.js limit & cause **load error** from Shared Piano.
  - In this case, some keys won't sound properly.
  - It will be fixed if you immediately turn off the sustain with `←` key for a bit.

## WIP
- ~~Direct midi file convert~~ ✅ **Support since v1.0!**
- Velocity

#### WIP but not soon
- Better sustain interval
- UI
- Pause & Replay
- Play speed control

## This is a fix of the [original project](https://github.com/Queue-ri/Shared-Piano-Playbot) by Queue-ri. I might continue to update it as the code breaks from newer versions of Chrome/Tampermonkey.
