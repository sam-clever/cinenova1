CineNova two-page setup

1. Keep index.html and download.html in the same folder.
2. Host BOTH files on the same website origin (same domain, protocol and port), for example in the same Netlify publish folder.
3. Do not test by double-clicking the files as file:// URLs; IndexedDB sharing is unreliable there.
4. Open the hosted index.html, then click Download on a title.
5. The download page now previews audio/video inline and provides Download File links.

Important: media stored in the browser IndexedDB is local to that browser and origin. Upload/publish the site files does not automatically upload the media blobs. Re-upload media on the hosted CineNova site or use a backend media URL if the hosted site needs to serve it to other visitors.

