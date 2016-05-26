demoLive555withFFMPEG
=====================
Forked from https://github.com/yuvalk/demoLive555withFFMPEG to update for VS 2015, Live555 20160520, FFMPEG 20160526, SDL 1.2.15.

You need to download:
- Live555 source and build (see http://tujv.bitbucket.org/2016/02/building-live555/)
- ffmpeg-20160526-git-89e9393-win32-dev
- SDL-devel-1.2.15-VC.zip (Visual C++)

Current project setup expects the local path to look like:
<parent_folder>
|-ffmpeg-20160526-git-89e9393-win32-dev
|-live
|-SDL-1.2.15
|-demoLive555withFFMPEG

For quick debug, also download the shared build of FFMPEG and put the DLLs in the debug build folder.
