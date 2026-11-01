# Holmes Universal Solutions — Hub

Website for https://holmesuniversal.com — a multi-page site (polished design, v3):

- `/` — Home: hero (Houston), ventures, manifesto, about the founder
- `/publishing/` — Books & Publishing: full book list (4 published, 4 in progress), CTA to tedrickholmes.com
- `/web/` — Holmes Web Solutions: packages ($999 Starter, $2,499 Professional, $99/mo Website Care), process, CTA
- `/readypic/` — ReadyPic: photography venture, CTA to readypic.org
- `/styles.css` — shared design system (Fraunces serif + Inter, navy/gold, HU monogram lockup)
- `/assets/` — hero-houston.webp, readypic.webp, web.webp, books-cover.png (real author cover art)

Hosting: Cloudflare Pages connected to this repo. DNS for holmesuniversal.com and
holmesuniversalsolutions.com is on Cloudflare (registrar remains Porkbun).

Redirects (Cloudflare Redirect Rules):
- holmesuniversalsolutions.com + www -> https://holmesuniversal.com
- books.holmesuniversal.com -> https://tedrickholmes.com
- readypic.holmesuniversal.com -> https://readypic.org
- web.holmesuniversal.com -> https://holmes-web-solutions.tedrickdh.workers.dev

Scope rule (Tedrick, 2026-11-01): projects that already have their own domains are NOT
connected to this hub, except tedrickholmes.com and ReadyPic (readypic.org).
