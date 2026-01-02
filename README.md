# EvacSafe Static Website (GitHub Pages)

## Wat zit erin
- Meerdere pagina's: Home, Oplossingen, Projecten, Over EvacSafe, Onderhoud, Contact
- Responsive design
- Jouw logo staat in de header en footer
- Cinematic visuals staan in `assets/img/`
- Contactformulier is een placeholder (GitHub Pages heeft geen backend)

## Upload naar GitHub
1. Maak een repo aan (bijv. `evacsafe-site`).
2. Upload alle bestanden uit deze map naar de root van je repo.
3. Ga naar **Settings** → **Pages**
4. Source: **Deploy from a branch**
5. Branch: **main** en folder: **/ (root)**
6. Save

Na publicatie staat je site live op:
`https://<jouw-username>.github.io/<repo-naam>/`

## Contactformulier koppelen (later)
- Gebruik Formspree, Getform, Basin of Netlify Forms
- Vervang in `contact.html` de `form action="#"` door de URL van je dienst