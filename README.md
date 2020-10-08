# Sample Streams

This is a collection of sample streams in various HTTP streaming formats that are free to use.

## Contributions

If you want to contribute to this list, first ensure that the provided stream are free to use and online and then submit the stream as a PR.

- No NSFW content, since most people using this list will be doing so professionally.
- Vendors are welcome to post streams to the list.

## HLS

HTTP (no gzip):
- 480x270, 640x360, 1024x576 (AVC) http://maitv-vod.lab.eyevinn.technology/VINN.mp4/master.m3u8

HTTPS (no gzip):
- 480x270, 640x360, 1024x576 (AVC) https://maitv-vod.lab.eyevinn.technology/VINN.mp4/master.m3u8

HTTPS (gzip):
- 384x216, 512x288, 640x360, 768x432, 1024x576, 1280x720, 1920x1080 (AVC) https://redbee.ctl.cdn.ebsd.ericsson.net/eyevinn/stswe/assets/e720d1da-0915-411b-807c-3e83f451bbb7_29C72F/materials/x8Tsg4z2a9_29C72F/vod-idx.ism/.m3u8

HTTPS Live CPIX Keyrotation:
- https://live.unified-streaming.com/keyrotation/keyrotation.isml/.m3u8

HTTPS VOD Static Multi-DRM CBCS (CPIX):
- https://demo.unified-streaming.com/video/multi-format-drm/master.m3u8

HTTPS VOD JITP Multi-Key CENC (CPIX):
- https://demo.unified-streaming.com/video/tears-of-steel/tears-of-steel-multikey-cenc.ism/.m3u8

## MPEG-DASH
HTTPS Live DVB-DASH-Low-Latency:
- https://live.unified-streaming.com/scte35/scte35.isml/.mpd?mpd_profile=urn:dvb:dash:profile:dvb-dash:2014

HTTPS VOD JITP $Timeline:
- https://demo.unified-streaming.com/video/tears-of-steel/tears-of-steel-tiled-thumbnails-timeline.ism/.mpd

HTTPS VOD JITP $Number:
- https://demo.unified-streaming.com/video/tears-of-steel/tears-of-steel-tiled-thumbnails-numbered.ism/.mpd

HTTPS VOD Static Trickplay Tiled-Thumbnails:
- https://demo.unified-streaming.com/video/tears-of-steel/tears-of-steel-tiled-thumbnails-static.mpd

HTTPS VOD Static Multi-DRM CBCS (CPIX):
- https://demo.unified-streaming.com/video/multi-format-drm/dash-cbcs.mpd

HTTPS VOD JITP Multi-Key CENC (CPIX):
- https://demo.unified-streaming.com/video/tears-of-steel/tears-of-steel-multikey-cenc.ism/.mpd

## Smooth Streaming
HTTPS VOD Mult-Bitrate/Multi-Language:
- https://demo.unified-streaming.com/video/tears-of-steel/tears-of-steel-multiple-subtitles.ism/Manifest

HTTPS VOD JITP Dynamic Track Filtering:
- `https://demo.unified-streaming.com/video/tears-of-steel/tears-of-steel.ism/Manifest?filter=(type==%22audio%22%26%26systemBitrate%3C100000)||(type==%22video%22%26%26systemBitrate%3C1024000)`

# License (MIT)

Copyright 2020 Eyevinn Technology

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# About Eyevinn Technology

Eyevinn Technology is an independent consultant firm specialized in video and streaming. Independent in a way that we are not commercially tied to any platform or technology vendor.

At Eyevinn, every software developer consultant has a dedicated budget reserved for open source development and contribution to the open source community. This give us room for innovation, team building and personal competence development. And also gives us as a company a way to contribute back to the open source community.

Want to know more about Eyevinn and how it is to work here. Contact us at work@eyevinn.se!
