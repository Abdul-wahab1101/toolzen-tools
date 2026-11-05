TOOLZEN STARTER (working name only)
=================================

This is a static, browser-side image tools website. It does not need Python,
Streamlit, Groq, Supabase, a database, or an API key.

Included in this first build:
- Image compression with target maximum presets: 20 KB, 50 KB, 100 KB,
  200 KB, 500 KB, 1 MB, 2 MB, 5 MB, and a custom size from 20 KB to 5 MB.
- Image resizing with optional aspect-ratio preservation.
- Image format conversion to WebP, JPG, or PNG.
- Local browser-side processing (no upload endpoint in this starter).
- Responsive layout and mobile menu.

Important limitations:
- This first build supports common JPG, PNG, WebP and GIF input. HEIC may not
  work in all browsers. GIF is processed as a still image (first frame).
- Very small target sizes are not always achievable without noticeable quality
  loss. The app reports the actual output size and warns when it misses the target.
- The first build accepts images up to 25 MB to reduce browser memory problems.
- PDF tools are not included yet; they will be added and tested separately.
- “ToolZen” is the current working label only; its domain, social handles and trademark have not been legally cleared or reserved. Verify these before investing in the brand.

LOCAL TEST:
1. Open index.html in a modern browser such as Chrome or Edge.
2. Choose a JPG/PNG/WebP image.
3. Try Compress (for example 200 KB), Resize, and Convert.
4. Check the output size and open the downloaded file.

GITHUB PAGES PUBLISHING (when ready):
1. Create a new PUBLIC GitHub repository, e.g. toolzen-tools (temporary repo name).
2. Upload index.html and README.txt to the repository root.
3. Open Settings > Pages.
4. Under Build and deployment choose “Deploy from a branch”.
5. Select branch “main”, folder “/(root)”, then Save.
6. Use the “Visit site” link after the deployment completes.

GitHub Pages sites from public repositories are public on the internet. Do not
place API keys, passwords, private documents, or user files in this repository.
