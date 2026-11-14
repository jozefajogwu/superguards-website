# Superguards Ltd — Website

Official website for **Superguards Ltd**, an NSCDC-licensed private security company (Licence NSCDC/PG/007/00029, Category B) based at No. 8B Rukuba Road, Jos, Plateau State.

Static single-page site (HTML/CSS/JS, no build step), deployed on Vercel.

## Structure
```
index.html                  # the whole site
assets/
  logo-white.png            # logo for dark backgrounds
  logo-navy.png             # logo for light backgrounds / favicon
  guard-360-sprite.jpg      # 90-frame sprite for the rotating guard in the hero
  superguards-team.jpg      # About section team photo
vercel.json                 # caching headers
```

## Quote form
Submissions are emailed via [FormSubmit](https://formsubmit.co) (endpoint key in `index.html`).
The form only works when served from a web server (not when opening the file directly).

## Local preview
```
python3 -m http.server 8000
```
Then open http://localhost:8000

Built by [Hiveweb Technologies](https://hivewebtechnologies.com).
