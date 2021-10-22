---
layout: page
title: HDR + WCG Image Viewer
permalink: /hdrimageviewer/
---

HDR + WCG Image Viewer lets you view a variety of popular high dynamic range (HDR) image formats at full visual quality on a capable HDR10 display:
* OpenEXR
* Radiance RGBE (.hdr)
* JPEG XR (including HDR game screenshots captured on Xbox and Windows)
* HEIC and AVIF with HDR10 image data

When viewing the above on a standard dynamic range (SDR) display, the app performs HDR tonemapping to achieve the best possible quality. The app also includes some useful tools for HDR developers such as rendering the image luminance as a colorized heatmap, or forcing an image to be interpreted with a specific colorspace (for example, PNG images encoded as HDR10).

In addition, you can view a variety of high bit depth and/or wide color gamut (WCG) image formats on a capable display:
* JPEG with embedded ICC profile
* TIFF

# Obtaining the App
HDR + WCG Image Viewer can be found on the [Microsoft Store](https://www.microsoft.com/store/apps/9PGN3NWPBWL9). The source code is published under the MIT license at [GitHub](https://github.com/13thsymphony/HDRImageViewer).

# Command line usage
You can invoke ```HDRImageViewer.exe``` from a command line to access advanced functionality. You should invoke HDRImageViewer from the directory containing the image you wish to load - UWP apps launched from a command line only have access to files within the working directory.

## Parameters
`-f` Start in fullscreen mode

`-h` Start with UI hidden

`-forcebt2100` Force images to use BT.2100 PQ

`-input:filename` Load `filename`

**Note: Filename must be relative to the current working directory as HDRImageViewer only has access to that directory.**

## Example
`HDRImageViewer.exe -f -h -input:myimage.jxr`



# Support
For questions and problems, email [support@13thsymphony.com](mailto:support@13thsymphony.com). Alternatively, file a bug on the [GitHub page](https://github.com/13thsymphony/HDRImageViewer).

# Privacy Policy
HDR + WCG Image Viewer does not collect, store or transmit any personal information or information about files opened by the app, except data to help fix bugs or improve the quality of the app.

# 3rd Party License Information
## [OpenEXR](http://www.openexr.com/license.html)
Copyright (c) 2002-2011, Industrial Light & Magic, a division of Lucasfilm Entertainment Company Ltd. All rights reserved. 
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met: 

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer. 
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution. 
Neither the name of Industrial Light & Magic nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission. 

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE
## [zlib](https://www.zlib.net/zlib_license.html)
  version 1.2.11, January 15th, 2017

  Copyright (C) 1995-2017 Jean-loup Gailly and Mark Adler

  This software is provided 'as-is', without any express or implied
  warranty.  In no event will the authors be held liable for any damages
  arising from the use of this software.

  Permission is granted to anyone to use this software for any purpose,
  including commercial applications, and to alter it and redistribute it
  freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must not
     claim that you wrote the original software. If you use this software
     in a product, an acknowledgment in the product documentation would be
     appreciated but is not required.
  2. Altered source versions must be plainly marked as such, and must not be
     misrepresented as being the original software.
  3. This notice may not be removed or altered from any source distribution.

  Jean-loup Gailly        Mark Adler
  jloup@gzip.org          madler@alumni.caltech.edu
## [DirectXTex](https://github.com/Microsoft/DirectXTex/blob/master/LICENSE)
Copyright (c) 2018 Microsoft Corp

Permission is hereby granted, free of charge, to any person obtaining a copy of this 
software and associated documentation files (the "Software"), to deal in the Software 
without restriction, including without limitation the rights to use, copy, modify, 
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to 
permit persons to whom the Software is furnished to do so, subject to the following 
conditions: 

The above copyright notice and this permission notice shall be included in all copies 
or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF 
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE 
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
