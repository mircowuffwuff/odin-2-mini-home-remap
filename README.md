# Odin 2 Mini Home Remap
Magisk module that remaps the physical home button to the `GUIDE` key code, which is otherwise completely unused on the handheld. `GUIDE` can then be caught by Key Mapper, Button Mapper, Tasker, etcetera.

<!--<p float="left">-->
<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="https://donate.yrkl.net">
    <img width="160" alt="thrilled" src="https://github.com/user-attachments/assets/9789b502-579c-435d-939a-1643f7540c04" />
  </a>
</p>

# Usage
1. Download the module [here](https://github.com/mircey/odin-2-mini-home-remap/releases/download/1.0/odin-2-mini-home-remap-1.0.zip)
2. Install it to Magisk via `Modules->Install from storage`, then selecting the zip
3. Reboot the device
4. Launch the android settings app and turn off `Odin settings->Prevent press the Home button accidentally`

That is it! Now, the home button no longer exits to the launcher, and next time you try and remap the home button to something else via any key mapper, it will work!

# Motivation
Personally, I wanted to be able to map the Odin 2 Mini's home button to open the ~~[HandheldExp](https://github.com/Teppichseite/HandheldExp)~~ in-game overlay, as per its [installation guide](https://github.com/Teppichseite/HandheldExp?tab=readme-ov-file#%EF%B8%8F-installation). Sadly, the Odin 2 Mini does not support this by default, as key mappers cannot intercept its home button press.
