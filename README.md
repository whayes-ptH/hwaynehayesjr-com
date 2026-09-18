# hwaynehayesjr.com

Short leadership page for **H. Wayne Hayes Jr** — static site for Netlify + custom domain `hwaynehayesjr.com`.

## Deploy (Netlify)

1. New site from Git → connect `whayes-ptH/hwaynehayesjr-com`
2. Build: none · Publish directory: `.` (or leave blank; `netlify.toml` publishes `.`)
3. Domain management → Add `hwaynehayesjr.com` and `www.hwaynehayesjr.com`
4. Copy the DNS targets Netlify shows into **Joker.com** → DNS for `hwaynehayesjr.com`

Typical Joker records (confirm against Netlify’s UI):

| Type | Name | Value |
|------|------|-------|
| A | `@` (apex) | Netlify load-balancer IP(s) shown in Netlify |
| CNAME | `www` | `<site>.netlify.app` |

Leave parking / Dynamic DNS off on Joker.

## Content rules

Restrained bio only — no vanity/hype copy. Update `index.html` for role changes.
