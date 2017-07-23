# archlinux-mirror-tools: tools for working with archlinux package repositories

DISCLAIMER:

Acquiring archlinux packages via rsync is generally discouraged.
It should be noted that there are very few cases where syncing *all* packages of a mirror is truly needed;
undue use puts undue burden on the mirrors.
For this reason, "defaults" will never be shipped for these scripts.

Ideally, you would only use the rsync scripts if you intend to run a mirror yourself;
and it's always a Good Idea™ if possible to see if the mirror you use an an upstream is cool with the usage.
I'm not going to be held responsible if a mirror bans your IP address range because of usage of these scripts.
(Shouldn't need saying, but re responsibility: please read the disclaimer in the license file.)
