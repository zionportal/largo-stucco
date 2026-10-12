# Largo Stucco website demo

An isolated, responsive website concept built with Next.js App Router, TypeScript, React, and Tailwind CSS. The warm stucco design uses locally hosted licensed stock photography and a simple project-enquiry path.

## Commands

`pnpm install --frozen-lockfile --ignore-scripts`

No local preview server was started. Development and start scripts bind to localhost when deliberately invoked.

`pnpm run lint`, `pnpm run typecheck`, `pnpm run build`

## Review before publication

Only the business names supplied through repository URLs are confirmed. Service categories are proposals and are explicitly disclosed on the page. Stock photos are inspiration, not photographs of completed client work. See IMAGE_CREDITS.md for sources and license. No invented testimonials, licenses, metrics, pricing, phone numbers, addresses, offers or customer claims.

The form uses browser validation and local React state. It sends and stores nothing. No analytics, contact integration or external image/font services. Confirm approved services, imagery and contact details before adding a real submission integration or publishing.

Navigation, mobile menu, keyboard focus, skip link, reduced-motion preference, FAQ disclosures, labelled form inputs and live submission feedback are included.

General educational references: https://imiweb.org/stucco-restoration/ and https://www.cement.org/cement-concrete/applications-of-cement/ (repair considerations and finish textures).

## Verification status
Completed on 2026-10-11 with Node 24.15.0 and pnpm 10.18.1:

- Offline installation succeeded: all 350 packages reused, zero downloads, with integrity verification and install scripts disabled.
- Lint passed with zero errors and zero warnings after naming the existing PostCSS configuration export.
- Strict TypeScript check passed.
- Production build passed and prerendered the home page and icon.
- Review of the 12 prospective source, config, and lockfile files found no common credential-pattern matches or environment files.
- The stucco theme and local-only form validation are present; source contains no invalid control or replacement characters.

The dependency manifests matched Tampa's exactly, allowing reuse of its generated pnpm lockfile without changing declared dependencies. The same ESLint 9.39.3 support warning recorded for Tampa applies to this toolchain.

Browser interaction and visual checks remain pending. Business services, availability, imagery, and contact details still require confirmation. No local preview server, real enquiry submission, or deployment was performed. Git delivery was subsequently authorized separately.

The production build added standard allowJs and development-type include settings while retaining strict TypeScript. Framework-generated next-env.d.ts is ignored as recommended by Next.js: https://nextjs.org/docs/app/api-reference/config/typescript .

## Photography update — 2026-10-12

Hero and all three service illustrations replaced with licensed stock photography. Sources, license, optimization, and usage limits are documented in [IMAGE_CREDITS.md](IMAGE_CREDITS.md). Existing marketing copy, navigation, FAQs, and local-only enquiry behavior are preserved.

Photography update: lint, strict typecheck, and production build passed. Original photos were inspected; live browser checks remain pending.

## Estimate and callback refinement — 2026-10-12

Estimate-first navigation and hero CTAs, service-specific project prefill, repeated estimate actions, and a short three-field form (name, email or callback number, optional project details). Inline SVG replaces arrow and decorative star glyphs. Mobile actions and inputs have larger targets and 16px input text.

No verified business phone exists in the project sources, so no invented number or direct-call link is displayed. Request a callback opens the phone-contact variant of the same local-only proof-of-concept form. No backend or integration is required for this demo.

Lint, strict typecheck, and production build passed. Built HTML confirms two inputs plus one optional textarea, visible estimate/callback actions, and no form backend action. Licensed assets and credits are unchanged. Live browser interaction checks were not run; no local server or manual deployment was started.
