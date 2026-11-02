# Leapla Docs: before you touch anything

This repository is the user documentation of Leapla (docs.leapla.co), built with Mintlify (theme "maple", like docs.macro.com), chosen by Seppe on 2 November 2026. The app itself lives in `seprey/leapla`. Seppe, the owner, can not read code: talk to him in Dutch, short and plain.

## Rules

- **This repository is public.** Only text for users goes here: never internal notes, plans, code paths, keys, customer data or anything from `docs/` of `seprey/leapla`.
- **Everything on `main` is published by Mintlify at once.** Work on a branch; `main` only with Seppe's yes.
- **A new or changed feature of the app updates its page here** (agreed with Seppe on 2 November 2026). Describe only what exists; what is planned is marked **Binnenkort** in a `<Warning>` or `<Note>`.
- Before a commit: `npx mint@4.2.1063 validate` and `npx mint@4.2.1063 broken-links`, both clean. Preview: `npx mint@4.2.1063 dev` (http://localhost:3000).

## Writing

- Dutch, informal "je". Short sentences, one idea per sentence.
- Bold for what is on the screen: klik op **Instellingen**.
- Every page has `title`, `description` and a Lucide `icon` in its front matter.
- The order of the menu is in `docs.json`, under `navigation.languages[0].groups`.

## Terms

- **Wereld**: Persoonlijk, a company, or a shared workspace. **Gedeelde werkruimte**, not "space". **Apla** is the assistant. **Persoonlijk Plus** is the paid personal plan.
