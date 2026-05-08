# Djeli Coaching

Site web officiel de Djeli Coaching — coaching de transformation pour femmes CSP+, à la croisée de la PNL, de la CNV et de la tradition Djeli.

> Je te ramène à ta propre histoire.

## Stack

- HTML/CSS/JS statique single-file (`index.html`)
- Pas de build step. Vercel sert directement.
- Fonts : Fraunces (display), Instrument Serif (italic), Satoshi (body)

## Déploiement

Auto-deploy sur Vercel à chaque push sur `main`. Production : voir Vercel dashboard.

## Structure

- `/index.html` — page unique avec toutes les sections (Hero, Qui suis-je, Outils, Pour qui, Parcours, Call Découverte, Footer)
- `/vercel.json` — config Vercel (headers Content-Type)
- `/robots.txt` — autorisations crawlers
- `/sitemap.xml` — liste des URLs

## À faire (post-launch)

- [ ] Photo réelle de la coach (remplacer Unsplash dans `.about-img`)
- [ ] Vrai lien Calendly sur le CTA "Réserver mon Call Découverte"
- [ ] Email officiel (placeholder `contact@djeli-coaching.com`)
- [ ] Domaine custom (acheter `djeli-coaching.fr` ou similaire)
- [ ] Témoignages clients quand disponibles
