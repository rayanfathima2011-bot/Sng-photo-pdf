# Photo ⇄ AES-256 PDF (PWA)

GitHub Pages-இல் பதிவேற்றத் தயாராக உள்ள கோப்புகள்:
- `index.html` — முழு HD & AES-256 செயலி
- `manifest.json` — மொபைலில் ஆப் போல நிறுவ (Install / Add to Home Screen)
- `sw.js` — ஆஃப்லைன் பயன்பாட்டிற்கான Service Worker
- `icon.svg` — ஆப் ஐகான்

## GitHub Pages-இல் அமைக்கும் முறை
1. GitHub-இல் ஒரு புதிய **Public Repository** உருவாக்கவும்.
2. இந்த ZIP கோப்பை Extract செய்து உள்ளே உள்ள 4 கோப்புகளையும் (`index.html`, `manifest.json`, `sw.js`, `icon.svg`) Repository-இல் **Upload files** மூலம் பதிவேற்றி **Commit changes** செய்யவும்.
3. **Settings → Pages → Deploy from a branch (`main` / `/root`) → Save** கொடுக்கவும்.
4. கிடைக்கும் `https://<username>.github.io/<repo>/` இணைப்பை Chrome-இல் திறந்து **Install app / Add to Home screen** அழுத்தவும்.
