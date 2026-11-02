# Before you install an AI coding extension (1 page)

AI coding tools can read your files and run commands, so an extension you install gets a lot of trust. This is a checklist, not a claim about any one product. Most of the risk sits with look-alike and third-party extensions, so check before you install.

## 1. Is it the real one?
- [ ] Start from the vendor's own docs or site and follow their link to the store page. Don't search the store and click the first result.
- [ ] Publisher name matches the vendor and shows as verified. Look-alikes copy names and logos.
- [ ] Check spelling of the extension ID and the publisher carefully.

## 2. Does it look established?
- [ ] Install count and age make sense. A brand-new listing with few installs is a flag.
- [ ] Reviews are specific and varied, not a pile of one-line five-stars.
- [ ] A public source repo or changelog exists, and recent updates match the version shown.

## 3. What can it do?
- [ ] Read the permissions or capabilities list. Does a "formatter" really need network and terminal access?
- [ ] Does it say where your code and prompts are sent, and what is stored?
- [ ] Can you turn off telemetry? Does the vendor publish a data policy?

## 4. Protect yourself anyway
- [ ] Try new extensions in a throwaway project or profile first, not your main repo.
- [ ] Keep secrets out of reach: no `.env` in the project folder you're testing, and deny read access to secret files in settings.
- [ ] Never paste keys, tokens or customer data into a prompt.
- [ ] Use a separate low-privilege token for anything the tool needs, and revoke it when you're done.
- [ ] Commit before you let it edit files, so you can see exactly what changed.

## 5. After installing
- [ ] Watch what it does for a day: new network connections, unexpected files, extra processes.
- [ ] Turn on auto-update only for sources you trust; review what changed in big updates.
- [ ] Remove it if you stop using it.

If anything looks off, uninstall, rotate any keys it could have seen, and report the listing to the store.
