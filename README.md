# hexdump
A very lightweight python hexdump utility.

As I was writing my custom [6502 Emulator](https://github.com/thbop/6502) I decided to create a simple hexdump python script like the one in [Ben Eater's Video Here](https://youtu.be/0q6Ujn_zNH8?si=qB87dFz5KKBUPB_O&t=781).

To run, simply:

`python hexdump.py -f <filename.exe>`

It doesn't have any features besides that. Here's an example of an output:

```
00000000  D8 58 A0 7F 8C 12 D0 A9  A7 8D 11 D0 8D 13 D0 C9  |.X..............|
00000010  DF F0 13 C9 9B F0 03 C8  10 0F A9 DC 20 EF 80 A9  |................|
00000020  8D 20 EF 80 A0 01 88 30  F6 AD 11 D0 10 FB AD 10  |.......0........|
00000030  D0 99 00 02 20 EF 80 C9  8D D0 D4 A0 FF A9 00 AA  |................|
00000040  0A 85 2B C8 B9 00 02 C9  8D F0 D4 C9 AE 90 F4 F0  |..+.............|
00000050  F0 C9 BA F0 EB C9 D2 F0  3B 86 28 86 29 84 2A B9  |........;.(.).*.|
00000060  00 02 49 B0 C9 0A 90 06  69 88 C9 FA 90 11 0A 0A  |..I.....i.......|
00000070  0A 0A A2 04 0A 26 28 26  29 CA D0 F8 C8 D0 E0 C4  |.....&(&).......|
00000080  2A F0 97 24 2B 50 10 A5  28 81 26 E6 26 D0 B5 E6  |*..$+P..(.&.&...|
00000090  27 4C 44 80 6C 24 00 30  2B A2 02 B5 27 95 25 95  |'LD.l$.0+...'.%.|
000000A0  23 CA D0 F7 D0 14 A9 8D  20 EF 80 A5 25 20 DC 80  |#...........%...|
000000B0  A5 24 20 DC 80 A9 BA 20  EF 80 A9 A0 20 EF 80 A1  |.$..............|
000000C0  24 20 DC 80 86 2B A5 24  C5 28 A5 25 E5 29 B0 C1  |$....+.$.(.%.)..|
000000D0  E6 24 D0 02 E6 25 A5 24  29 07 10 C8 48 4A 4A 4A  |.$...%.$)...HJJJ|
000000E0  4A 20 E5 80 68 29 0F 09  B0 C9 BA 90 02 69 06 2C  |J...h).......i.,|
000000F0  12 D0 30 FB 8D 12 D0 60  00 00 00 0F 00 80 00 00  |..0....`........|
```
