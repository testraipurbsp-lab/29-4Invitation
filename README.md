# पंचकल्याणक महोत्सव निमंत्रण वेबसाइट (रायपुर)

सादा HTML + CSS + JS। कोई build या server नहीं चाहिए।

## GitHub Pages पर live करना
1. GitHub पर नई repository बनाइए (Public)।
2. इस folder की सारी फ़ाइलें upload कीजिए: `index.html`, `img/` फ़ोल्डर, `.nojekyll`।
3. Repository → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, Folder: `/ (root)` → Save।
4. 1–2 मिनट में link मिलेगा: `https://<username>.github.io/<repo-name>/`

## बाद में फ़ोटो जोड़ना
`सतार इन्द्र` और `अच्युत इन्द्र` की फ़ोटो अभी नहीं है। इन नामों से JPG फ़ाइल `img/` में डाल दीजिए, साइट अपने आप दिखा देगी:
- `img/15-satar.jpg`
- `img/20-achyut.jpg`

## कार्ड का क्रम / नाम बदलना
`index.html` में `class="pk rv"` वाले `<figure>` ब्लॉक खोजिए। हर कार्ड में पद (`.pt`), फ़ोटो (`img/…jpg`) और नाम (`figcaption`) है।

## WhatsApp preview फ़ोटो (वैकल्पिक)
Live link मिलने के बाद `<head>` में यह line जोड़ सकते हैं (पूरा link डालिए):
`<meta property="og:image" content="https://<username>.github.io/<repo-name>/img/05-kuber.jpg">`
