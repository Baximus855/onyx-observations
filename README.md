# onyx-observations

## Link-rot spot check: Colossal Cave Adventure source page

Observed 2026-08-08 00:49 SAST (2026-08-07 22:49 UTC)
Device: Samsung Galaxy A56 5G. Browser: Brave. DNS: NextDNS. VPN: ProtonVPN.
Method: manual traversal of pingback links listed under
jerz.setonhill.edu/intfic/colossal-cave-adventure/
All targets are syndications of a single Colossal Cave review dated 2023-01-20.

| Target | State observed |
|---|---|
| worldnewsbook.xyz/2023/01/20/colossal-cave-review-extreme-retro-gaming/ | Blocked by Bitdefender Web Protection, "untrusted page" |
| newsment.xyz | GoDaddy parking page, domain for sale, USD 699 outright or USD 100/month lease-to-own |
| techtelegraph.co.uk/colos... | TLS failure, NET::ERR_CERT_COMMON_NAME_INVALID |
| phonenews.net/uk/1/colossal-cav... | HTTP 410 Gone |
| thronews.wiki/2023/01/20/colossa... | No DNS record, DNS_PROBE_POSSIBLE |
| game.guestpostsitels.site/colossal... | No DNS record, DNS_PROBE_POSSIBLE |
| web.archive.org/web/20091227141920/... (Russotto ADVENT mirror) | HTTP 429 Too Many Requests, nginx |
| dhq.digitalhumanities.org/vol/001/2/000009.html | "Resource not found" |

Control, same session, same device:
| advdat.77-03-11 (Crowther original data file, dated 1977-03-11) | Retrieved and rendered without error |

Notes:
- The DHQ failure is a URL-scheme change, not a takedown. The article is live at
  dhq.digitalhumanities.org/vol/1/2/000009/000009.html and as a static PDF at
  dhq-static.digitalhumanities.org/pdf/000009.pdf. The stale path is the one
  published in the author's own citation on his own site.
- The Bitdefender result is that vendor's classification, not an independent
  determination that the site is malicious. Recorded as observed, no inference drawn.
- The Internet Archive 429 is a rate limit, not a loss. Recorded because it means the
  fallback was unavailable at time of check.
- DNS and registration states are volatile. This table records one moment only.

Tier A: directly observed and screenshotted at the stated time.
