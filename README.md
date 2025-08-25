# SlateMate — Support

A macOS tool for automated, batch video slating.

## Contact
- Email: [shuen.zhou@outlook.com](mailto:shuen.zhou@outlook.com)

## Quick Help / FAQ
- **Minimum macOS**: 14.0 or later.
- **Where does processing happen?** 100% on your Mac. No uploads.
- **CSV format**: Header with `Shot` and `Submission Notes`. If missing, the first two columns are used.
- **Why can’t I export to the same folder?** To prevent overwriting source media.
- **Codecs**: Export “Same as Original”, DNxHR SQ, or ProRes 422.
- **Timecode alignment**: Optional start TC at frame 1000 (24/25 fps).
- **Custom backgrounds & thumbnails**: Built‑in preset plus PNG import.

## Report a bug
Please include:
- SlateMate version and macOS version
- Steps to reproduce, expected vs. actual result
- Error text from the app (and a screenshot if possible)
- A small test clip and the CSV (redact sensitive data)

## Troubleshooting
- **“Required external tools not found”**: Reinstall/update the app; tools are bundled and should resolve automatically.
- **No videos found**: Supported extensions are `mp4`, `mov`, `avi`, `mkv`.
- **Permission errors**: Use the “Browse…” buttons to grant folder/file access.
- **ProRes/DNxHR issues**: Try an alternate export format or “Same as Original”.

## Privacy
We do not collect personal data. See our [Privacy Policy](https://shuenzhou.github.io/SlateMate-privacy/).

## Open Source Licenses
This app bundles:
- FFmpeg — licensed under LGPL v2.1+.  
  License: [https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html](https://shuenzhou.github.io/SlateMate-privacy/)  
  Project legal page: [https://ffmpeg.org/legal.html](https://ffmpeg.org/legal.html)

- ImageMagick — licensed under Apache 2.0.  
  License: [https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)
  Project license page: [https://imagemagick.org/script/license.php](https://imagemagick.org/script/license.php)

Corresponding source code and build configuration for the bundled components are available upon request at [shuen.zhou@outlook.com](mailto:shuen.zhou@outlook.com).



---

© 2025 Xuan Zhou
