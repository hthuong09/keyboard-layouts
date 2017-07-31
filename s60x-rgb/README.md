## My custom firmware layout for S60-X RGB PCB

### Layer 0 - Normal layer
![Layer 0](/assets/layer0.png)
- Default ASCII QWERTY layout with some replacement
- `Left Control` was replaced with `Momentary Layer Change` key a.k.a `FN1`, when hold down it will switch to Layer 1 (FN layer)
- `F` was replaced with `Layer-tap` key a.k.a `FN2`, when hold down it will switch to layer 2 (Vim Mode layer), when tap (press then release) it will act as `F`
- `RGUI` (Right Windows/Super key) was replaced with `Momentary Layer Change` key a.k.a `FN3`, when hold down it will switch to Layer 3 (LED Control Layer)
- `CapsLock` was replaced with `Mod-tap` key, when hold down it will act as `Control`, when tap (press then release) it will act as `Esc`
- `Backslash` and `Backspace` are swapped
- `LGUI` and `Left Alt` swapped

### Layer 1 - FN Layer
![Layer 1](/assets/layer1.png)
- Held `FN1` + `Tab` = `CapsLock`
- Held `FN1` + `1 to =` = `F1 to F12`
- Held `F1` + `q` = `Media Prev`
- Held `F1` + `w` = `Media Next`
- Held `F1` + `e` = `Media Toggle Play/Pause`
- Held `F1` + `r` = `Media Stop`
- Held `F1` + `a` = `Volume Down`
- Held `F1` + `s` = `Volume Up`
- Held `F1` + `d` = `Volume Mute`
- Held `F1` + `p` = `Screen Print`

### Layer 2 - Vi Mode layer
![Layer 2](/assets/layer2.png)
- Held `FN2` + `h` = `Left`
- Held `FN2` + `j` = `Down`
- Held `FN2` + `k` = `Up`
- Held `FN2` + `l` = `Right`
- Held `FN2` + `y` = `Home`
- Held `FN2` + `u` = `Page Down`
- Held `FN2` + `i` = `Page Up`
- Held `FN2` + `o` = `End`

### Layer 3 - LED Control (Underglow) layer
![Layer 3](/assets/layer3.png)
- Held `FN3` + `t` = `Toggle Underglow Led`
- Held `FN3` + `m` = `Change Underglow Led Mode`
- Held `FN3` + `1` = `Increase Hue`
- Held `FN3` + `2` = `Decrease Hue`
- Held `FN3` + `3` = `Increase Saturation`
- Held `FN3` + `4` = `Decrease Saturation`
- Held `FN3` + `5` = `Increase Value`
- Held `FN3` + `6` = `Decrease Value`

## TODO
- [x] Update image and introduce each layer job
- [ ] Document how to use json file
