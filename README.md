# Diānas digitālā vizītkarte

Atver `index.html` pārlūkā. Faili: `index.html`, `style.css`, `diana.svg`.

## Kur izpildīta katra prasība

**Vizītkarte (HTML pamati):** `<title>`, `<h1 id="vards">`, `<h2>Par mani`, rindkopas, `<ul>` ar 4 hobijiem, `<strong>` + `<em>`, `<img>` ar `alt`, ārēja saite uz w3schools.com, `<br>`, `<hr>`, `<ol>`.

**N2 (semantika, tabula, forma):** `header` ar logo, `nav` ar 5 saitēm `ul/li`, viens `main`, 5 × `section` ar `h2`, `article.kartite`, `footer`, tabula „Prasmes” (6 rindas, `th`), forma (vārds, e-pasts, `select`, `textarea`, poga), `label for/id`, `aside` „Īsumā par mani”.

**N3 (CSS selektori):** ārējs `style.css`; `body` fonts/krāsa; `.izcelts` uz `<span>` un `<td>`; `#vards`; `nav a` + `nav a:hover`; `input[type="email"]`; kaskāde (2 × `h2`) un specifiskums (`p` / `.citats` / `#moto`) ar komentāriem; `h1, h2, h3`; `tr:nth-child(even)`; `!important` komentārs.

**N4 (box modelis, krāsas, fonti):** `white`, `#1a5fb4`, `rgb(...)`; dažādi foni body/header/footer (kontrasts ≥ 4.5); Lora virsrakstiem, Inter tekstam ar rezerves fontiem; `font-size`, `line-height`, `text-align`; sekcijām `border` + `border-radius` + `padding` + `margin`; `main { max-width; margin: 0 auto }`; `.kartite` 280px → 318px (content-box) / 280px, saturs 242px (border-box) — komentārā; margin sabrukšana (30px); `input:focus` outline; Google Fonts.
