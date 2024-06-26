# Intro
Berserk is a univeral keyboard layout for programmable keyboards, and offers a sensible default for split and 40% keyboards. 

features:

- [ ] max 1u (1 key) finger travel
- [ ] compatible down to 40%, up to 100%
- [ ] optimized for mouse use
- [ ] eliminates dedicated mod keys
- [ ] homerow mods optional except for the A key
- [ ] room for at least 1 big spacebar for sound
- [ ] ample unused keys

requirements:

- [ ] dual function keys and layers offered by programmable firmware such as VIA/VIAL.

Most programmable keyboards don't come with layout instructions, and almost tout figuring it out yourself as a feature. But this is a lot of hard work that gets in the way of real work. Berserk isn't so much original as it is inevitable for anyone with similar requirements. Save time by starting with many of the answers first. I've also written a [custom keyboard guide](https://github.com/johans-work/custom-keyboard-guide). 

# Answers First

## phase 1: elimination

- [ ] We adopt the hhkb ctrl position at caps lock, and swap it with tab on tap, ctrl on hold.
- [ ] If you only have one space bar, swap it with space on tap, shift on hold.
- [ ] If you have two space bars, swap left space with enter on tap, shift on hold, and right spacebar with space on tap, layer1 on hold.
- [ ] With the shift key free, we swap it with esc on tap, alt on hold.
- [ ] With the esc key free, we swap it with del on tap, win on hold.
- [ ] We add layer1 for numbers.

With that, we have eliminated all mod keys on the bottom row, and the num row.

## phase 2: multiplication

Layers multiply key count. So even with a 40% keyboard, 3 layers already gives you 120%, with minimum finger travel.

- [ ] ; is replace with ' that has higher usage.
- [ ] We adopt a numpad layout on the left side of layer1 to allow all numbers to be accessible by the left hand.
- [ ] Navigation arrows are used when not using the mouse, so are added to the right side of layer1.
- [ ] We adopt standard VIM motions and add navigation arrows at H J K L.

## phase 3: symbols


- [ ] Layer2 is added for symbols.
- [ ] The symbols paired with number keys remain paired occupying the same position as their numbers.
- [ ] - _ = + are added to T B G R on the left of layer 2. Equal is in the middle, with underscore below it, and minus above it, with plus next to minus at the 9 position.
- [ ] ; and : are placed above , and . at K L on the left of layer 2.
- [ ] ` is place at ' and ~ above it at P on the left of layer 2.  
- [ ] () are added at H J, {} at Y U, and [] at I O on the left of layer 2. 
- [ ] | and \ are added to N and M on the left of layer 2. With Alice layouts, / is added to the spair key to the left of N.
- [ ] < > ? remain at their positions on layer 2.
- [ ] Layer 3 is added for Fn keys, with the same numpad layout.

With the above, all input keys have been laid out with room to spair.

Next are the mod keys. They are merged into tap and hold dual function keys to the leftmost column and thumb row.

- [ ] We are assuming at least two left thumb keys, and one right thumb key.
- [ ] The main right thumb key is replaced with space on tap, and layer 1 (numbers) on hold.
- [ ] The main left thumb key is replaced with enter on tap, and shift on hold.
- [ ] With shift at the thumb, caps lock and shift keys become redundant.
- [ ] Caps lock is replaced with ctrl on hold after the popular HHKB layout, and tab on tap, for tab to be in the middle of the column.
- [ ] Between left shift and the original tab key, we can distribute alt, win, del, and esc.
- [ ] To avoid accidentally hitting del, we move it to the top of the column at the original tab key position, and therefore esc goes to left shift.
- [ ] The original tab on hold, and alt to left shift.
- [ ] 
- [ ] 
- [ ] The second left thumb key is replaced with backspace on tap, and Layer 1 on hold.
- [ ] The main right thumb key is replaced with space on tap and layer 1 on hold.

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






