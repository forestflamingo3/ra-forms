# Existing work and remaining checks

Substantial conversion work is present. The repository contains 18 individual Word documents, four custom form templates, and an event package with mapped Event fields. This confirms that deliverables exist; it does not establish who created them or that every conversion is correct.

## Evidence

- The package contains 160 content controls and 45 XML data bindings. Its contents lists 18 forms and references.
- Notice to Competitors has nine content controls, one data binding, and explicit Avenir font references. It is the selected visual reference.
- Each individual working document contains mapped Event controls. The custom Notice, Protest Worksheet, Scoring Review, and Signal Boat forms have additional editable controls.
- The inherited [readme](original-readme.txt) describes a 45-page package, paper forms converted to Word tables, and retained rotation images. Page count, print layout, font fallback, and Word behavior remain unverified in desktop Word.
- Four Office-folder templates are byte-identical to their counterparts in `templates/`; the root package copy is byte-identical to `packages/Race-Administration-Event-Package.dotx`. Copies are retained in their documented locations.

## Source coverage

| US Sailing original | Existing working document |
| --- | --- |
| `ProtestTime.xls` | `forms/ProtestTime.docx` |
| `RCactions.xls` | `forms/RCactions.docx` |
| `RCLog1.xls` | `forms/RCLog1.docx` |
| `RCMarkRound.xls` | `forms/RCMarkRound.docx` |
| `RCWindLog.xls` | `forms/RCWindLog.docx` |
| `RRS26Timer.xls` | `forms/RRS26Timer.docx` |
| `ScoringReviewRequest.xls` / `.pdf` | `forms/ScoringReviewRequest-US-Sailing.docx` |
| `trap_60_reach.xls` | `forms/trap_60_reach.docx` |
| `trap_70_reach.xls` | `forms/trap_70_reach.docx` |
| `wl-courses.xls` | `forms/wl-courses.docx` |
| `scrpnlty.pdf` | `forms/scrpnlty.docx` |
| `Visio-Scoring_Form.pdf` | `forms/Visio-Scoring_Form.docx` |
| `Round_Robin_Rotations.pdf` | `forms/Round_Robin_Rotations.docx` |
| `Fleet_Race_Rotations.doc` / `.pdf` | `forms/Fleet_Race_Rotations.docx` |
| `Signal-Boat-Summary-Report.doc` | `forms/Signal-Boat-Summary-Form.docx` (custom replacement, per inherited readme) |
| `Cox-Sprague_Scoring_Sys.pdf` | No converted counterpart found |
| `RMC_WORK_SHEET.doc` / `MC_WORK_SHEET.pdf` | No converted counterpart found |

Mappings follow filenames and the inherited readme. Detailed cell-by-cell or text comparison has not been completed. The supplied page does not identify a direct original for the custom Notice to Competitors, custom Scoring Review, or Protest Worksheet templates.

## Remaining work

1. **Check appearance in Word.** Compare each form with Notice to Competitors: typography, headers, graphics, field treatment, margins, and paper writing spaces. No visual sign-off is claimed from XML inspection.
2. **Verify event branding.** Test that editing Event once updates every intended location. Confirm whether Event is sufficient as the title, then establish how to replace at most two graphics. No dedicated title/graphic branding controls were identified among the package's named controls.
3. **Check printing.** Verify the inherited 45-page claim, contents page numbers, landscape tables, rotation images, and the wind log's one-page layout.
4. **Decide on the two uncovered source forms.** Cox-Sprague and the five-minute RC worksheet are now preserved as originals. Their absence is a coverage gap only if the intended library includes every race-management form on the source page.
5. **Review legacy content before event use.** The package retains source wording, including a 720-degree penalty reference and older protest/arbitration text. No current-rules review was performed in this organization pass.
6. **Confirm provenance where missing.** The origins of custom templates and `references/existing/how2windlog.docx` are not independently established. Clarify licensing before distribution.
7. **Refresh the ZIP after future document changes.** The archived ZIP is preserved exactly as received and does not reflect the new folder layout.

## Scope of this pass

All 34 inherited files were moved without byte changes. [moved-files.json](moved-files.json) records original paths, current paths, and SHA-256 hashes. The two hearing templates are archived, and the inherited Protest Worksheet remains in the forms and package. No form formatting, package contents, or branding behavior was changed.
