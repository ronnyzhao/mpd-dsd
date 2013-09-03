mpd-dsd
=======

Version of stable MPD 0.17.5 for fasttracking DSD playback development.
Once development is complete the changes / enhancements will be submitted to
MPD.

Planned DSD playback enhancements and fixes:

Enhancements:
- DSD128 playback with DoP using one stereo channel @ 352.8 [done]
- DSD128 playback with DoP using two stereo channels @ 176.4

Fixes:
- MPD hangs at the end of a song when playing certain DFF files [done]
- Pops at the end of certain DSF files [done]

Planned enhancements:
- Re-introduce fast forward and rewind for both DSF and the DFF decoder [done for DSDIFF]
- Utilize DSD/DoP support provided by ALSA in kernel 3.6.11 and up [*1]

[*1] The current DoP implementation in kernel 3.6.11 seems to provide a incorrect/incompatible DoP
format not compatible with commond DACs known to support DoP.

