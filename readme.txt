ConvertX Studio v2
==================

START
1. Extract ConvertX-Studio.zip.
2. Open index.html in an up-to-date Chrome or Edge browser.
3. Add files in Convert files. Output format defaults to Auto-detect.
4. Convert and use the individual Download links.

FEATURES
- Automatic image/audio/video detection from MIME type and common extensions.
- Auto output format by media category (WEBP for images, MP3 for audio, MP4 for video).
- Separate Image, Video and Audio Studio tabs.
- Image conversion (PNG/JPG/WEBP), resizing, aspect-ratio lock and quality controls using browser canvas.
- Video resolution, brightness, contrast, saturation, sharpening and denoising controls.
- Audio bitrate, sample-rate and volume controls.
- Batch jobs, per-file downloads, session history.
- Top and bottom ad placement placeholders.

IMPORTANT TECHNICAL NOTES
- Image tools use the browser's native image decoder/canvas. Browser-readable image formats are supported; animated GIF export is a still frame.
- Audio/video tools load FFmpeg.wasm from jsDelivr on first use. An internet connection is required to download the engine.
- Processing runs in browser memory; files are not intentionally uploaded to a ConvertX server.
- Some codecs/containers may not be supported by the FFmpeg build. Very large videos can exceed browser memory.
- The resolution setting changes dimensions; upscaling does not create genuine detail.
- This is a static website package. It is not deployed or connected to an ad network.

ADS / REVENUE
Ad boxes are placeholders only. To show real ads, host the site on a domain you control, apply to an ad network, and after approval replace the placeholder sections with the network's official ad code. You will also need a privacy policy and any required cookie/consent setup. Never click your own ads or encourage invalid clicks. Ad-network accounts and payments may require an adult account holder; if under 18, have a parent/guardian manage the account as required by the provider.
