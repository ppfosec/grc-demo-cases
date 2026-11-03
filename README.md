# GRC demo cases

Four small, fictional cases for [the Agentic GRC data sandbox](https://demos.thisisgrc.com/data). Each case changes one fact and shows how that could change the next question a practitioner asks.

## Change a case

1. Download or copy [`what-if-cases.json`](what-if-cases.json).
2. Edit one of the six text fields in a case. Keep the JSON structure and use fictional details only.
3. Open the [sandbox](https://demos.thisisgrc.com/data) and choose **Load an edited JSON file**.

Your file is read in your browser tab. This does not change the hosted Risk, Control, TPRM, or Heuristics Lens replays. Those Lenses use reviewed fixtures and outputs, so a changed input needs a new run and review before it can support a changed recommendation.

The case fields are `name`, `changeLabel`, `originalFact`, `changedFact`, `originalMove`, and `changedMove`. The sandbox accepts one to eight cases, each field must be a nonempty string of at most 500 characters, and the file must be under 50 KB.

## What the examples represent

The internal people, devices, findings, control changes, vendor engagements, and decisions in these four cases are fictional. TPRM Lens also has a separate eight-vendor portfolio built from real public evidence; those public vendor facts are not included here. See the public [TPRM Lens repository](https://github.com/ppfosec/tprm-data-mapping) for its fictional engagement fixture and public evidence method, and [Heuristics Layer](https://github.com/ppfosec/heuristics-layer) for the public judgment method.

This repository is the editable casebook for the small sandbox. It is not the source code for the combined Site or the full Lenses.
