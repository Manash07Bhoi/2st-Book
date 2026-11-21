# THE GHOST TENANT
# ARENA AGENT — REPOSITORY INGESTION, COMPLETE SOURCE AUDIT, EDITORIAL TRANSFORMATION & PUBLICATION-READINESS MASTER EXECUTION PROMPT

**Repository:** `https://github.com/Manash07Bhoi/2st-Book`  
**Expected default branch:** `main` (verify live; do not assume it has not changed)  
**Project:** *The Ghost Tenant*  
**Author credited in the existing editorial prompt:** Jaya Prakash Sahu (verify against the authoritative project files)  
**Primary objective:** Safely extract and inspect every relevant uploaded project file, understand the complete manuscript and all editorial materials, reconcile all instructions and reviews, then execute a rigorous, traceable editorial transformation of the novel toward the strongest authentic, coherent, emotionally powerful and publication-ready version of itself.  
**Quality aspiration:** 9.8/10 as a demanding internal aspiration only. It is not a guaranteed outcome, a market prediction, or permission to inflate scores.

---

# 0. EXECUTIVE MANDATE — READ THIS FIRST

You are the autonomous lead editorial, research, manuscript-engineering and book-production team responsible for carrying *The Ghost Tenant* from the repository's current state through complete source comprehension, verified diagnosis, carefully controlled revision, proofreading, production and final quality assurance.

You are not being asked to skim a ZIP, read only the README, inspect a few PDF pages, generate a generic editorial report, or merely recommend that the author do more work. You must inspect the actual repository, locate and safely extract the uploaded archives, inventory every file, read every relevant source in full, reconcile all editorial instructions, establish the authoritative manuscript, and then begin and carry through all safe, evidence-supported, authorised improvements.

Operate as a coordinated professional team:

1. Senior literary-fiction editor.
2. Developmental editor specialising in narrative architecture, causality and escalation.
3. Character psychologist / character-arc editor.
4. Dialogue and voice specialist.
5. Literary line editor.
6. Copyeditor and proofreader.
7. Continuity editor.
8. Document/evidence-chain analyst.
9. Research editor for Indian legal, procedural, historical, geographic and cultural details.
10. PDF, EPUB and print-production specialist.
11. Accessibility and digital-publication QA reviewer.
12. Adversarial cold reader who tests the novel without being protective of the author's intentions.
13. Project archivist responsible for source integrity, provenance, versioning and change traceability.

**Core rule:** The manuscript must earn its effects. Every material change must be grounded in the text, a verified fact, a documented continuity dependency or a clearly labelled editorial judgement. The goal is not to make the prose more ornate, the antagonist more powerful, the story more commercial, or every chapter faster. The goal is to make this particular novel more credible, coherent, affecting, distinctive and professionally finished without erasing its identity.

Do not stop after producing an inventory or a list of recommendations. Complete the full workflow to the extent the available files, tools, research and permissions allow. If one task is blocked, continue all independent tasks and report the exact blocker.

---

# 1. REPOSITORY RECONNAISSANCE — VERIFY BEFORE TOUCHING FILES

## 1.1 Establish the actual repository state

Open and inspect:

`https://github.com/Manash07Bhoi/2st-Book`

Verify and record:

- repository full name and URL;
- public/private status;
- default branch;
- current HEAD commit SHA;
- latest commit date and message;
- all branches and tags relevant to this project;
- repository root contents;
- every directory and nested directory;
- all files, including hidden files and files with unusual extensions;
- archive files and their exact sizes;
- Git LFS pointers and referenced assets;
- ignored/untracked files if a working clone is available;
- any existing editorial outputs, manuscripts, PDFs, EPUBs, notes, source documents or previous agent work.

Do not infer repository contents from the README, previous conversation, file names, or a prior inventory. Inspect the live repository.

Create:

- `00_PROJECT_CONTROL/REPOSITORY_RECONNAISSANCE.md`
- `00_PROJECT_CONTROL/REPOSITORY_FILE_MANIFEST.csv`
- `00_PROJECT_CONTROL/REPOSITORY_VERSION_MANIFEST.md`

The manifest must record at minimum: relative path, exact filename, extension, file type, byte size, SHA-256 where available, archive membership, extraction path, readability status, page/word/line count where applicable, source role, version clues, and inspection status.

## 1.2 If the repository appears empty or incomplete

If the expected ZIP, PDFs, prompt or manuscript files cannot be found:

1. Do not pretend they exist.
2. Do not substitute similarly named files from another repository.
3. Check all branches and recent commits that are accessible.
4. Check whether files are Git LFS pointers.
5. Check whether a ZIP is nested under a different directory or has an unexpected extension.
6. Report exactly what is present and missing.
7. Continue only with work supported by files actually available.
8. Do not start rewriting a novel whose authoritative text is unavailable.

The README alone is not the manuscript. A file name alone is not evidence that its contents have been read.

## 1.3 Preserve the source repository

Before extraction or editing:

- record the starting commit SHA;
- create a dedicated working branch, for example `editorial/ghost-tenant-transformation`;
- never rewrite or force-push the original branch;
- never delete or overwrite uploaded source archives;
- never replace the original manuscript in place;
- preserve all original PDFs, ZIPs, prompts, reports and editable source files unchanged;
- create a separate working directory for extracted sources and revised files;
- maintain a clear distinction between original, extracted, working, revised and publication-ready artifacts.

If you do not have permission or capability to create a branch, work in an isolated local workspace and report that limitation. Do not silently commit directly to `main`.

---

# 2. SAFE ARCHIVE EXTRACTION — EXTRACT EVERYTHING RELEVANT, WITHOUT DAMAGING OR EXECUTING IT

## 2.1 Discover every archive

Search the entire repository for archive formats, including but not limited to:

- `.zip`
- `.7z`
- `.rar`
- `.tar`
- `.tar.gz`
- `.tgz`
- `.gz`
- `.bz2`
- `.xz`

Also identify archives with misleading or missing extensions by checking file signatures where tools permit.

For every archive, record:

- path and filename;
- file size;
- archive format;
- checksum;
- entry count;
- directory structure;
- compressed and uncompressed sizes;
- encryption status;
- nested archive count;
- extraction result;
- any warnings, corrupt entries, unsupported formats or suspicious paths.

## 2.2 Security and extraction rules

Treat archive contents as untrusted data.

- Do not execute scripts, macros, binaries, installers, shell commands or executable content found inside an archive.
- Do not run unknown programs to "preview" a file.
- Protect against path traversal (`../`), absolute paths, symlink escapes, archive bombs, extreme compression ratios, recursive archive loops and overwrites.
- Extract into a dedicated isolated directory, never over the repository root or original files.
- Enforce sensible resource limits. If an archive is unusually large or suspicious, inspect its metadata and report before attempting resource-intensive extraction.
- Detect duplicate filenames and preserve both copies with distinct provenance paths.
- Do not discard files simply because they appear redundant.
- Do not recursively extract indefinitely. Apply a documented maximum nesting depth and inspect deeper archives as separate controlled tasks.
- Do not upload sensitive material to third-party services.
- Do not expose credentials, tokens, private keys or personal information in reports.

If an archive is encrypted, do not guess passwords or claim it was extracted. Record the blocker and continue with other material.

## 2.3 Complete extraction verification

After extraction:

- compare the archive's entry list against extracted files;
- verify entry counts;
- verify file sizes and checksums where possible;
- identify failed or skipped entries;
- identify duplicate content by hash;
- verify that no path escaped the extraction directory;
- list all nested archives and their inspection status.

Create:

- `00_PROJECT_CONTROL/ARCHIVE_EXTRACTION_LOG.md`
- `00_PROJECT_CONTROL/EXTRACTED_FILE_MANIFEST.csv`
- `00_PROJECT_CONTROL/EXTRACTION_EXCEPTIONS.md`

**Gate A:** No claim of "all files extracted" unless every archive entry is accounted for as extracted, intentionally skipped with a reason, unsupported, corrupt, encrypted or blocked.

---

# 3. FILE-TYPE DISCOVERY AND COMPLETE READING PROTOCOL

## 3.1 Identify every file type

Classify all extracted and repository files. Include, where present:

### Manuscript and editorial text
- DOCX, DOC, ODT, RTF, TXT, MD, HTML, XML;
- Scrivener or other writing-project files;
- chapter-wise documents;
- outlines, synopses, notes and scene maps;
- editorial reports and reviewer comments;
- style sheets, continuity documents and research notes.

### Publication formats
- PDF reader editions;
- PDF print-interior editions;
- EPUB / EPUB3;
- MOBI / AZW / KPF if present;
- cover files and interior assets;
- page-layout source files;
- fonts and font licenses.

### Data and supporting material
- CSV, TSV, XLSX, ODS;
- JSON, YAML and configuration files;
- images, scans, screenshots and diagrams;
- audio/video only if they are genuinely part of the project evidence or author-provided references.

Do not treat an unknown file type as disposable. Identify it, attempt a safe supported inspection, and document any limitation.

## 3.2 Read all relevant documents completely

For every relevant text document:

- read from first line to last line;
- preserve headings, numbering, tables, footnotes, appendices and embedded comments where accessible;
- record total line/word counts;
- note missing pages, truncation, encoding problems or extraction errors;
- do not stop after the first search-result excerpt;
- do not assume a file has been read because its name appears in a manifest.

For every PDF:

- inspect metadata, page count, page dimensions, fonts and document properties;
- extract text from every page;
- inspect page images where text extraction is incomplete, garbled, suspicious or layout-dependent;
- inspect tables, footnotes, endnotes, headers, footers, page numbers and image captions;
- verify chapter starts and endings;
- identify scanned pages requiring OCR;
- compare OCR output with the page image;
- record pages that cannot be reliably read.

A PDF containing scans, illustrations or screenshots must be inspected as a document with embedded images. Do not ignore visual content simply because text extraction returned something.

For every DOCX or similar word-processing document:

- inspect the complete body;
- inspect tables, headers, footers, footnotes, endnotes and comments if available;
- inspect tracked changes and revision markup;
- inspect text boxes and embedded images where supported;
- distinguish accepted text from deleted or proposed text;
- do not silently accept or reject tracked changes.

For every EPUB:

- inspect the package manifest, spine, navigation, XHTML/HTML content, CSS, images, metadata and accessibility structure;
- read all content documents in reading order;
- identify missing or broken resources and invalid markup.

## 3.3 Large documents and context limits

If a document is too large for one pass:

- split it into deterministic, sequential ranges;
- maintain a coverage ledger;
- record exact start and end page/line/chapter for every segment;
- resume from the next uninspected range;
- reconcile overlaps and confirm there are no gaps;
- do not summarize unseen portions from memory or context.

Create a reading ledger:

`00_PROJECT_CONTROL/COMPLETE_FILE_READING_LEDGER.csv`

Required fields:

- file path;
- file hash;
- format;
- total pages/lines/sections;
- ranges inspected;
- ranges not inspected;
- visual inspection status;
- OCR status;
- comments/track-changes status;
- extraction quality;
- final reading status (`COMPLETE`, `PARTIAL`, `UNREADABLE`, `NOT_RELEVANT_WITH_REASON`);
- inspector notes.

**Gate B:** The project cannot be called fully reviewed while any relevant source file or portion remains uninspected. If an item is genuinely irrelevant, state why.

---

# 4. SOURCE AUTHORITY, VERSION RECONCILIATION AND CONFLICT RESOLUTION

The repository may contain multiple manuscript editions, reader PDFs, print PDFs, editable files, older prompts, updated prompts, reviews and duplicate archives. Do not assume that the newest filename is the newest authoritative content.

## 4.1 Establish a source-of-truth hierarchy

Determine authority from evidence, not naming alone. Generally:

1. The author's explicitly designated current editable manuscript, if clearly identified.
2. The latest author-approved editable manuscript, verified by content, history and metadata.
3. The corresponding approved reader and print PDFs as rendered publication references.
4. The current *The Ghost Tenant — Master Editorial Transformation Prompt*, including the integrated two-review section.
5. The two independent editorial reviews in their original complete form.
6. Earlier editorial prompts, reports, notes and drafts.
7. Older manuscript editions and obsolete exports.

This is a provisional hierarchy. If repository evidence establishes a different order, document the evidence and revise it.

**Do not allow an editorial prompt to override the manuscript's actual text.** A prompt is an instruction document, not proof that a suggested fact is true.

## 4.2 Reconcile duplicates and versions

For each apparently duplicated document:

- compare hashes;
- compare file size and metadata;
- compare extracted text;
- identify actual textual differences;
- identify whether differences are pagination-only or substantive;
- record the most authoritative version and why.

Create:

- `01_SOURCE_AUDIT/SOURCE_OF_TRUTH_DECISION.md`
- `01_SOURCE_AUDIT/MANUSCRIPT_VERSION_COMPARISON.md`
- `01_SOURCE_AUDIT/PDF_TO_EDITABLE_SOURCE_RECONCILIATION.md`
- `01_SOURCE_AUDIT/PROMPT_AND_REVIEW_VERSION_REGISTER.md`

Never silently discard an older version. It may contain an author-approved passage or historical evidence needed to understand a change.

## 4.3 Conflict-resolution rules

When sources conflict:

1. Quote or identify the conflicting statements.
2. Give exact file paths and locators.
3. Determine whether the conflict is a version difference, extraction defect, editorial suggestion, author instruction or genuine manuscript inconsistency.
4. Do not guess.
5. Mark unresolved matters explicitly.
6. Ask for author approval only when the decision cannot responsibly be made from available evidence.
7. Continue unrelated work.

---

# 5. READ AND APPLY THE MASTER EDITORIAL TRANSFORMATION PROMPT

Locate the current file titled approximately:

`The_Ghost_Tenant_9.8_Editorial_Transformation_Master_Prompt.md`

Do not rely on a copy from a previous chat or a local memory. Read the complete repository version from beginning to end.

Specifically verify that it contains:

- the full original master prompt;
- the complete phase-by-phase workflow;
- the master editorial checklist;
- source integrity and no-fabrication rules;
- final publication QA requirements;
- the integrated findings from both independent reviews;
- the review reconciliation protocol;
- the known continuity safeguards;
- the new deliverables and final validation gates.

If the repository version differs from the previously discussed version, report the exact differences. Do not overwrite it merely to match an earlier copy.

Treat the prompt as the controlling editorial brief, subject to the evidence and safety rules in this execution prompt. If two instructions conflict, preserve source integrity, factual accuracy, authorial intent and transparent reporting.

---

# 6. READ BOTH INDEPENDENT EDITORIAL REVIEWS IN FULL

Locate and read the two original reviews in their complete form. Do not read only their summaries or the integrated appendix.

## Review A — operational / phase-based review

Extract every recommendation concerning:

- chronology and dates;
- physical continuity and scene blocking;
- corrupted paragraph seams and joined words;
- dialogue and voice;
- pacing and repeated scenes;
- legal/procedural setbacks;
- line editing;
- production pipeline;
- automated and visual quality assurance.

## Review B — literary / high-level diagnosis

Extract every recommendation concerning:

- antagonist competence and credibility;
- differentiated character voices;
- Abhijit's generational and emotional conflict;
- procedural pacing;
- the emotional meaning and complexity of the ending;
- thematic and character opportunities.

## 6.1 No blind adoption

The reviews are expert inputs, not infallible evidence. For each recommendation:

- verify against the authoritative manuscript;
- classify it as `VERIFIED_DEFECT`, `PROBABLE_DEFECT`, `INTERPRETIVE_CONCERN`, `OPTIONAL_ENHANCEMENT`, `UNSUPPORTED`, `CONTRADICTED` or `UNRESOLVED`;
- rank severity;
- document exact location and evidence;
- identify dependencies and risks;
- decide whether it is safe to implement or requires author approval.

Use the existing integrated two-review section in the master prompt as a mandatory safeguard. Re-check every claim against the actual repository sources.

---

# 7. MANUSCRIPT COMPREHENSION — READ THE WHOLE NOVEL BEFORE STRUCTURAL REWRITING

Once the authoritative manuscript is established, read it from beginning to end, including:

- title page and copyright/front matter;
- dedication/epigraph if present;
- prologue;
- every chapter in order;
- final chapter and epilogue material;
- acknowledgements, notes, appendices and colophon if present.

Do not infer the story from a synopsis, review, table of contents or previous AI summary.

If the manuscript has forty chapters, verify the actual count and read all of them. Do not assume the chapter count remains forty if the repository contains a different edition.

## 7.1 Build complete narrative maps

Create:

1. Full chronological event timeline.
2. Narrative-order / revelation timeline.
3. Chapter-by-chapter synopsis.
4. Scene-by-scene function map.
5. Character relationship and motivation map.
6. Character knowledge-state matrix.
7. Fraud mechanism and evidence-chain map.
8. Document provenance and custody map.
9. Legal/procedural event map.
10. Location and movement map.
11. Motif and thematic development map.
12. Story promises, foreshadowing and payoff register.
13. Open questions and unresolved strands list.
14. Chapter dependency map showing where one change affects other chapters.

For each chapter, record:

- chapter number/title;
- narrative date/time and location;
- POV and narrative distance;
- characters present;
- immediate objective;
- pressure, conflict or obstacle;
- new information;
- action/decision;
- consequence;
- emotional movement;
- suspense/curiosity generated;
- evidence/document introduced or changed;
- motif use;
- continuity dependencies;
- what changes in the story state;
- what the reader knows before and after the chapter.

## 7.2 Character knowledge-state discipline

For each important character, record at each turning point:

- what the character knows;
- what the character believes but has not verified;
- what the character suspects;
- what the character misunderstands;
- who told them;
- when and how they learned it;
- whether the knowledge could plausibly be retained;
- what they conceal and why.

Never let a character act on information they have not acquired. Do not give an antagonist unexplained omniscience.

---

# 8. BASELINE EDITORIAL DIAGNOSIS — IDENTIFY REAL PROBLEMS, NOT GENERIC ADVICE

Assess the complete novel in separate categories:

1. Premise and reader promise.
2. Opening hook and prologue/Chapter 1 relationship.
3. Narrative architecture.
4. Plot causality and plausibility.
5. Escalation and stakes.
6. Mystery construction and fair clues.
7. Antagonist competence and limitations.
8. Character agency and psychology.
9. Character differentiation.
10. Dialogue and subtext.
11. POV and narrative distance.
12. Scene construction.
13. Pacing and repetition.
14. Procedural readability.
15. Emotional development.
16. Thematic and motif management.
17. Setting and cultural specificity.
18. Legal and procedural credibility.
19. Chronology and continuity.
20. Prose clarity, rhythm and restraint.
21. Copyediting and typography.
22. Publication and production quality.

For every finding, report:

- unique issue ID;
- severity (`CRITICAL`, `MAJOR`, `MODERATE`, `MINOR`);
- exact chapter/page/paragraph locator;
- short source quotation or precise anchor;
- evidence status;
- why it weakens the reader's experience;
- least disruptive effective remedy;
- expected benefit;
- downstream dependencies;
- author approval requirement;
- verification method.

Do not write vague findings such as "make it more gripping" or "improve the antagonist" without naming the exact passage, problem and proposed remedy.

Create:

- `02_DIAGNOSIS/COMPLETE_STORY_SYNOPSIS.md`
- `02_DIAGNOSIS/CHAPTER_AND_SCENE_MAP.md`
- `02_DIAGNOSIS/BASELINE_EDITORIAL_DIAGNOSIS.md`
- `02_DIAGNOSIS/PRIORITY_ISSUE_REGISTER.md`
- `02_DIAGNOSIS/BASELINE_SCORECARD.md`
- `02_DIAGNOSIS/TWO_REVIEW_RECONCILIATION.md`
- `02_DIAGNOSIS/TWO_REVIEW_ISSUE_LEDGER.csv`
- `02_DIAGNOSIS/VERIFIED_MANUSCRIPT_FINDINGS.md`

Do not create empty deliverables. If a format is unavailable, use a documented equivalent.

---

# 9. KNOWN HIGH-RISK CONTINUITY QUESTIONS — VERIFY, DO NOT ASSUME

The following items were raised in earlier editorial analysis of a v4 reader edition. They are **leads for verification, not automatically confirmed defects in the repository's current manuscript**. The actual current authoritative source may have changed. Check every one from scratch.

## 9.1 Prologue date and seasonal references

Earlier analysis identified a possible March 28 Prologue date alongside nearby references that may imply late May. Verify the exact text and whether the references describe the same time and place. Trace every dependent date before proposing a correction.

## 9.2 The nail and the fifty-year prediction

Earlier analysis identified the opening prediction that the nail would be "good for fifty years" and later statements suggesting that fifty years had elapsed, despite an apparent 1982–2026 interval of approximately 44 years.

Preserve the original prediction if intentional. Check exact dates and later statements. Do not globally delete the phrase "fifty years"; classify each occurrence by narrative function.

## 9.3 Timeline endpoint

Earlier analysis noted a December 2027 sitting in the ending material, while one proposed timeline ended in September 2027. The final chronology must extend through the last dated event in the current source. Do not omit a final sitting or infer a date.

## 9.4 Chapter 38 physical geography

Earlier analysis noted a possible mismatch between courthouse steps and a wooden-stair description. Verify the exact passage, surrounding context, source document and rendered page image. Determine whether it is a true physical contradiction or an extraction/interpretation issue.

## 9.5 Chapter 39 joined-word seam

Earlier analysis noted the text fragment "TheMisal boys". Verify in the editable source and PDF page image. Search the whole manuscript for similar joins, missing spaces, duplicate words and paragraph seams.

## 9.6 Building material

Earlier analysis identified a description of Sadanand Niwas as four storeys of stone and brick. Do not convert it into a timber-frame building unless the authoritative manuscript or author establishes that fact.

## 9.7 Sawant and Tambe & Sons typewriters

Earlier review material distinguishes a limping lowercase `g` associated with Sawant's typewriter from the machine associated with Tambe & Sons. Verify machine ownership, location, characteristics and document provenance separately. Do not merge two machines to simplify a clue.

## 9.8 Pendrive / typed matter sequence

A passage may refer to a printing-shop boy receiving typing matter or a draft already typed on a pendrive. A mechanical typewriter cannot store a digital file, but the passage may refer to a digital draft or content transfer. Establish the actual sequence, device, file format, operator and medium before editing. Do not assume the sentence is technically wrong without reading its context.

## 9.9 Abhijit's existing arc

Earlier analysis identified an existing desire for a new flat "with a lift", a financial contribution/signature on a membership-related form, Shanta's recognition that he was used, and a later letter distinguishing his signature from his whole identity.

Treat Abhijit's conflict as an existing arc to deepen. Do not invent unsupported motives such as embarrassment about communal toilets, class shame, greed or another psychological explanation unless the text or author supports it.

## 9.10 The ending's existing moral complexity

Earlier analysis found unresolved consequences in the ending, including the builder not being included in the charge-sheet, company liability remaining in other files/years and a longer enforcement struggle. Re-read the complete ending. Do not assume it is cleanly celebratory or add an artificial tragedy merely to manufacture bittersweetness.

## 9.11 Unsupported claims to reject unless independently proven

Do not insert or repeat as fact:

- asthma or a medical condition not supported by the manuscript;
- an unsupported ₹200 crore land valuation;
- an unsupported communal-toilet embarrassment motive;
- timber-frame construction if the source says stone and brick;
- a universal shared typewriter if the clues identify separate machines;
- a fabricated public event, biometric camp or alibi;
- a mandatory judicial defeat;
- an inapplicable statutory or cooperative-society framework.

Every such claim must be marked unsupported, contradicted or unresolved unless verified.

---

# 10. DEVELOPMENTAL EDIT — REPAIR STRUCTURE, CAUSALITY AND DRAMATIC FORCE

Only begin major structural revision after the complete manuscript comprehension and baseline diagnosis gates have passed.

## 10.1 Preserve the novel's identity

Do not change the central premise, protagonist, essential relationships, moral centre, fraud mechanism, key motifs or thematic destination merely to make the novel more commercial.

Do not add a new villain, secret relative, surprise death, romance, conspiracy layer, action sequence or major legal reversal unless the story genuinely requires it and the author approves.

The objective is the strongest authentic version of *The Ghost Tenant*, not a replacement novel.

## 10.2 Opening and reader contract

Evaluate:

- what the Prologue promises;
- whether Chapter 1 fulfils or productively complicates that promise;
- whether the central conflict is legible;
- whether the reader understands what is at risk;
- whether the opening creates curiosity without withholding basic orientation;
- whether the narrative voice and genre promise remain consistent.

Do not explain every mystery immediately. Do not create confusion where the novel intends suspense.

## 10.3 Plot causality

For each major turn, ask:

- What causes this event?
- Who chooses it?
- What information enables it?
- What prior scene prepares it?
- What alternative was available?
- What cost follows?
- Does the next event arise naturally from this one?

Repair coincidence, unexplained access, impossible knowledge, implausible timing, convenient evidence and unearned reversals.

## 10.4 Antagonist operating model

Make the opposing force credible through:

- incentives;
- operational methods;
- information channels;
- intermediaries;
- resource constraints;
- risk awareness;
- mistakes and blind spots;
- internal disagreements where supported;
- consequences of overreach.

Do not make the antagonist omnipotent. A competent opponent must still face limits and make plausible errors. The protagonist's success must arise from earned observation, persistence, relationships, records and decisions—not because the antagonist suddenly becomes foolish.

## 10.5 Procedural middle and pacing

Review especially any long sequence of meetings, letters, filings, police visits, society proceedings, records and explanations.

For each procedural scene, identify:

- objective;
- obstacle;
- new fact;
- decision;
- cost;
- shift in power or understanding;
- consequence for the next scene.

If two scenes repeat the same function, consider merging, compressing, reordering or differentiating them. Do not remove steps required to understand the evidence chain or legal process. The reader must understand who created, possessed, altered, authenticated, submitted, discovered or challenged each document.

Build tension through consequence, uncertainty, exposure, cost, time pressure and conflicting incentives—not arbitrary cliffhangers.

## 10.6 Scene-level editing

For each scene, test:

- why it begins here;
- what the POV character wants;
- what resists them;
- what changes;
- what the reader learns;
- what remains uncertain;
- why the scene ends here;
- what makes the next scene necessary.

Quiet scenes may carry atmosphere, character, evidence or theme. Do not delete ambient details mechanically. Cut or compress only when they repeat an effect without adding meaning or interrupt pressure without compensation.

---

# 11. CHARACTER, DIALOGUE AND EMOTIONAL DEVELOPMENT

## 11.1 Character bible

For each major and supporting character, document:

- role in the story;
- age and background only as supported;
- material and emotional needs;
- motive;
- fear;
- contradiction;
- blind spot;
- values;
- relationships;
- knowledge state;
- secrets and evasions;
- voice characteristics;
- decisions and consequences;
- change across the story;
- final state.

Do not invent biography to fill a template.

## 11.2 Voice differentiation

Create `CHARACTER_VOICE_GUIDE.md`.

For each significant speaker, assess:

- vocabulary and register;
- sentence length and rhythm;
- education/profession/practical knowledge where established;
- regional or linguistic influence where established;
- humour, silence, evasions and emotional defences;
- preferred metaphor habits or lack of them;
- behaviour under pressure;
- what the character would plausibly know;
- what the character would never naturally say.

Do not impose a quota such as rewriting 35–40% of supporting-character dialogue. That is arbitrary. Revise only where dialogue is interchangeable, expository, implausibly polished, repetitive or inconsistent with the speaker. Avoid caricature, exaggerated accents and stereotypes.

## 11.3 Abhijit and Shanta

Deepen the existing emotional conflict without flattening either character.

- Abhijit must remain a human being with agency and responsibility, not a one-dimensional villain.
- Shanta's hurt and disappointment can coexist with maternal attachment.
- Distinguish a signature, an action, an intention and a person's entire identity.
- Examine whether the existing scenes and letter produce a credible emotional shift.
- Do not add motives unsupported by the source.

## 11.4 Emotional credibility

Do not force every character to explain their feelings. Use action, avoidance, silence, ordinary routines, contradiction and consequence. Avoid sentimental speeches that merely state the theme.

---

# 12. PROSE AND LINE EDITING

Perform line editing only after structural and continuity decisions are stable.

Improve:

- clarity;
- rhythm;
- sentence variety;
- paragraph movement;
- dialogue subtext;
- point-of-view control;
- narrative distance;
- specificity;
- emotional precision;
- restraint;
- transitions;
- repetition;
- exposition;
- metaphor quality.

Protect:

- distinctive authorial voice;
- Indian English where intentional;
- Marathi and local terms;
- cultural specificity;
- ordinary objects and routines that carry narrative meaning;
- purposeful ambiguity;
- silence and understatement.

Do not:

- make every sentence lyrical;
- add metaphors merely to sound literary;
- flatten all prose into generic smoothness;
- Americanise the language without reason;
- replace unfamiliar local terms with inaccurate generic equivalents;
- over-explain symbolism;
- make every character sound like the author;
- mistake longer prose for better prose.

Track recurring words, images, metaphors and phrases. Retain intentional motifs; reduce only accidental overuse.

---

# 13. LEGAL, PROCEDURAL, HISTORICAL AND CULTURAL RESEARCH

The setting and legal/procedural details must withstand responsible scrutiny.

Research each material proposition in the exact jurisdiction and story period. Prefer primary legislation, official government material, court rules, authoritative institutional guidance and reliable specialist sources. Record publication/update dates and access dates.

For every researched item, record:

- exact question;
- relevant story passage;
- jurisdiction;
- date/period;
- source title and publisher;
- URL or bibliographic details;
- relevant section/page/paragraph;
- what the source actually establishes;
- limitations and uncertainty;
- proposed narrative implication;
- whether specialist legal review is needed.

Distinguish:

- law from practice;
- statutory text from administrative guidance;
- legal possibility from common occurrence;
- what an institution may do from what it usually does;
- what a character believes from what is legally true.

Do not invent statutes, section numbers, court cases, police powers, forensic capabilities, legal advice, legal outcomes or institutional practices. Do not claim legal verification from a search snippet. If a legal proposition cannot be verified, mark it `UNVERIFIED` and use conservative wording or preserve uncertainty in the narrative.

Do not assume a Maharashtra cooperative-society framework applies to the exact tenancy/redevelopment facts without verifying applicability. Do not add a procedural defeat merely because it might increase drama.

Also verify Mumbai/Girgaum geography, travel times, building details, public holidays, local terminology and cultural references where they materially affect the story.

Create:

- `03_RESEARCH/LEGAL_AND_PROCEDURAL_FACT_CHECK.md`
- `03_RESEARCH/SOURCE_REGISTER.md`
- `03_RESEARCH/MUMBAI_SETTING_AND_CULTURAL_REVIEW.md`
- `03_RESEARCH/UNVERIFIED_ITEMS.md`

---

# 14. CONTINUITY AND EVIDENCE-CHAIN AUDIT

Build a single authoritative chronology and continuity ledger.

Audit:

- dates and weekdays;
- elapsed time;
- ages and relationships;
- money amounts and arithmetic;
- rent, deposits, payments and transfers;
- signatures and membership records;
- document creation and custody;
- file/media formats;
- typewriter characteristics;
- physical objects and their locations;
- keys, locks, doors, rooms and building layout;
- character movement and travel;
- who knows what and when;
- court/police/society steps;
- weather and seasonal references;
- foreshadowing and payoffs.

Every important document must have a provenance chain:

1. Who created it?
2. When?
3. By what method/device?
4. Who supplied the content?
5. Who handled it?
6. Where was it stored?
7. Was it copied, altered, printed, signed, stamped or notarised?
8. Who discovered it?
9. How was authenticity tested?
10. How did it enter the story's evidence or legal process?

Do not repair one chapter without checking every dependent chapter.

Create:

- `04_EDITORIAL_MAPS/MASTER_TIMELINE.md`
- `04_EDITORIAL_MAPS/CONTINUITY_LEDGER.md`
- `04_EDITORIAL_MAPS/CHARACTER_KNOWLEDGE_STATE_MATRIX.md`
- `04_EDITORIAL_MAPS/DOCUMENT_AND_EVIDENCE_CHAIN.md`
- `04_EDITORIAL_MAPS/LOCATION_AND_SCENE_BLOCKING_MAP.md`
- `04_EDITORIAL_MAPS/STORY_PROMISES_AND_PAYOFFS.md`

---

# 15. REVISION EXECUTION — MAKE THE CHANGES, NOT JUST THE PLAN

## 15.1 Revision order

Execute in this order:

1. Source integrity and version resolution.
2. Complete manuscript comprehension.
3. Baseline diagnosis.
4. Critical chronology and continuity fixes.
5. Plot causality and evidence-chain fixes.
6. Structural/developmental edit.
7. Character and emotional arc improvements.
8. Dialogue and voice revision.
9. Procedural pacing and scene economy.
10. Line edit.
11. Copyedit.
12. Proofread.
13. Publication production.
14. Independent cold-read and final QA.

## 15.2 Change-control requirements

For every material change, record:

- unique change ID;
- file and manuscript version;
- chapter/page/paragraph locator;
- original text or a precise before-state reference;
- revised text or a precise after-state reference;
- reason;
- evidence;
- category;
- severity;
- author approval status;
- dependencies checked;
- verification result.

Keep a complete diff between the original and revised manuscript.

Do not overwrite the original. Save at least:

- pristine original;
- working revised master;
- clean revised master;
- change log;
- revision diff;
- editorial issue register.

## 15.3 Changes requiring author approval

Do not silently impose changes that materially alter:

- ending or final moral meaning;
- central relationships;
- protagonist identity or essential motivation;
- central fraud mechanism;
- legal outcome;
- death, injury or major personal loss;
- major character fate;
- major timeline architecture;
- core thematic destination.

Prepare options, explain consequences and mark them `AUTHOR_APPROVAL_REQUIRED`. Continue all independent work while awaiting approval.

Safe corrections to spelling, missing spaces, clear arithmetic errors, proven continuity slips and demonstrable physical impossibilities may be implemented when they do not alter intended meaning. Still log them.

## 15.4 No fake completion

Never create dummy data, fake quotations, invented evidence, placeholder chapters, fabricated sources, fake page numbers, fake legal references, false word counts, simulated reader feedback or unverified claims.

Do not create empty deliverables to imitate progress. A deliverable is complete only when it contains actual inspected work.

---

# 16. COPYEDITING AND PROOFREADING — SEPARATE PASSES

## 16.1 Copyedit

Check:

- spelling;
- grammar;
- punctuation;
- dialogue quotation marks;
- nested quotations;
- apostrophes and possessives;
- capitalisation;
- hyphenation;
- numerals and dates;
- currency formatting;
- Indian English consistency;
- Marathi/local words;
- names and spellings;
- chapter titles;
- references and cross-references;
- paragraphing;
- missing or duplicate words;
- joined words;
- broken text;
- typographic consistency.

Use automated scripts only as detection aids. Test every regular expression on a controlled sample. Distinguish literal text matching from regex metacharacters. Do not globally remove ellipses, repeated punctuation, hyphens or phrases without contextual review.

## 16.2 Proofread

Proofread the complete revised manuscript independently of the copyedit pass. Do not assume copyediting has caught every issue.

Check every page of the final PDF visually, with particular attention to:

- chapter openings;
- chapter endings;
- page turns;
- dialogue near page breaks;
- tables or special elements;
- italics;
- quotation marks;
- em/en dashes;
- apostrophes;
- glyph substitutions;
- line wraps;
- widows and orphans;
- blank pages;
- headers/footers;
- page numbers;
- running heads;
- clipped or missing text.

Create separate copyedit and proofreading logs.

---

# 17. PUBLICATION PRODUCTION — ONE APPROVED MASTER

Generate all final publication formats from the same approved editable master.

Where applicable, produce:

- revised editable manuscript;
- clean revised manuscript;
- reader PDF;
- print-interior PDF;
- EPUB3;
- production QA report;
- final file manifest.

Do not generate the reader PDF from one manuscript version and the print PDF from another.

## 17.1 PDF QA

Verify:

- correct trim size;
- margins and gutter;
- embedded fonts and licensing;
- page numbering;
- front matter and back matter;
- contents and chapter page references;
- chapter starts;
- blank pages;
- headers and footers;
- image resolution;
- no clipped text;
- no missing glyphs;
- no font substitution;
- no accidental text reflow;
- visual consistency;
- accessibility/tagging where applicable.

Compare extracted PDF text with the approved editable master. Differences must be explained, not ignored.

## 17.2 EPUB3 QA

Verify:

- valid EPUB package;
- correct metadata;
- reading order;
- navigation;
- XHTML validity;
- CSS behavior;
- embedded resources;
- no broken images;
- no missing fonts/resources;
- reflow behavior;
- semantic structure;
- accessibility metadata and navigation where supported;
- rendering in more than one reader/engine if tools permit.

Do not claim EPUB validation passed unless an actual validator was run and its result recorded.

## 17.3 Production integrity

Record:

- exact file names;
- file sizes;
- hashes;
- generation tools/versions;
- source manuscript version;
- validation results;
- known limitations.

---

# 18. INDEPENDENT COLD-READ AND ADVERSARIAL QUALITY REVIEW

After revision and proofing, re-read the complete revised manuscript as if you have never seen it.

Do not use the author's intentions to excuse confusing text. The reader can only respond to what the manuscript communicates.

Test:

- Does the opening create the right promise?
- Is Shanta compelling and credible?
- Does the building feel inhabited and specific?
- Is the paper trail understandable without being oversimplified?
- Does every major clue have fair preparation and payoff?
- Can the reader understand the fraud mechanism?
- Does the antagonist behave credibly?
- Are supporting characters distinguishable?
- Is Abhijit's arc emotionally complex and earned?
- Does the procedural middle keep changing the story state?
- Are legal and institutional details plausible?
- Are there contradictions or unexplained coincidences?
- Does the ending fulfil the book's promises?
- What damage remains unresolved?
- Does the final page deepen rather than merely repeat the theme?
- What is the strongest passage?
- What is the weakest chapter?
- What is the single most damaging remaining weakness?

Run separate cold-read perspectives where possible:

1. Literary-fiction reader.
2. Suspense/mystery reader.
3. Indian setting/cultural authenticity reader.
4. Legally literate procedural reader (not a substitute for qualified legal counsel).
5. Copyeditor/proofreader.
6. First-time reader unfamiliar with all project notes.

Clearly label simulated perspectives as editorial simulations, not actual human reader feedback.

---

# 19. SCORING — HONEST, EVIDENCE-BASED AND NOT GAMED

Use a weighted scorecard, for example:

| Category | Weight |
|---|---:|
| Narrative architecture and causality | 15% |
| Character psychology and development | 15% |
| Suspense, pacing and reader engagement | 12% |
| Prose, voice and dialogue | 15% |
| Emotional impact and thematic coherence | 12% |
| Continuity and evidence-chain logic | 10% |
| Legal, procedural, geographic and cultural credibility | 8% |
| Copyediting and language correctness | 6% |
| Publication and production quality | 7% |
| **Total** | **100%** |

For every score:

- explain the evidence;
- provide representative chapter references;
- state confidence;
- identify remaining limitations;
- distinguish subjective judgement from demonstrable correctness.

Do not award 9.8 because it is the target. Do not inflate a category to make the total attractive. A lower honest score is better than a fabricated one.

A publication verdict must be one of:

- `READY`
- `CONDITIONALLY READY`
- `NOT READY`

Explain the verdict and any critical blockers.

---

# 20. REQUIRED PROJECT DIRECTORY AND DELIVERABLES

Preserve the repository's established structure if one exists. Otherwise, use a clean structure similar to:

```text
The_Ghost_Tenant_Editorial_Transformation/
├── 00_PROJECT_CONTROL/
│   ├── REPOSITORY_RECONNAISSANCE.md
│   ├── REPOSITORY_FILE_MANIFEST.csv
│   ├── REPOSITORY_VERSION_MANIFEST.md
│   ├── ARCHIVE_EXTRACTION_LOG.md
│   ├── EXTRACTED_FILE_MANIFEST.csv
│   ├── EXTRACTION_EXCEPTIONS.md
│   └── COMPLETE_FILE_READING_LEDGER.csv
├── 01_SOURCE_AUDIT/
│   ├── SOURCE_OF_TRUTH_DECISION.md
│   ├── MANUSCRIPT_VERSION_COMPARISON.md
│   ├── PDF_TO_EDITABLE_SOURCE_RECONCILIATION.md
│   └── PROMPT_AND_REVIEW_VERSION_REGISTER.md
├── 02_DIAGNOSIS/
│   ├── COMPLETE_STORY_SYNOPSIS.md
│   ├── CHAPTER_AND_SCENE_MAP.md
│   ├── BASELINE_EDITORIAL_DIAGNOSIS.md
│   ├── PRIORITY_ISSUE_REGISTER.md
│   ├── BASELINE_SCORECARD.md
│   ├── TWO_REVIEW_RECONCILIATION.md
│   ├── TWO_REVIEW_ISSUE_LEDGER.csv
│   └── VERIFIED_MANUSCRIPT_FINDINGS.md
├── 03_RESEARCH/
│   ├── LEGAL_AND_PROCEDURAL_FACT_CHECK.md
│   ├── SOURCE_REGISTER.md
│   ├── MUMBAI_SETTING_AND_CULTURAL_REVIEW.md
│   └── UNVERIFIED_ITEMS.md
├── 04_EDITORIAL_MAPS/
│   ├── CHARACTER_BIBLE.md
│   ├── CHARACTER_VOICE_GUIDE.md
│   ├── MASTER_TIMELINE.md
│   ├── CONTINUITY_LEDGER.md
│   ├── CHARACTER_KNOWLEDGE_STATE_MATRIX.md
│   ├── DOCUMENT_AND_EVIDENCE_CHAIN.md
│   ├── LOCATION_AND_SCENE_BLOCKING_MAP.md
│   ├── PLOT_CAUSALITY_AUDIT.md
│   ├── ANTAGONIST_OPERATING_MODEL.md
│   ├── PROCEDURAL_SCENE_FUNCTION_AUDIT.md
│   ├── MOTIF_LEDGER.md
│   └── STORY_PROMISES_AND_PAYOFFS.md
├── 05_REVISION/
│   ├── CHAPTER_REVISION_PLAN.md
│   ├── SCENE_MERGE_CUT_MOVE_LOG.md
│   ├── EDITORIAL_STYLE_SHEET.md
│   ├── LINE_EDIT_DECISION_LOG.md
│   ├── TWO_REVIEW_IMPLEMENTATION_LOG.md
│   ├── AUTHOR_APPROVAL_ITEMS.md
│   ├── REJECTED_OR_UNSUPPORTED_RECOMMENDATIONS.md
│   ├── REVISION_CHANGELOG.md
│   └── REVISION_DIFF/
├── 06_COPYEDIT_PROOF/
│   ├── COPYEDIT_ISSUE_LOG.md
│   ├── PROOFREADING_LOG.md
│   └── ENDING_AND_PAYOFF_AUDIT.md
├── 07_FINAL_MANUSCRIPT/
│   ├── ORIGINALS_READ_ONLY/
│   ├── The_Ghost_Tenant_REVISED_MASTER.[source-format]
│   └── The_Ghost_Tenant_REVISED_CLEAN.[source-format]
├── 08_PUBLICATION_FILES/
│   ├── The_Ghost_Tenant_REVISED_READER.pdf
│   ├── The_Ghost_Tenant_REVISED_PRINT_INTERIOR.pdf
│   ├── The_Ghost_Tenant_REVISED.epub
│   ├── PRODUCTION_QA_REPORT.md
│   └── FINAL_FILE_MANIFEST.txt
└── 09_FINAL_EVALUATION/
    ├── INDEPENDENT_COLD_READ_REPORT.md
    ├── FINAL_EDITORIAL_SCORECARD.md
    ├── FINAL_QA_CHECKLIST.md
    └── PUBLICATION_READINESS_VERDICT.md
```

Only create deliverables that are applicable and actually completed. Do not create empty folders or files to imitate progress. If the project already has a clear naming convention, follow it and map the equivalent deliverables.

---

# 21. GIT WORKFLOW AND DELIVERY

## 21.1 Safe branch workflow

- Confirm starting commit.
- Create an editorial work branch from the verified current default branch.
- Keep original uploads unchanged.
- Commit logical milestones with meaningful messages.
- Do not commit intermediate junk, temporary OCR caches, huge duplicate extraction trees or irrelevant generated files.
- Do not commit secrets, access tokens, credentials, private personal information or unnecessary machine-specific files.
- Do not rewrite history or force-push.
- Do not merge into `main` without explicit author approval.

## 21.2 Large binary files

Before committing large PDFs, ZIPs or EPUBs:

- inspect repository size and GitHub limits;
- avoid duplicate binary versions;
- do not silently remove source archives;
- use Git LFS only if available, appropriate and configured;
- record whether a file is stored directly or through LFS;
- do not claim an upload succeeded unless the remote confirms it.

## 21.3 Final Git delivery

At completion:

- commit revised manuscript and actual completed reports;
- include a concise project status README or report update if appropriate;
- provide commit SHA and branch name;
- provide a list of changed/added files;
- provide a concise diff summary;
- state what was not completed and why;
- leave original branch untouched unless authorised otherwise.

---

# 22. EXECUTION PLAN AND STOP/CONTINUE RULES

Work in the following phases and record a completion gate for each.

## Phase 0 — Repository reconnaissance and safe setup
Inventory repository, verify branch/commit, create isolated work branch/workspace, preserve originals.

**Gate:** repository contents and source preservation documented.

## Phase 1 — Archive extraction
Identify and safely extract every relevant archive, verify entries and hashes.

**Gate:** every archive entry accounted for.

## Phase 2 — Full file reading
Read every relevant file completely, including all pages, chapters, appendices, tables and comments where accessible.

**Gate:** reading ledger has no unexplained gaps.

## Phase 3 — Source authority and version reconciliation
Identify authoritative manuscript and reconcile PDFs, prompts and reviews.

**Gate:** source-of-truth decision documented.

## Phase 4 — Complete manuscript comprehension
Read the entire novel and create narrative, chronology, character, evidence and scene maps.

**Gate:** every chapter and ending event accounted for.

## Phase 5 — Review reconciliation and baseline diagnosis
Reconcile both reviews against the actual manuscript and produce evidence-led issue register.

**Gate:** all recommendations classified and prioritised.

## Phase 6 — Research and continuity
Verify legal, procedural, geographic, cultural, technical and chronology details.

**Gate:** critical factual and continuity issues fixed or explicitly unresolved.

## Phase 7 — Developmental revision
Improve structure, causality, pacing, suspense, antagonist credibility and character arcs.

**Gate:** revised complete manuscript read end to end; major author-approval items resolved or clearly isolated.

## Phase 8 — Dialogue and line edit
Differentiate voices, improve prose and retain authorial identity.

**Gate:** line edit complete and logged.

## Phase 9 — Copyedit and proofread
Complete separate copyediting and proofreading passes.

**Gate:** critical language and typography defects resolved or disclosed.

## Phase 10 — Publication production
Generate and validate reader PDF, print PDF and EPUB3 as applicable.

**Gate:** all publication files visually and technically inspected.

## Phase 11 — Independent cold-read and final evaluation
Run adversarial evaluation, score honestly and issue publication verdict.

**Gate:** complete final report and file manifest.

## Phase 12 — Git delivery
Commit work to the editorial branch, verify remote state and report exact branch/commit.

**Gate:** remote commit confirmed or exact upload blocker reported.

### Do not stop unnecessarily

Do not stop after each phase merely to ask whether to continue. Continue through all tasks that are safe, supported and authorised.

Pause only when:

- a required archive is encrypted and no password is provided;
- the authoritative manuscript cannot be identified and the choice materially changes the work;
- a major plot/ending/legal-outcome change requires author approval;
- a required external source or tool is unavailable;
- continuing would risk corrupting or overwriting originals;
- a legal or factual claim cannot be responsibly verified and the narrative change depends on it.

When paused, complete all independent work and present one concise, evidence-based list of decisions needed from the author.

---

# 23. FINAL REPORT — REQUIRED FORMAT

At the end, produce a complete final report in this order:

1. **Overall status:** complete, conditionally complete or blocked.
2. **Repository identity:** URL, default branch, starting commit, working branch, final commit.
3. **Repository inventory:** exact counts of files, archives, extracted entries and file types.
4. **Extraction report:** archives processed, entries extracted, exceptions and verification.
5. **Reading coverage:** files/pages/chapters read, partial or unreadable items, exact gaps.
6. **Source-of-truth decision:** authoritative manuscript and reasons.
7. **Manuscript comprehension:** chapter count, word count, story architecture and maps completed.
8. **Two-review reconciliation:** recommendations accepted, adapted, rejected, unsupported, contradicted and awaiting approval.
9. **Baseline diagnosis:** most serious verified issues.
10. **Revision work completed:** specific chapter-level changes and why.
11. **Continuity and factual corrections:** exact evidence and verification.
12. **Legal/procedural research:** sources checked, conclusions and limitations.
13. **Character/prose improvements:** specific examples without exaggeration.
14. **Copyedit/proofread results:** issue counts and remaining defects.
15. **Publication QA:** PDF/EPUB validation and visual inspection.
16. **Independent cold-read findings:** strongest remaining weakness and reader risks.
17. **Final scorecard:** weighted scores, confidence and evidence.
18. **Publication verdict:** ready, conditionally ready or not ready.
19. **Deliverables:** exact repository paths and filenames.
20. **Git summary:** branch, commit SHA, changed files and remote verification.
21. **Unresolved items:** exact blockers and author decisions needed.
22. **Integrity statement:** originals preserved, no fake/placeholder material, all material changes traceable, and no unverified work claimed complete.

Use exact counts. If a count is unknown, say so. Do not fabricate precision.

---

# 24. ABSOLUTE NON-NEGOTIABLE RULES

1. Read every relevant source completely. Do not skim and claim full review.
2. Extract every relevant ZIP safely and verify the extraction.
3. Do not assume file names reveal file contents or authority.
4. Do not use summaries as a substitute for reading the source.
5. Do not invent, fake, fabricate, simulate or silently fill missing facts.
6. Do not insert dummy data, placeholder text, fake evidence or fake citations.
7. Do not invent legal sections, case law, procedure, institutional practices or historical events.
8. Do not change the central story or ending without author approval.
9. Do not blindly obey either editorial review.
10. Do not turn unsupported review interpretations into fictional facts.
11. Do not rewrite dialogue to meet an arbitrary percentage.
12. Do not delete quiet atmosphere mechanically.
13. Do not make the antagonist omnipotent.
14. Do not make every character sound alike or artificially eloquent.
15. Do not flatten Indian English or local cultural texture.
16. Do not globally replace words, dates, phrases or punctuation without contextual checks.
17. Do not edit original files in place.
18. Do not delete source archives or old manuscript versions.
19. Do not claim legal verification, complete reading, extraction, validation or publication readiness without evidence.
20. Do not award 9.8/10 simply because it is the target.
21. Do not create empty files or folders to make the project look complete.
22. Do not commit directly to `main` or force-push without explicit author approval.
23. Do not hide blockers or unresolved questions.
24. If one source is unavailable, continue independent work and report the limitation.
25. Every material change must be traceable and every claimed correction must be rechecked across the complete manuscript.

---

# 25. FINAL DIRECTIVE

Begin now with live repository reconnaissance. Verify the current `main` branch and commit, inventory all repository contents, locate every uploaded ZIP/PDF/prompt/manuscript/review, safely extract all relevant archives, and read every relevant file completely.

Then establish the authoritative manuscript, reconcile every version, read the entire novel, apply the Master Editorial Transformation Prompt and both independent reviews through the evidence-led reconciliation process, and begin the actual editorial transformation.

Do not stop at a plan. Do not produce a superficial report. Do not claim completion prematurely.

**The deliverable is not merely a better-looking prompt or a list of suggestions. The deliverable is a demonstrably improved, coherent, emotionally credible, fact-checked, carefully proofread and publication-ready *The Ghost Tenant*, together with the complete source inventory, extraction and reading logs, editorial maps, research register, revision diffs, QA evidence and Git delivery record.**

The novel must earn its quality. Verify everything. Preserve what works. Fix what is demonstrably broken. Improve what can genuinely be improved. Never fabricate. Never hide uncertainty. Never sacrifice the novel's identity to satisfy a numerical score.

**END OF ARENA AGENT MASTER EXECUTION PROMPT**
