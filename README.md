## YATKA
yet another tetris klone in action

### about
- gfx and code (mostly) by me (vamastah a.k.a. szymor)
- frame limiting, counting and upscaling code by Artur 'zear' Rojek
- in-game music by Vomitron

Feel free to report errors.

### how to build (Ubuntu)
    apt update
    apt install libsdl-image1.2-dev libsdl-mixer1.2-dev libsdl-ttf2.0-dev libsdl1.2-dev
    git clone https://github.com/szymor/yatka.git
    cd yatka
    make

### command line parameters
- --nosound - disable music and sound effects
- --sound - enable music and sound effects if disabled
- --fullscreen - full screen mode
- --scale1x - 320x240 mode
- --scale2x - 640x480 mode
- --scale3x - 960x720 mode
- --scale4x - 1280x960 mode
- --startlevel <num> - the higher level, the higher speed

For more, please refer to the source code.

### ideas / plans
- animated mascot (becchi?) evolving while playing or saying random things during gameplay
- better score system (combos, T-spins)
- advanced wall kick
- rumble support for Bittboy
- line clear animation (TGM?)
- ports for other platforms
- introducing max speed level
- key configuration
- fixed easy spin
- more randomizers
- tetromino color defined per skin
- precolored (no dyeing) brick support
