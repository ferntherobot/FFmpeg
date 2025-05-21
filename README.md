## Modifications to FFmpeg

This repository is based on FFmpeg (https://ffmpeg.org), with custom changes to allow for Range and Rate-Control RTSP headers based on discussions from the ffmpeg-devel mailing list:
- https://ffmpeg.org/pipermail/ffmpeg-devel/2020-November/272826.html

Modifications authored by ferntherobot on May 18, 2025.

This build is licensed under the GNU **LGPL v2.1 or later**, consistent with the original FFmpeg licensing. Note: Some components of FFmpeg are licensed under the GPL; see below for more information.

### License

FFmpeg is primarily licensed under the GNU **Lesser General Public License (LGPL) v2.1 or later**, with some optional parts under the **GNU General Public License (GPL) v2 or later**. For details, see the `COPYING.LGPLv2.1` and `COPYING.GPLv2` files in this repository.

If you build FFmpeg with GPL-only components enabled, the resulting binaries are subject to the terms of the GPL.

### Credits

This fork includes modifications based on contributions by **Yakov Okshtein** and **Andriy Gelman**, as posted on the ffmpeg-devel mailing list in November 2020:
- https://ffmpeg.org/pipermail/ffmpeg-devel/2020-November/272826.html


FFmpeg README
=============

FFmpeg is a collection of libraries and tools to process multimedia content
such as audio, video, subtitles and related metadata.

## Libraries

* `libavcodec` provides implementation of a wider range of codecs.
* `libavformat` implements streaming protocols, container formats and basic I/O access.
* `libavutil` includes hashers, decompressors and miscellaneous utility functions.
* `libavfilter` provides means to alter decoded audio and video through a directed graph of connected filters.
* `libavdevice` provides an abstraction to access capture and playback devices.
* `libswresample` implements audio mixing and resampling routines.
* `libswscale` implements color conversion and scaling routines.

## Tools

* [ffmpeg](https://ffmpeg.org/ffmpeg.html) is a command line toolbox to
  manipulate, convert and stream multimedia content.
* [ffplay](https://ffmpeg.org/ffplay.html) is a minimalistic multimedia player.
* [ffprobe](https://ffmpeg.org/ffprobe.html) is a simple analysis tool to inspect
  multimedia content.
* Additional small tools such as `aviocat`, `ismindex` and `qt-faststart`.

## Documentation

The offline documentation is available in the **doc/** directory.

The online documentation is available in the main [website](https://ffmpeg.org)
and in the [wiki](https://trac.ffmpeg.org).

### Examples

Coding examples are available in the **doc/examples** directory.

## License

FFmpeg codebase is mainly LGPL-licensed with optional components licensed under
GPL. Please refer to the LICENSE file for detailed information.

## Contributing

Patches should be submitted to the ffmpeg-devel mailing list using
`git format-patch` or `git send-email`. Github pull requests should be
avoided because they are not part of our review process and will be ignored.
