= Phoque1 Board definitions

Usage in Platformio:

- Clone this repository into a folder within your PlatforIO project (for example `custom_arduino_variant`)
    - `mkdir custom_arduino_variant; cd custom_arduino_variant && git clone https://github.com/Moddingear/Phoque1-boarddef PHOQUE1`
- Move PHOQUE1.json to a folder named `boards` 
    - `mkdir ../boards; cp PHOQUE1.json ../boards`
- Add `board_build.variants_dir = custom_arduino_variant` to platformio.ini
- That's it
