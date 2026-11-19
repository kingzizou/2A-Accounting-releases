# Bundled libraries

Shipped with the app (instead of loading them from the internet each time) so the desktop app and the
web app can start with no internet connection (offline mode, 2.1.8).

| File | Library | Version | Licence |
|---|---|---|---|
| supabase-js-2.118.0.js | @supabase/supabase-js (UMD build) | 2.118.0 | MIT (LICENSE-supabase-js.txt) |
| xlsx-0.18.5.full.min.js | SheetJS xlsx | 0.18.5 | Apache 2.0 (LICENSE-xlsx.txt) |

To update one: download the new build, save it here with the version in the file name, change the
`<script>` line near the top of index.html, and add the new name to web/sw.js (SHELL list).
