(draft)

# Berserk

A universal ergonomic keyboard layout for programmable keyboards that offers a sensible default for anything from split and 40% and up. Get a running start or just take whatever works for you. 

Most programmable keyboards don't come with layout instructions, and though solving puzzles are fun, this can obstruct your real work. 


![image](https://pbs.twimg.com/media/GRINuIqbYAEL3nf?format=jpg&name=4096x4096)
👆 cisne 40% keyboard

berserk requirements:

- [ ] dual function keys and layers (offered by programmable firmware such as VIA/VIAL).

berserk features:

- [ ] no finger travel (max 1u / 1 key)
- [ ] good with any keyboard
- [ ] great with the mouse
- [ ] no dedicated mod keys
- [ ] good with mod combinations
- [ ] arrow keys on homerow
- [ ] homerow mods optional except for the A key
- [ ] room for big spacebars for sound
- [ ] ample free keys

berserk opinions:
- [ ] categories should be dedicated to one hand
- [ ] mice are great
- [ ] tiny keyboards are great

      
Berserk isn't so much original as it is inevitable for anyone with similar requirements.  I've also written a [custom keyboard guide](https://github.com/johans-work/custom-keyboard-guide). 

## 1: eliminate all mod, num, and fn keys

Mods are merged into the far left, and layers are triggered with the right thumb and left pinky.

base layer / layer0 = Alphas + mods + special keys.

![image](https://github.com/johans-work/berserk/assets/108384802/a668aacc-a49a-4440-bbb3-f735956d37f9)

- [ ] We adopt the hhkb ctrl position at caps lock, and swap caps lock with tab on tap, ctrl on hold.
- [ ] If you only have one space bar, swap it with space on tap, shift on hold.
- [ ] If you have two space bars, swap left space with enter on tap, shift on hold, and right spacebar with space on tap, layer1 on hold.
- [ ] With the shift key free, swap left shift with esc on tap, alt on hold.
- [ ] With the esc key free, swap esc with del on tap, win on hold.
- [ ] layer1 is added for numbers, layer2 for symbols, and layer3 for function keys.

For regular keyboards with only one spacebar, shift is added to the spacebar, with enter and backspace remaining at their standard positions. With a split spacebar, both enter and backspace can be assigned to the left hand side, which works great with the mouse.

## 2: multiply by 4

A 40% keyboard with 4 layers already gives you 160%, with no finger travel.

layer1 = The numpad + navigation layer. Arrow keys are at homerow.

![image](https://github.com/johans-work/berserk/assets/108384802/7c697354-d504-4b42-a7bf-f9dd31bbbaef)

The number symbols are left paired, with the remaining symbols grouped into 3 categories.

![image](https://github.com/johans-work/berserk/assets/108384802/86fe64f5-8e4a-407f-a566-f8c986bc50f6)

The fn layer simply follows the num positions. Ample room for more custom keys.

![image](https://github.com/johans-work/berserk/assets/108384802/1715f475-7f3c-4752-be03-2271276ff1e0)

## phase 3: the rest

- [ ] The number symbols remain paired at the same position on the symbol layer.
- [ ] - _ = + are added to T B G R on the left of layer 2. Equal is in the middle, with underscore below it, and minus above it, with plus next to minus at the 9 position.
- [ ] ; is replace with ' that has higher usage on layer0.
- [ ] ; and : are placed above , and . at K L on the right of layer 2.
- [ ] ` is place at ' and ~ above it at P on the right of layer 2.  
- [ ] () are added at H J, {} at Y U, and [] at I O on the right of layer 2. 
- [ ] | and \ are added to N and M on the left of layer 2. With Alice layouts, / is added to the spair key to the left of N.
- [ ] < > ? remain at their positions on layer 2.

## optional configurations

Next are the mod keys. They are merged into tap and hold dual function keys to the leftmost column and thumb row.


- [ ] To avoid accidentally hitting del, we move it to the top of the column at the original tab key position, and therefore esc goes to left shift.
      
To adapt the above to standard keyboards with just one spacebar at the thumb:

- [ ] The right hand shift, enter, and backspace remain at their positions.
- [ ] Space is replaced with space on tap and shift on hold.

# Determining Factors

- [ ] Whether you use your mouse a lot.
- [ ] Whether you rely on classic shortcut keys for copy and paste, photoshop, or vim, etc.
- [ ] Whether you even use function keys at all.
- [ ] Whether you prefer similar keys grouped on one hand or split across both.
- [ ] Whether you code.
- [ ] Your keyboard.



# Why Now?

New layouts such as Berserk have become possible thanks to the popularity of new firmware that enables easy customization of layers and key functions; namely QMK, and it's derivatives VIA and VIAL.






