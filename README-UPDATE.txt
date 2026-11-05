TOOLZEN COMPLETE MULTI-PAGE UPDATE
==================================

Brand: ToolZen
GitHub Pages base URL: https://abdul-wahab1101.github.io/toolzen-tools/
Support email: aw376552@gmail.com
Tools listed on home page: 30 (26 existing browser tools + CV Maker, Document Scanner, PDF to Word and Word to PDF).

IMPORTANT: Replace the repository contents with this package and PRESERVE THE FOLDER STRUCTURE.

1. Download this ZIP and Extract All.
2. Open your existing GitHub repository: toolzen-tools.
3. Add file -> Upload files.
4. Upload every file and folder from the extracted package into the repository root. Do not upload only the ZIP.
5. Commit to main. If GitHub reports files with the same paths, choose replace/overwrite for this update.
6. Keep GitHub Pages source on main / (root).
7. Wait for the Pages build to finish in Actions, then hard-refresh the live site.

New interactive pages:
- /cv-maker/ - Build a CV in-browser; export a PDF. It does not guarantee job outcomes.
- /document-scanner/ - Camera or image scan, crop and export JPG/single-page PDF. No OCR or auto perspective correction.
- /pdf-to-word/ - Extract selectable text from PDF into DOCX. Does not preserve original complex layout/images/tables; scanned PDFs need OCR.
- /word-to-pdf/ - Convert .docx to PDF. Old .doc files unsupported; complex layouts may change.

Sharing:
- Output pages offer Download and Share file where Web Share API supports files.
- The native share sheet may show apps like WhatsApp or Google Drive depending on the device and browser.
- WhatsApp page action shares the ToolZen page URL, not the generated file.
- Direct Google Drive upload OAuth is NOT included in this version. Do not describe it as automatic Drive upload.

Privacy:
- File contents are processed in the browser by the current code. No ToolZen file-upload endpoint is included.
- Some libraries are loaded from public CDNs on demand. File contents are not sent to those CDNs by this code.
- CDN providers/host providers may receive normal connection metadata.

Ads:
- Ad slots are empty placeholders only. No ad network script is installed.

Testing notes:
- Test image compressor, resizer, converter, JPG-to-PDF, merge, split, rotate, PDF-to-JPG, CV Maker, Document Scanner, PDF-to-Word and Word-to-PDF.
- PDF-to-Word is text extraction, not layout-perfect conversion. Test on a text-based PDF.
- Scanner camera requires HTTPS and browser camera permission.
- Some advanced pages load libraries from CDNs, so a network connection is needed at first use.
- Mobile devices may have memory limits for large files.

No CV-maker.html was supplied in the conversation, so a new browser-based CV Maker has been created in this package rather than copying a missing file.
