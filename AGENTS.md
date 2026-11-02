# Leapla Docs: before you touch anything

This repository is the user documentation of Leapla (docs.leapla.co), built with Mintlify (theme "maple", like docs.macro.com), chosen by Seppe on 2 November 2026. The app itself lives in `seprey/leapla`. Seppe, the owner, can not read code: talk to him in Dutch, short and plain.

## Rules

- **This repository is public.** Only text for users goes here: never internal notes, plans, code paths, keys, customer data or anything from `docs/` of `seprey/leapla`.
- **Everything on `main` is published by Mintlify at once.** Work on a branch; `main` only with Seppe's yes.
- **A new or changed feature of the app updates its page here** (agreed with Seppe on 2 November 2026). Describe only what exists; what is planned is marked **Binnenkort** in a `<Warning>` or `<Note>`.
- Before a commit: `npx mint@4.2.1063 validate` and `npx mint@4.2.1063 broken-links`, both clean. Preview: `npx mint@4.2.1063 dev` (http://localhost:3000).

## Writing

- Every page exists in Dutch and in English, with the same content (agreed with Seppe on 2 November 2026). English is the default and lives at the root (`features/calendar.mdx` is `/features/calendar`); Dutch lives under `nl/` with the same file name (`/nl/features/calendar`). Seppe chose English as the default on 2 November 2026. The language switcher only finds the other language when both files have the same name.
- Addresses (file and folder names) are always English, also for the Dutch pages. A page that moves keeps its old address working through `redirects` in `docs.json`.
- Dutch: informal "je". English: plain, "you". Short sentences, one idea per sentence. Button names are the ones the app shows in that language.
- Bold for what is on the screen: klik op **Instellingen**.
- Every page has `title`, `description` and a Lucide `icon` in its front matter.
- The order of the menu is in `docs.json`, under `navigation.languages`: `[0]` is English, `[1]` Dutch. Change both.

## Terms

- **Wereld**: Persoonlijk, a company, or a shared workspace. **Gedeelde werkruimte**, not "space". **Apla** is the assistant. **Persoonlijk Plus** is the paid personal plan.
