# De Rueda Construction — staging name

This repository tests the requested name `de-rueda-construction-lgtm.github.io`.

It is **not** the live website. The live public site remains:

https://marjoncompany-lgtm.github.io/

That user-site repository was not renamed and was not overwritten by this staging copy.

## What the name does and does not do

The GitHub account is `marjoncompany-lgtm`. Its user-site hostname is `marjoncompany-lgtm.github.io`. Creating a repository whose name ends in `.github.io` does **not** make `https://de-rueda-construction-lgtm.github.io/` exist.

If GitHub Pages is later enabled for this repository from the `main` branch at `/`, the project-site address would be:

https://marjoncompany-lgtm.github.io/de-rueda-construction-lgtm.github.io/

Pages was not switched on from this commit. Do not add a CNAME or change DNS until the company confirms the host.

Links in these pages are relative so they still work under a project-site path.

## What this staging site is not

- It is not the staff record system.
- It does not store inquiries in the browser. A success message is not shown, because nothing here is written to the company record.
- It does not include the old field book. Device-local payroll estimates are not official.
- It does not replace the signed Android packages. Keep the current packages until a new release is signed, hash-checked and tested on a phone.

## Source of truth

The company record application (authentication, database, roles) is separate from this static staging repository and from the current public Pages site. Do not edit the two public trees as if they were the same files.
