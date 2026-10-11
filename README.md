# Largo Stucco website demo

An isolated, responsive website concept built with Next.js App Router, TypeScript, React, and Tailwind CSS. The warm stucco design uses original CSS illustrations and a simple project-enquiry path.

## Commands

`pnpm install --frozen-lockfile --ignore-scripts`

No local preview server was started. Development and start scripts bind to localhost when deliberately invoked.

`pnpm run lint`, `pnpm run typecheck`, `pnpm run build`

## Review before publication

Only the business names supplied through repository URLs are confirmed. Service categories are proposals and are explicitly disclosed on the page. Original CSS illustrations are concepts, not project photographs. No invented testimonials, licenses, metrics, pricing, phone numbers, addresses, offers or customer claims.

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
