# Race Administration Forms

Word forms and an event package for race management, using Notice to Competitors as the visual reference.

The repository contains substantial prior conversion work. This pass organizes those files, adds US Sailing originals, and records remaining checks. Document contents are unchanged; the package has not yet been verified in desktop Word.

## Contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Files](#files)
- [Design notes](#design-notes)
- [License](#license)
- [Maintainer](#maintainer)
- [History](#history)

## Requirements

- Microsoft Word for creating event copies and checking content controls, pagination, and printing.
- Avenir for the intended appearance. The original readme reports Calibri as the fallback; check layout if Avenir is unavailable.

## Usage

1. In Word, create a new document from [the event template](packages/Race-Administration-Event-Package.dotx), or open [the blank package](packages/Race-Administration-Event-Package.docx).
2. Enter the Event name on the first page. The package contains mapped Event controls intended to repeat that value throughout.
3. Save the event copy as `.docx`. Check page breaks and print only the needed pages.

For a single form, use a blank document in [forms](forms/) or create a document from a template in [templates](templates/).

Event branding is intended to be a title and at most two graphics. A repeatable graphic-replacement workflow remains unverified; see [the review](docs/review.md).

## Files

| Folder | Contents |
| --- | --- |
| [forms](forms/) | 18 individual blank Word documents |
| [templates](templates/) | Four form templates; original Office-folder copies retained under `office-copies/` |
| [packages](packages/) | Existing event package, in `.dotx` and `.docx` formats |
| [references/us-sailing](references/us-sailing/) | 20 downloaded originals, with source URLs and checksums |
| [references/existing](references/existing/) | Existing wind-log instructions; provenance unconfirmed |
| [docs](docs/) | Review, original readme, and file-move record |
| [archive](archive/) | Original ZIP, duplicate root package, and hearing templates retained outside the race-management working set |

## Design notes

- [Notice to Competitors](templates/Notice-To-Competitors-Form.dotx) is the chosen visual reference.
- Keep this as a small document collection. No package builder or configuration system is introduced.
- Preserve the inherited forms, including the Protest Worksheet already embedded in the package. Hearing Decision templates are archived; no judges package is being developed.
- [US Sailing source page](https://www.ussailing.org/competition/rules-officiating/race-officers/materials-for-race-officers/forms-diagrams-equipment/) supplies the reference downloads. [The source notes](references/us-sailing/README.md) explain coverage.
- The original ZIP is an inherited snapshot, not a rebuilt release. Use the organized folders for current work.

## License

No repository license has been declared. US Sailing reference material retains its original ownership and notices; downloading it does not establish redistribution permission.

## Maintainer

Paul Leonard <paul.e.leonard@gmail.com>

This project is maintained primarily for my own use. Bug reports are welcome, but I am not currently accepting code contributions.

## History

### 2026-10-31

- Organized existing files without changing document contents.
- Downloaded 20 US Sailing source references and recorded provenance.
- Added a review of existing work and remaining checks.
