# ELLES — paquet de desplegament

Aquest paquet separa l’HTML, el CSS i el JavaScript per facilitar el manteniment i el desplegament estàtic. El contingut literari i la interfície s’han preservat en aquesta primera neteja estructural.

## Publicació de proves

Es pot desplegar la carpeta sencera a Cloudflare Pages (Direct Upload) o connectar-la a un repositori Git. La pàgina d’entrada és `index.html`.

## Abans d’obrir al públic

- Migrar `localStorage` a Supabase amb autenticació i polítiques RLS.
- Implementar confirmació de pagament al servidor (Stripe Checkout + webhook).
- No exposar claus secretes al navegador.
- Revisar privacitat, consentiment, condicions de compra i còpies de seguretat.
- Fer proves de navegació, accessibilitat i mòbil.

Aquest paquet encara no connecta Supabase ni Stripe i no activa cobraments reals.
