# GloBIAS 2026 · Group 5 · workshop

Working space for **Group 5** in **Session 06 "Benchmarking"** of the GloBIAS 2026 workshop: discussions,
meeting notes, LLM-benchmark entries, consensus experiments and the presentation. *Group work for the
workshop; not an official GloBIAS repository.*

## The assignments

From the session document:

- **Assignment I.** Choose an example bioimage analysis question and an image dataset, construct a prompt,
  use at least three different LLMs, and examine their proposals from a professional bioimage analyst's
  point of view, comparing the answers.
- **Assignment II (Group 5, Consensus).** *Can consensus become ground truth?* Participants receive several
  independent annotations of the same dataset and construct a reference annotation. Possible strategies:
  majority vote, expert adjudication, unanimity, weighted expertise, or exclusion of uncertain regions.
  Output: the consensus ground truth and the rule used to construct it. Key question: ***Is consensus
  sufficient to define ground truth?***
- **Presentation.** 15 minutes per group on the LLM benchmarking and the discussions.

## How to use the issues

| I want to… | New issue → | Labels |
|---|---|---|
| propose or discuss a topic | **Workshop discussion topic** | `discussion` |
| record one LLM's answer (Assignment I) | **Assignment I: LLM benchmark entry** | `llm-benchmark` `assignment-1` |
| record one consensus experiment (Assignment II) | **Assignment II: consensus experiment** | `consensus` `assignment-2` |
| write up a meeting | **Meeting notes** | `meeting` |

Conventions: one topic per issue; paste LLM prompts and answers verbatim; action items as task lists
(`- [ ] @who — what — by when`); post the conclusion as the last comment before closing a thread;
`decision-needed` marks threads where the group has to decide. The labels are created from
`.github/labels.tsv` by `.github/workflows/labels.yml`.

## Related repositories

| repository | what it holds |
|---|---|
| [ilastik-mitocheck-run](https://github.com/globias-2026-group5/ilastik-mitocheck-run) | One LLM agent (Claude) running ilastik's MitoCheck cell-tracking example end to end, with every step, error and result documented |
| [agent-benchmark-ilastik-tracking](https://github.com/globias-2026-group5/agent-benchmark-ilastik-tracking) | That run compared with four later sessions: two reproductions and two "blind" runs on the Group 5 question |
| [shape-analysis-field-guide](https://github.com/globias-2026-group5/shape-analysis-field-guide) | A plain-language guide to the Shape Analysis 101 tutorial, with the [published site](https://globias-2026-group5.github.io/shape-analysis-field-guide/) |

## Reading (from the session document)

- Cortese & Castagnola (2026), *Seeing, Interpreting, and Trusting Images in the Age of Artificial
  Intelligence*, J. Histochem. Cytochem. https://doi.org/10.1369/00221554261454582
- Pan, Panzeri, Johanns et al. (2026), *BIABench: Evaluating AI Agents on Real-World Bioimage Analysis
  Tasks*, arXiv:2609.34274. https://doi.org/10.48550/arXiv.2609.34274
- Real bioimage analysis cases from cell biology journals:
  https://miura.github.io/Bioimage-Analysis-Methods-in-Journals/
- Session chat: GloBIAS Zulip, `#Workshop2026 > Session 06 Benchmarking`
