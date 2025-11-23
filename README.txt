Vic Medicals — Admin wrapper
Files included:
- index.html (full-screen wrapper with bottom-left 'Vic medicals' label)
- styles.css
- script.js (warm-up + placeholder + fast reveal + postMessage helper)
- sw.js (service worker to cache wrapper shell)
- manifest.json
- README.txt

Usage:
1. Extract and upload files to your host root or open index.html locally.
2. The cover label opens the dashboard in a new tab. Double-click or long-press it to hide.
3. To make app-links reliable from the framed site, use parent.postMessage({type:'open-external', url:'whatsapp://send?text=Hello'},'*') inside that site's JS or ensure links use target="_blank" with app-schemes.

Target: https://preview--vicnovos-healthes-hub-54332.lovable.app/admin/adm-6f3b2c
