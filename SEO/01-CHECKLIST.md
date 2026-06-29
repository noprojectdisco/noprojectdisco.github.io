# Checklist SEO — No Project Disco

Lo técnico del sitio ya quedó hecho y publicado (JSON-LD, canonical, robots.txt, sitemap.xml, title).
Esta lista es **lo único que tienes que hacer tú**. Orden de impacto. Marca con [x] al terminar.

---

## 1. Google Search Console  ·  ~10 min  ·  IMPRESCINDIBLE
Es lo que hace que Google "vea" todo lo demás.

- [ ] Entra a https://search.google.com/search-console con tu cuenta Google.
- [ ] Agrega propiedad → **Prefijo de URL** → `https://noprojectdisco.github.io/`
- [ ] Verificación: elige **"Etiqueta HTML"**. Te dará una línea `<meta name="google-site-verification" ...>`.
      → Pégamela en un mensaje y yo la inserto en el `<head>`. (O súbela tú entre las otras `<meta>` del index.html.)
- [ ] Una vez verificado: menú **Sitemaps** → escribe `sitemap.xml` → Enviar.
- [ ] Menú **Inspección de URLs** → pega `https://noprojectdisco.github.io/` → "Solicitar indexación".

## 2. Wikidata  ·  ~20 min  ·  alimenta el Knowledge Panel
- [ ] Crea cuenta en https://www.wikidata.org → "Create a new account".
- [ ] Abre `02-WIKIDATA.md` (en esta carpeta) y sigue los campos ya redactados. Es copiar/pegar.

## 3. Reclamar perfiles de plataforma  ·  ~15 min  ·  consistencia = confianza para Google
La bio, ciudad y género deben ser **idénticas** a las del sitio.
- [ ] **Spotify for Artists** → https://artists.spotify.com → reclama "No Project Disco".
      Bio sugerida y ciudad en `02-WIKIDATA.md`. Pon "Colima, México" como ubicación.
- [ ] **Apple Music for Artists** → https://artists.apple.com → reclama el perfil.
- [ ] Revisa que IG, YouTube y Facebook tengan "Colima, México" visible en el perfil/about.

## 4. Prensa local  ·  esfuerzo variable  ·  ESTO es lo que vuelve real "la más influyente de Colima"
Google asocia "banda importante + Colima" cuando medios lo dicen y enlazan tu sitio.
- [ ] Abre `03-NOTA-DE-PRENSA.md`. Tiene la nota lista + lista de medios + email de envío.
- [ ] Envía a los medios de Colima. Meta mínima: 3–4 notas con enlace a noprojectdisco.github.io.

## 5. Más adelante (opcional, alto impacto)
- [ ] Comprar dominio `noprojectdisco.com` y apuntarlo a GitHub Pages (yo te configuro el CNAME).
- [ ] Página de letras indexable (ya tienes los textos en /LETRAS) → captura búsquedas de tus canciones.

---

### Lo que YO ya dejé hecho (no tienes que tocar nada)
- `index.html`: datos estructurados `MusicGroup` (banda, Colima, género, miembros, álbum, enlaces a tus 5 plataformas), `<title>` orientado a búsqueda, `canonical`.
- `robots.txt` y `sitemap.xml` creados.
- Todo commiteado y publicado en GitHub Pages.
