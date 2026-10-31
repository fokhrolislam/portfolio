# Fokhrol Islam · Portfolio

Full-stack developer in Dhaka, Bangladesh. Founder of [Sabaq](https://sabaaq.com). This page lists the products, client builds and fixes I have delivered, most of them in 2026. Client code stays with the clients; what is public is linked.

**Stack:** PHP · Laravel · MySQL · Flutter · Dart · WordPress · Elementor · WooCommerce · Wix Studio · Capacitor · Supabase · TypeScript · React · Bun · Linux / cPanel · Bash · Node.js · Playwright

---

## Products I own

### Sabaq (ছবক) · madrasa and school management · [sabaaq.com](https://sabaaq.com) · [Play Store](https://play.google.com/store/apps/details?id=com.sabaaq.sabaq_app)
Multi-tenant Laravel SaaS, one site and database per institution, 700+ institutions. Flutter app for staff and guardians (Bangla, English, Arabic), Sanctum API layer that mirrors the web application field for field, fleet deployment with contract gates across 370+ live sites, self-serve free trial with WhatsApp OTP, licence enforcement, biometric attendance, SMS gateway, board exam registration, board-exam forms printed from system data. Overview: [sabaq-madrasa-management](https://github.com/fokhrolislam/sabaq-madrasa-management).

### Sabaq helpline chatbot
Laravel + Gemini support bot that answers staff questions about every module of the software in Bangla, with a catalogue of 350+ curated answers and version-aware notes for each app release.

### Sabaq marketing (CTWA)
Laravel app that captures Click-to-WhatsApp ad leads through the YCloud webhook, stores the chat history, syncs audiences and reports lead quality per ad.

### Sabaq support tools
Password-protected tool hub for the support team: trial leads with usage scoring and WhatsApp-verified badges, due checks, push result checks, answer finder.

### Sabaq feature video
Remotion-rendered product video (16:9 and 9:16) of the app, Bangla narration, built from real app screens.

---

## WordPress and Elementor builds

| Site | Work |
|---|---|
| [luetolf-partner.ch](https://luetolf-partner.ch) | Full site built in Elementor from designer HTML, header and footer builder, no custom code constraint |
| [novo-immo.marketing](https://novo-immo.marketing) | Real-estate homepage rebuilt in Elementor, theme-builder conditions and .htaccess issues solved |
| [caseandclause.co.uk](https://caseandclause.co.uk) | Legal consultancy site from the client's developer pack, booking flow |
| [lspeptides.co.uk](https://lspeptides.co.uk) | UK peptide WooCommerce build, brand system, legal register that gates the catalogue |
| [elegance-outlet.com](https://elegance-outlet.com) | Watch shop: hand-delivery option with 50 EUR deposit plugin, order flow fixes |
| [nextglow.be](https://nextglow.be) | "Reset 30" WooCommerce + Brevo automation plugin, quiz promo-code plugin with stacking rules |
| [planrevente.com](https://planrevente.com) | Anti-bot forms, weekly promo-code job, email sequence, Meta Conversions API for Lead and Purchase |
| [madeofyucca.com](https://madeofyucca.com) | YuSnack homepage rebuild, WooCommerce + Square, state-limited shipping rules |
| [goldfactoryonline.co.uk](https://goldfactoryonline.co.uk) | Live gold pricing, product options, SEO, WP Super Cache + WooCommerce basket-leak fix, Tawk widget customisation |
| [attn2detail.info](https://attn2detail.info) | Gravity Forms 3 breakage fixed across 26 forms, thank-you page rebuild, lead-drop investigation, agency hand-over clean-up |
| [komor.de](https://komor.de) | Found and fixed the "critical error on publish" (double-serialized page-builder meta), self-healing guard, Elementor removal |
| [institute-ln.com](https://institute-ln.com) | Speed work, homepage and faculty rework |
| Pikliz on Wheelz | Haitian food WooCommerce (Woodmart, GoDaddy): spice-builder product, catering page, sandbox-only PHP under a managed-host cache ban |
| Profab | Figma to Elementor rebuild with a documented pattern library and gotcha list |
| ChimneyForce, Druck-Manager, Vets on the Block, ELIS, Mindify, NOVO | React, Lovable, Wix and Figma designs converted to importable Elementor JSON on agency staging, including Hebrew RTL and multi-step MetForm wizards |
| dicmadrasha.com | WordPress site fed live data from the madrasa's Sabaq tenant through a custom plugin |

Field notes from these jobs: [wordpress-field-notes](https://github.com/fokhrolislam/wordpress-field-notes).

## Wix Studio

- [freeart-studio.ch](https://www.freeart-studio.ch): gallery site for a Swiss art studio, built from a brief and a prototype.
- Freeart Holding AG one-pager, duplicated and published in Wix Studio.

## Mobile and SaaS for clients

- **Balance** wellness app: Capacitor 7 + Supabase, App Store and Play launch.
- **Employee pulse SaaS** (unreleased, under confidentiality, so no name or link): homepage with a clickable product demo, full brand kit, sample AI reports, and a takeover of the TypeScript backend in progress (Bun, Hono, oRPC, Drizzle), starting with role checks, anonymity fixes and migration repair.
- Audit and scoping of a social-media scheduling SaaS (Next.js + Supabase).

## Security and recovery

- sabaaq.com: account takeover with 11,500 casino spam posts cleaned, update path re-protected, iPhone content-filter block diagnosed.
- fmfschool.edu.bd and dialab.pro: malware removed (backdoor plugin, hidden admins, zero-byte shells, traffic-direction redirect), hardening advice.
- Sabaq fleet: licence-expiry lock added to the API within one day of the gap being reported, 372 sites patched with md5-guarded rollouts.

## SEO and content

- sabaaq.com: 59 Bangla template pages with downloadable Word files, Search Console indexing queue, district filter clean-up, print gallery of 102 real documents.
- attn2detail.info and institute-ln.com audits with method notes on what not to claim before verifying.

## Tooling I built along the way

- [php-number-format-dart](https://github.com/fokhrolislam/php-number-format-dart), [bangla-utils-dart](https://github.com/fokhrolislam/bangla-utils-dart), [flutter-risk-scans](https://github.com/fokhrolislam/flutter-risk-scans), [site-visual-scan](https://github.com/fokhrolislam/site-visual-scan)
- Fleet deployment with delta packages, prerequisite md5 lists, parity scans and per-site rollback
- Repo redaction gate that blocks any commit carrying a secret or a real phone number
- Remote WordPress operation through a REST-first CLI: file transfer in XOR-encoded chunks past WAFs, PHP execution with JSON payloads, WP-CLI on sibling installs

---

Client work with screenshots: [xspider.net/our-work](https://xspider.net/our-work/)

Contact: [sabaaq.com](https://sabaaq.com) · Dhaka, Bangladesh
