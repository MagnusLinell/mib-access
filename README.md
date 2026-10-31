# MIB – Agent M Access Terminal

A **fictional** Men in Black–inspired Halloween costume website. Scanning your badge QR code can open a page that simulates an agent verification and displays **ACCESS AUTHORIZED / AGENT M**.

Everything runs in the visitor's browser. No real login, server, tracking, or authentication. The site includes an image of the person on the card, so publish only if you are comfortable making that portrait public.

## Publicera på GitHub Pages (svenska)

1. Logga in på [github.com](https://github.com) och skapa ett nytt **public** repository. Döp det t.ex. till `mib-agent-m`.
2. Extrahera ZIP-filen. Ladda upp **`index.html`**, **`assets/agent-m.webp`**, samt **`.nojekyll`** till repositoryt. Behåll mappen `assets` och dess fil. Tips: GitHubs **Add file → Upload files** låter dig dra in filer och mappar.
3. Under **Settings → Pages → Build and deployment**, välj **Deploy from a branch**, sedan **main**, **/(root)** och klicka **Save**.
4. Öppna sidan med adressen `https://DITT-GITHUB-NAMN.github.io/mib-agent-m/` (om repositoryt heter `mib-agent-m`). Kontrollera den riktiga URL:en via **Settings → Pages → Visit site**.
5. Skapa en QR-kod till den **verkliga publika URL:en** och placera QR-koden på MIB-kortets baksida. QR-koden är bara en länk – statusen på sidan är en kul filmeffekt.

OBS: Om du väljer ett annat namn på ditt repository ändras sista delen av URL:en. Webbplatsen fungerar även lokalt genom att öppna `index.html` i en webbläsare.

## Files

- `index.html` – all page layout, styling and animations (no external libraries)
- `assets/agent-m.webp` – Agent M portrait derived directly from your original uploaded photograph, with sunglasses overlaid; original face and hair retained
- `.nojekyll` – instructs GitHub Pages to publish the files without Jekyll processing

## Customization

Edit the HTML file to change `AGENT M`, `MIB-7746-09`, `LEVEL IX`, or the messages. To update the photo, replace `assets/agent-m.webp` with an image of the same name.

This is a **fictional cosplay prop** and is not associated with any official organization or movie studio.
