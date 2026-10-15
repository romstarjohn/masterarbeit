# Rules for AI agents

These instructions apply to every AI agent working in this repository. The
researcher is the final authority on scope, content, methods, and conclusions.

## 1. Researcher control and scope

1. Work only on tasks explicitly requested or explicitly approved by the
   researcher.
2. Never expand the agreed scope autonomously. Do not add a new research
   question, hypothesis, method, chapter, argument, dataset, tool, deliverable,
   recommendation, or project-management item without prior confirmation.
3. Do not insert `TODO`, `TBD`, placeholders, speculative content, example
   content, or proposed future work unless the researcher has asked for it.
4. If a task requires a material decision that has not been agreed, stop and ask
   one clear question. Do not make the decision on the researcher's behalf.
5. Suggestions outside the current scope must first be presented as a question.
   They may be implemented only after the researcher explicitly accepts them.
6. Do not reinterpret silence as approval. Previous approval applies only to the
   stated change and does not authorize related changes.
7. Do not modify unrelated files, reorganize the thesis, or perform opportunistic
   cleanup while completing another task.

## 2. Plan before every edit

1. Before changing, creating, renaming, moving, or deleting any file, state a
   concise plan describing the exact intended changes and their verification.
2. The plan must identify assumptions and any choice that could affect the
   scientific meaning or project scope.
3. If the plan contains anything not already authorized, obtain explicit
   confirmation before editing.
4. If new information changes the plan, announce the revised plan before making
   further edits.

## 3. Evidence before writing

1. Evidence comes before prose. Do not write a substantive scientific claim
   until adequate supporting evidence has been located and examined.
2. Every factual, empirical, quantitative, historical, technical, or causal
   claim must be supported by a traceable source, data, calculation, or formal
   derivation appropriate to that type of claim.
3. Place citations directly beside the claims they support. A bibliography entry
   alone is not evidence that a particular claim is supported.
4. For books and papers, record precise page, section, figure, table, or theorem
   locations whenever available. For online material, record a stable URL, the
   responsible organization or author, publication date, and access date.
5. Never cite a source that the agent has not inspected. Never claim that a
   source supports a statement unless the relevant passage, data, or result has
   been checked.
6. Never invent or guess citations, authors, titles, dates, DOIs, page numbers,
   quotations, datasets, measurements, statistics, or experimental results.
7. AI-generated text and summaries are not evidence. They must be verified
   against original, authoritative sources before use.
8. If sufficient evidence cannot be found, do not present the statement as fact.
   Report the evidence gap to the researcher and ask how to proceed.

## 4. Meaning of proof

The required support depends on the claim:

- A mathematical claim requires a valid derivation or a precise reference to an
  established theorem whose assumptions are satisfied.
- An empirical claim requires traceable data and a documented method of
  collection and analysis.
- A quantitative claim requires reproducible calculations, units, inputs, and
  uncertainty where relevant.
- A causal claim requires a research design capable of supporting causality;
  correlation or temporal order alone is insufficient.
- A technical claim requires authoritative documentation, a standard, source
  code, or a reproducible test.
- A claim about prior research requires the original publication, not an
  unverified secondary summary.

Scientific evidence usually supports a claim to a stated degree rather than
proving it absolutely. Use calibrated language and never express greater
certainty than the evidence warrants.

## 5. Source quality

1. Prefer primary research, official standards, authoritative documentation,
   original datasets, and peer-reviewed publications.
2. Use secondary sources for orientation or synthesis only when appropriate and
   trace important claims back to primary sources.
3. Evaluate source relevance, methodology, sample, limitations, publication
   context, conflicts of interest, and date before relying on it.
4. Distinguish peer-reviewed evidence from preprints, opinion, marketing,
   unsourced web content, and AI-generated material.
5. Do not use a source merely because it agrees with the expected conclusion.
   Seek relevant contradictory evidence and report it fairly.
6. Do not add a bibliographic entry unless its metadata has been verified.

## 6. Quotations, paraphrases, and citations

1. Quotations must reproduce the source exactly, use quotation marks, and include
   a precise source location.
2. Paraphrases must accurately preserve the source meaning and still include a
   citation.
3. Do not cite a source for a broader or different claim than it establishes.
4. Clearly distinguish the source author's conclusion from the thesis author's
   interpretation.
5. Respect copyright and licence conditions. Do not copy unnecessary source text
   into the repository.

## 7. Data and analysis integrity

1. Preserve raw data and document provenance. Do not overwrite or silently
   correct source data.
2. Document every cleaning, exclusion, transformation, coding decision, and
   derived variable sufficiently for reproduction.
3. Do not omit inconvenient observations, negative results, limitations, or
   contradictory findings.
4. Never fabricate, manipulate, or selectively report data to support a desired
   conclusion.
5. State assumptions, units, sample sizes, missing-data handling, uncertainty,
   and relevant limitations.
6. Keep exploratory analysis distinct from confirmatory analysis.
7. Do not introduce or change an analytical method without researcher approval.

## 8. Scientific writing

1. Separate established evidence, interpretation, inference, hypothesis, and
   recommendation. Label each accurately.
2. Avoid unsupported generalizations, absolute wording, rhetorical exaggeration,
   and causal language not justified by the method.
3. Define important terms and use them consistently.
4. State the population, context, period, and boundary conditions to which a
   conclusion applies.
5. Present relevant limitations and alternative explanations beside the results
   they qualify.
6. Do not fill missing information with plausible-sounding text. Ask the
   researcher for the missing information.

## 9. AI transparency

1. Record material AI assistance in `tools/ai-usage-log.md` only when the
   researcher has authorized the entry or requested logging for the task.
2. Document the purpose, tool/model when known, retained output, human review,
   corrections, and affected files or sections.
3. Never expose confidential information, personal data, credentials, or
   copyrighted full text to an AI system without explicit authorization and a
   lawful basis.
4. Never describe AI output as independently verified research.

## 10. Verification before handoff

Before reporting a task as complete, the agent must:

1. Check every new substantive claim against its cited evidence.
2. Confirm that quotations, numbers, names, dates, and citation metadata match
   their sources.
3. Verify that interpretations do not exceed the evidence.
4. Check that no unapproved proposal, placeholder, `TODO`, or scope change was
   introduced.
5. Review the diff to confirm that only authorized files and content changed.
6. Run the relevant build, validation, calculation, or test when it can be done
   safely within the agreed scope.
7. Report unresolved evidence gaps, failed checks, assumptions, and limitations
   plainly. Never conceal them to make the work appear complete.
