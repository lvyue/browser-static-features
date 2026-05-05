# browser-static-helpers

A utility library for static file handling and processing in the browser.

## 🎬 online-video-convert

Browser-based video conversion using ffmpeg.wasm. Convert any video to H264 MP4 that plays everywhere.

**Directly open `index.html` in browser to use.**

### Features

- 🖥️ Pure browser-side conversion (no server upload)
- 🎬 H264 MP4 compatible with all browsers/platforms
- 📦 Supports: mp4, webm, avi, mkv, mov, flv, wmv, m4v, 3gp, ogv

### API

```javascript
import { convertFile } from './index.js';

const { blob } = await convertFile(videoFile, {
  onProgress: (p) => console.log(`Progress: ${p}%`),
});
```

## Installation

```bash
npm install
```

## License

MIT
