# C-Net SysOp Support Center (CSSC)

## What is this?

This started, as so many retro projects do, as something "simple": I was after a C64 based BBS target that my war dialing demo could use. I remembered accessing C-Net based BBS's back in the early 90's so there was some nostalgia present but it also seemed to be quite popular around that era. I figured let's install one, how hard can it be? Yea, I know how that statement typically ends. As I've gotten more into this I found there used to be a resource of the same name, the C-Net SysOp Support Center, run by a group of SysOps back when so I reused that name.

I'm starting to document what I'm finding on how to get a version 12 BBS of C-Net up and running and in my case that has a heavy focus on using real hardware. The reference standard I'm after is a regular Commodore 64 using a userport 1670 modem at 1200 baud. I have a small phone network so I can run real analog voice and dial in locally, I'd use SIP for this but the 1670 doesn't do well there as it has little to no error correction.

## Starting Out

One of the first things I discovered was that most of the disk images floating around the Internet are copies, dumps or archives of existing BBS's and, as a result, have been previously configured. The first problem there is being able to log in to it as as Sysop account and do really anything. Best as I can tell these accounts and passwords are stored in the file `u.config`, something is also stored in `u.alpha` though I'm not entirely sure what. The fastest way to get things back to a reconfigured state is to delete the following files from the d64 image:

```
* bd.data
* u.config
* u.alpha
```