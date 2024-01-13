# hexdump
A very lightweight python hexdump utility.

As I was writing my custom [6502 Emulator](https://github.com/thbop/6502) I decided to create a simple hexdump python script like the one in [Ben Eater's Video Here](https://youtu.be/0q6Ujn_zNH8?si=qB87dFz5KKBUPB_O&t=781).

To run, simply:

`python hexdump.py -f <filename.exe>`

It doesn't have any features besides that. Here's an example of an output:

```
00000000  d8 58 a0 7f 8c 12 d0 a9  a7 8d 11 d0 8d 13 d0 c9  |.X..............|
00000010  df f0 13 c9 9b f0 03 c8  10 0f a9 dc 20 ef 80 a9  |................|
00000020  8d 20 ef 80 a0 01 88 30  f6 ad 11 d0 10 fb ad 10  |.......0........|
00000030  d0 99 00 02 20 ef 80 c9  8d d0 d4 a0 ff a9 00 aa  |................|
00000040  0a 85 2b c8 b9 00 02 c9  8d f0 d4 c9 ae 90 f4 f0  |..+.............|
00000050  f0 c9 ba f0 eb c9 d2 f0  3b 86 28 86 29 84 2a b9  |........;.(.).*.|
00000060  00 02 49 b0 c9 0a 90 06  69 88 c9 fa 90 11 0a 0a  |..I.....i.......|
00000070  0a 0a a2 04 0a 26 28 26  29 ca d0 f8 c8 d0 e0 c4  |.....&(&).......|
00000080  2a f0 97 24 2b 50 10 a5  28 81 26 e6 26 d0 b5 e6  |*..$+P..(.&.&...|
00000090  27 4c 44 80 6c 24 00 30  2b a2 02 b5 27 95 25 95  |'LD.l$.0+...'.%.|
000000A0  23 ca d0 f7 d0 14 a9 8d  20 ef 80 a5 25 20 dc 80  |#...........%...|
000000B0  a5 24 20 dc 80 a9 ba 20  ef 80 a9 a0 20 ef 80 a1  |.$..............|
000000C0  24 20 dc 80 86 2b a5 24  c5 28 a5 25 e5 29 b0 c1  |$....+.$.(.%.)..|
000000D0  e6 24 d0 02 e6 25 a5 24  29 07 10 c8 48 4a 4a 4a  |.$...%.$)...HJJJ|
000000E0  4a 20 e5 80 68 29 0f 09  b0 c9 ba 90 02 69 06 2c  |J...h).......i.,|
000000F0  12 d0 30 fb 8d 12 d0 60  00 00 00 0f 00 80 00 00  |..0....`........|
```
