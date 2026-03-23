# C-Net SysOp Support Center (CSSC)

## What is this?

This started, as so many retro projects do, as something "simple": I was after a C64 based BBS target that my war dialing demo could use. I remembered accessing C-Net based BBS's back in the early 90's so there was some nostalgia present but it also seemed to be quite popular around that era. I figured let's install one, how hard can it be? Yea, I know how that statement typically ends. As I've gotten more into this I found there used to be a resource of the same name, the C-Net SysOp Support Center, run by a group of SysOps back when so I reused that name.

I'm starting to document what I'm finding on how to get a version 12 BBS of C-Net up and running and in my case that has a heavy focus on using real hardware. The reference standard I'm after is a regular Commodore 64 using a userport 1670 modem at 1200 baud. I have a small phone network so I can run real analog voice and dial in locally, I'd use SIP for this but the 1670 doesn't do well there as it has little to no error correction.

For now this is really just a brain dump of what I find with the eventual goal of producing a clean version 12 d64 image that can be used to start up a working, clean-slate, BBS on real hardware or under Vice.

## Starting Out

One of the first things I discovered was that most of the disk images floating around the Internet are copies, dumps or archives of existing BBS's and, as a result, have been previously configured. The first problem there is being able to log in to it as as Sysop account and do really anything. Best as I can tell these accounts and passwords are stored in the file `u.config`, something is also stored in `u.alpha` though I'm not entirely sure what. The fastest way to get things back to a reconfigured state is to delete the following files from the d64 image:

```
* bd.data
* u.config
* u.alpha
```

the file `bd.data` is the main configuration file for C-Net, when you configure the system those bits are stored in there, here's an example (after converting to ASCII):

```
8
0
8
0
8
0
8
0
8
0
8
0
UL
3
 10
C-Net 12.0 (c)1987 Perspective
169,2,141,2,76,2
```

What I think those things are used for:

* 8's and 0's: the device ID's used for the various diskettes that the system operates using, during installation/configuration you're asked for these.
* UL: the prefix used by user ID's on the system, in this case that's what I picked.
* 3: I think this is the identifier for the modem type in use, in my case I selected option 3 from the configuration menu which is the 1670 modem.
* 10: No idea what this is
* I would have to assume this is just a copyright message string?
* The last line I have no idea.

To further clean things out and set up for a basic system the following files can also be removed, if they're present:

```
* etc.stats
* etc.errlog
* etc.log
```