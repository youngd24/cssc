# Original Source Images

As I've come across software images, either from the Internet or from other people, they'll land here.

What I have so far:

```
IMAGE NAME        | BRIEF IMAGE DESCRIPTION
--------------------------------------------------------------------------
cnet12bbsdoc.d64  | D64 image (cnet12.D64) from the BBS documentary site
cnet12crk.d64     | Sourced from someone in the C-Net FB group
cnet12ucr.d64     | Sourced from someone in the C-Net FB group
```


## cnet12bbsdoc.d64

This was one of the first images I tried and had work. It appears to be an archive copy of a BBS named "The Lyon's Den" operated by a user named Maelstrom. It has been HIGHLY configured and modded and is notably missing p.EN so it's nearly impossible to manage users using it as is. However when it's reconfigured it does run and answer on a real C64 using a real 1670 modem.

* Maelstrom user: https://csdb.dk/scener/?id=6238
* Lyon's Den BBS: https://csdb.dk/bbs/?id=1559

### File Listing
```
OPENCBM:  sucessfully loaded opencbm.dll
D64 disk image recognised: cnet12bbsdoc.d64, 35 tracks.
Unit 8 drive 0: D64 disk image attached: cnet12bbsdoc.d64.
0 "c-net 12.0      "    2a
1    "bt"               prg 
25   "intro"            prg 
4    "ram.boot"         prg 
49   "ml"               prg 
1    "p-main"           seq 
3    "p.alpha"          prg 
1    "p.tele-logon"     prg 
2    "p.lotto"          prg 
26   "p.nu"             prg 
20   "p.cf"             prg 
30   "p.lo"             prg 
4    "p.AM"             prg 
11   "p.VF"             prg 
4    "menu 1"           seq 
4    "menu 2"           seq 
5    "menu 4"           seq 
4    "menu 5"           seq 
3    "menu 6"           seq 
3    "menu 7"           seq 
4    "menu 8"           seq 
1    "menu 9"           seq 
10   "proto 0"          prg 
5    "proto 1"          prg 
1    "proto 2"          prg 
12   "proto 3"          prg 
36   "p.em"             prg 
14   "p.f"              prg 
46   "p.s"              prg 
9    "p.access"         prg 
7    "p.diredit"        prg 
11   "p.n"              prg 
28   "ramdos040887.bin" prg 
40   "p.u/d"            prg 
5    "p.BA"             prg 
12   "p.BB"             prg 
2    "p.BC"             prg 
2    "p.CD"             prg 
3    "p.CW"             prg 
5    "p.E"              prg 
6    "p.ED"             prg 
6    "p.EX"             prg 
4    "p.LD"             prg 
2    "p.NL"             prg 
2    "p.PC"             prg 
2    "p.PW"             prg 
6    "p.ST"             prg 
10   "p.UL"             prg 
3    "p.SG"             prg 
4    "p.WF"             prg 
1    "dir.sub 1"        seq 
1    "bd.data"          seq 
9    "u.config"         rel 
2    "u.alpha"          rel 
1    "etc.suggest"      seq 
3    "etc.stats"        rel 
5    "etc.data"         rel 
1    "etc.msg"          seq 
4    "etc.new"          seq 
2    "sys.Sub"          seq 
1    "sys.U/D"          seq 
1    "sys.start"        seq 
1    "sys.login"        seq 
1    "sys.chat"         seq 
1    "cn.NEWS"          seq 
1    "n-main"           seq 
1    "sys.bbs"          seq 
1    " 8Games"          seq 
1    "dir.sub 8"        seq 
48   "cn"               prg 
4    "p.macros"         prg 
14   "p.su"             prg 
9    "etc.errlog"       seq 
3    "etc.recs"         seq 
1    " 1beta test"      seq 
53 blocks free.
Unit 8 drive 0: D64 disk image detached: cnet12bbsdoc.d64.
```

## cnet12crk.d64

Given to me by a person in the Facebook C-Net group, supposedly a full copy of the original C-Net 12 files but a cracked version. It starts up and says it is "Cracked by Peter Ace", that's the same as a partial copy of an image on the Internet Archive. This one starts up on Vice but has been configured already and when reconfigured won't finish starting up when using a 1670 modem, it bounces from BACK to ATH, the BAR screen never fully opens and you can't login.

### File Listing
```
OPENCBM:  sucessfully loaded opencbm.dll
D64 disk image recognised: cnet12crk.d64, 35 tracks.
Unit 8 drive 0: D64 disk image attached: cnet12crk.d64.
0 "c-net master    " 08 2a
1    "bt"               prg 
49   "cn"               prg 
25   "intro"            prg 
49   "ml"               prg 
10   "copy-all"         prg 
1    "dv change"        prg 
10   "p.su"             prg 
20   "p.cf"             prg 
6    "p.stack"          prg 
9    "p.access"         prg 
7    "p.diredit"        prg 
13   "p.em"             prg 
12   "p.f"              prg 
26   "p.lo"             prg 
11   "p.n"              prg 
26   "p.nu"             prg 
46   "p.s"              prg 
14   "p.t"              prg 
40   "p.u/d"            prg 
4    "p.weed"           prg 
5    "p.BA"             prg 
12   "p.BB"             prg 
2    "p.BC"             prg 
2    "p.CD"             prg 
7    "p.CP"             prg 
3    "p.CW"             prg 
5    "p.E"              prg 
6    "p.ED"             prg 
9    "p.EN"             prg 
3    "p.EX"             prg 
4    "p.LD"             prg 
2    "p.NL"             prg 
2    "p.PC"             prg 
2    "p.PW"             prg 
6    "p.ST"             prg 
10   "p.UL"             prg 
9    "p.VF"             prg 
3    "p.WF"             prg 
10   "proto 0"          prg 
5    "proto 1"          prg 
1    "proto 2"          prg 
12   "proto 3"          prg 
3    "menu 1"           seq 
4    "menu 2"           seq 
3    "menu 3"           seq 
5    "menu 4"           seq 
4    "menu 5"           seq 
3    "menu 6"           seq 
3    "menu 7"           seq 
4    "menu 8"           seq 
1    "menu 9"           seq 
1    "sys.login"        seq 
1    "sys.phonebook"    seq 
1    "sys.config"       seq 
1    "sys.new user"     seq 
1    "sys.start"        seq 
1    "sys.welcome"      seq 
1    "sys.end"          seq 
2    "sys.cred"         seq 
14   "sys.inst"         seq 
1    "etc.errlog"       seq 
1    "bd.data"          seq 
110 blocks free.
Unit 8 drive 0: D64 disk image detached: cnet12crk.d64.
```

## cnet12ucr.d64

Another one given to me by a person in the Facebook C-Net group, supposedly a full copy of the original C-Net 12 files and NOT the cracked one but a real deal install. This one would need the license dongle to operate if it truly is the original verison. I started it up, it loads but hits a CPU halt in Vice which I am assuming is where it's checking for the dongle in port 2.

### File Listing
```
OPENCBM:  sucessfully loaded opencbm.dll
D64 disk image recognised: cnet12ucr.d64, 35 tracks.
Unit 8 drive 0: D64 disk image attached: cnet12ucr.d64.
0 "c-net 64        " 12 2a
1    "bt"               prg 
48   "cn"               prg 
49   "ml"               prg 
25   "intro"            prg 
10   "copy-all"         prg 
1    "dv change"        prg 
1    ""...etc/prg disk" usr 
10   "p.su"             prg 
20   "p.cf"             prg 
6    "p.stack"          prg 
9    "p.access"         prg 
7    "p.diredit"        prg 
13   "p.em"             prg 
12   "p.f"              prg 
26   "p.lo"             prg 
11   "p.n"              prg 
26   "p.nu"             prg 
46   "p.s"              prg 
14   "p.t"              prg 
40   "p.u/d"            prg 
4    "p.weed"           prg 
5    "p.BA"             prg 
12   "p.BB"             prg 
2    "p.BC"             prg 
2    "p.CD"             prg 
7    "p.CP"             prg 
3    "p.CW"             prg 
5    "p.E"              prg 
6    "p.ED"             prg 
9    "p.EN"             prg 
3    "p.EX"             prg 
4    "p.LD"             prg 
2    "p.NL"             prg 
2    "p.PC"             prg 
2    "p.PW"             prg 
6    "p.ST"             prg 
10   "p.UL"             prg 
9    "p.VF"             prg 
3    "p.WF"             prg 
1    ""...system disk"  usr 
10   "proto 0"          prg 
5    "proto 1"          prg 
1    "proto 2"          prg 
12   "proto 3"          prg 
3    "menu 1"           seq 
4    "menu 2"           seq 
3    "menu 3"           seq 
5    "menu 4"           seq 
4    "menu 5"           seq 
3    "menu 6"           seq 
3    "menu 7"           seq 
4    "menu 8"           seq 
1    "menu 9"           seq 
1    "sys.login"        seq 
1    "sys.phonebook"    seq 
1    "sys.config"       seq 
1    "sys.new user"     seq 
1    "sys.start"        seq 
1    "sys.welcome"      seq 
1    "sys.end"          seq 
2    "sys.cred"         seq 
14   "sys.inst"         seq 
80   "sys.say"          rel 
31 blocks free.
Unit 8 drive 0: D64 disk image detached: cnet12ucr.d64.
```
