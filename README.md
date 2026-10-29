# ffmpeg-binaries

Prebuilt FFmpeg archives bundled into the Platto desktop app at build time
(`frontend/src-tauri/build/ffmpeg.rs` in yaniamac/platto). The build verifies each
archive against the SHA-256 values in `SHA256SUMS`.

FFmpeg is licensed under the LGPL/GPL; see https://ffmpeg.org/legal.html. Source code
for FFmpeg is available at https://ffmpeg.org/download.html.
