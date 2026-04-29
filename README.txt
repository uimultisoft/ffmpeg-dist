Natural Studio - Open Source Attribution

This application includes a modified version of FFmpeg, which is licensed under the GNU GENERAL PUBLIC LICENSE Version 3.

FFmpeg Integration:
The executable NS.exe included in this package is a derivative of the FFmpeg multimedia framework.

Modifications Made:
To integrate this tool into the Natural Studio environment, the following changes were applied to the FFmpeg binary:
- Visual Branding: Updated application icon and file metadata.
- Subsystem Change: Modified the executable header from 'Windows Console' to 'Windows GUI' to allow background processing without a persistent terminal window.

License Compliance & Source Code:
In accordance with the GPLv3:
1. Original Source: The original FFmpeg source code used for this version is included in this repository as FFmpeg-6d60cc7baf662b64e3c50f95826dead58cf8e839.
2. Corresponding Source: The source code for our modifications, including the build scripts and assets used to generate the modified binary, is publicly available at: https://github.com/uimultisoft/ffmpeg-dist
3. App Separation: Our main application is a separate, proprietary work that interacts with the FFmpeg binary via standard command-line interfaces. It is not a derivative work of FFmpeg and remains under our proprietary license.

DISCLAIMER:
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
