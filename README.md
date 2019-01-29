Layouts for the modified german programmers keyboard.
The number keys are mapped to the respective symbols in the default state, using shift they return numbers again.
Shift key acts as Control, CapsLock acts as Shift and Control acts as CapsLock
Full computer restart is needed to apply the changes

Following things are remapped in evdev (from /usr/share/X11/xkb/keycodes/):
´´´<LCTL> = 37;  -->   <LCTL> = 50;
<LFSH> = 50;  -->   <LFSH> = 66;
<CAPS> = 60;  -->   <CAPS> = 37;´´´

Following things are remapped in de (from /usr/share/X11/xkb/symbols/):
starting at line 10

´´´
    key <AE01>	{ [         exclam,     1,   rightsinglequotemark,   onesuperior ]};
    key <AE02>	{ [         quotedbl,   2,   twosuperior,            oneeighth ]};
    key <AE03>	{ [         section,    3,   threesuperior,          sterling ]};
    key <AE04>	{ [         dollar,     4,   onequarter,             currency ]};
    key <AE05>  { [         percent,    5,   exclamdown,             onehalf ]};
    key <AE06>  { [         ampersand,  6,   questiondown,           threequarters  ]};
    key <AE07>  { [         slash,      7,   braceleft,              oneeighth]};
    key <AE08>  { [         parenleft,  8,          bracketleft,            threeeighths]};
    key <AE09>  { [         parenright, 9,          bracketright,           fiveeighths]};
    key <AE10>  { [         equal,      0,          braceright,             seveneighths]};
    key <AE11>  {type[Group1]="FOUR_LEVEL_PLUS_LOCK",  symbols[Group1]=
                  [question, ssharp, backslash, questiondown, 0x1001E9E ]};
    key <AE12>	{ [dead_acute, dead_grave, dead_cedilla,  dead_ogonek ]	};
´´´
