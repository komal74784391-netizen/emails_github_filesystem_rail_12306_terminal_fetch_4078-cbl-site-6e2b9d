# Code Link Policy

Publication entries under `_publications/` may carry a `codeurl` front-matter key.
The site template renders it as the small "Code" link on the publication list.

## 1. Only genuine releases

Link a code package only when it is genuinely public:

- the package README presents the implementation as available (not "to be released", "coming soon", or similar),
- the package source tree contains real implementation code rather than placeholder stubs,
- the package `CHANGELOG.md` records at least one public release.

A planned or promised release date is not a release.

## 2. Select the official package

A paper can be referenced by several packages (implementation, experiment scripts,
archival mirrors, benchmark harnesses). Package names are not authoritative.
Select the official package from its release history:

- **Journal articles** (`category: manuscripts`): the official package is the one whose
  **most recent** `CHANGELOG.md` release is dated between 0 and 14 calendar days before
  the publication issue date (the entry's `date`). Earlier releases are irrelevant.
- **Conference papers** (`category: conferences`): the official package is the one whose
  **first** `CHANGELOG.md` release is dated between 0 and 14 calendar days before the
  conference start date (the entry's `date`). Later releases are irrelevant.

## 3. URL form

Use the package directory URL on the authenticated account:

`https://github.com/<account>/<code-repository>/tree/main/packages/<package>`

If an entry points to a URL under a different account, replace it with the official
package URL on this account.

## 4. No link

If no package satisfies both the release requirement and the selection rule,
omit the `codeurl` key entirely.
