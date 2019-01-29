Layouts for the modified german programmers keyboard.
The number keys are mapped to the respective symbols in the default state, using shift they return numbers again.
Shift key acts as Control, CapsLock acts as Shift and Control acts as CapsLock

Following things are remapped in evdev (from /usr/share/X11/xkb/keycodes/):
´´´<LCTL> = 37;  -->   <LCTL> = 50;
<LFSH> = 50;  -->   <LFSH> = 66;
<CAPS> = 60;  -->   <CAPS> = 37;´´´

Following things are remapped in de (from /usr/share/X11/xkb/symbols/):
starting at line 10

´´´key <AE01> { [               exclam,          1, rightsinglequotemark,   NoSymbol,     onesuperior,        exclamdown,           U02B9,        NoSymbol ] };
key <AE02>	{ [         quotedbl,   2,  twosuperior,    oneeighth ]	};
key <AE03>	{ [         section,    3, threesuperior,    sterling ]	};
key <AE04>	{ [         dollar,     4,   onequarter,     currency ]	};
key <AE05> { [               percent,         5,      exclamdown,        NoSymbol,         onehalf,           uparrow,           U02C1,        NoSymbol ] };
key <AE06> { [               ampersand,       6,    questiondown,        NoSymbol,   threequarters,         downarrow,           U02C0,        NoSymbol ] };
key <AE07> { [               slash,           7,       braceleft,        NoSymbol,       oneeighth,         leftarrow,       braceleft,        NoSymbol ] };
key <AE08> { [               parenleft,       8,     bracketleft,        NoSymbol,    threeeighths,        rightarrow,      braceright,        NoSymbol ] };
key <AE09> { [               parenright,      9,    bracketright,        NoSymbol,     fiveeighths,         plusminus,     bracketleft,        NoSymbol ] };
key <AE10> { [               equal,           0,      braceright,        NoSymbol,    seveneighths,         trademark,    bracketright,        NoSymbol ] };
key <AE11> {type[Group1]="FOUR_LEVEL_PLUS_LOCK",  symbols[Group1]=
              [question, ssharp, backslash, questiondown, 0x1001E9E ]};
key <AE12>	{ [dead_acute, dead_grave, dead_cedilla,  dead_ogonek ]	};´´´
