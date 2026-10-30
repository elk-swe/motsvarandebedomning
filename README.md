# Provkodsmotsvarigheter

Klickbar matris för att jämföra provkoder, kursmoment och möjliga motsvarigheter i röntgensjuksköterskeprogrammet.

Webbplatsen består av `index.html` och `data.json`. Dataunderlaget är provkodsregistret och följer matrisupplägget med en rad per moment.

## GitHub Pages

Arbetsflödet i `.github/workflows/pages.yml` publicerar webbplatsen när något ändras på `main`. Om GitHub ber om en publiceringskälla: öppna **Settings → Pages** och välj **GitHub Actions** under **Build and deployment → Source**.

När publiceringen är klar blir adressen:
https://elk-swe.github.io/motsvarandebedomning/
