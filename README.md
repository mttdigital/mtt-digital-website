# MTT Digital — Agency Website

Live marketing site for MTT Digital (AI-assisted website agency).

## Structure
- `index.html` — main site (Home, Services, Portfolio, Pricing, Process, About, FAQ, Contact)
- `portfolio/restaurant/index.html` — concept portfolio demo (Manipal Tandoor House)

## Deploy
Static site, zero build step. **Deploy with Netlify** (chosen over Vercel — Netlify's free plan explicitly permits commercial/client use; Vercel's Hobby plan legally restricts you to non-commercial projects). Push to a repo under your personal GitHub account, then import it in Netlify — no framework, no config required.

## Before going live
- ~~Replace WhatsApp placeholder~~ — done, WhatsApp number is live (+91 77604 96577).
- ~~Replace placeholder email~~ — done, business email is mttdigital.sol@gmail.com throughout (Contact section, mailto link, form backend, footer, templates).
- Contact form uses [FormSubmit.co](https://formsubmit.co) (no signup/API key needed) posting to mttdigital.sol@gmail.com. **Important:** the very first submission after deploy triggers a one-time confirmation email to that inbox — you must open it and click the activation link, or submissions after that first one won't be delivered. Test this yourself right after going live.
- Once a custom domain is purchased (mttdigital.in), connect it in your hosting provider's dashboard.
