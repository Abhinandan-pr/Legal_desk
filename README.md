# LegalDesk MVP

A responsive, browser-based prototype for preparing and managing first drafts of three agreement types:

- Residential Rent Agreement
- Mutual Non-Disclosure Agreement
- Service Agreement

## Run locally

From this folder, start a local static server:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000> in a browser. No package installation or build step is required.

## Included

- Template catalogue with search and category filters
- Guided, required-field forms and basic date / amount checks
- Optional clause selection with plain-language explanations
- Editable generated preview
- Save, reopen, duplicate and delete drafts
- Editable Word-compatible `.doc` download and browser print-to-PDF
- Draft and legal-review limitations shown in the interface

Drafts are stored in the current browser's local storage. They are not synced, backed up, encrypted by this application, or protected by user accounts. Avoid entering sensitive personal information on shared devices.

## Not connected yet

This prototype has no server, accounts, email verification, database, cloud document storage, payments, admin template editor, advocate review workflow, or legal-content approval pipeline. The included templates are generic prototype language and have not been reviewed by an advocate. The generated drafts are not legal advice and are not guaranteed to be valid or suitable for any jurisdiction.
