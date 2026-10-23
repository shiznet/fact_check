# Core reference

## Claim taxonomy
Classify claims where useful as:
- Descriptive/stable fact
- Quantitative/statistical claim
- Causal claim
- Historical or attribution claim
- Policy, legal, or procedural claim
- Product/technical capability claim
- Prediction or forecast
- Personal experience/testimonial
- Opinion, preference, or value judgment
- Advertising or promotional claim

Preserve the exact source wording and surrounding qualifiers. Separate compound claims that need different evidence. Watch for absolutes such as “always”, “all”, “guaranteed”, “proven”, and “currently”.

## Analyze the argument, not only its parts
For a compound statement, identify:
1. **Central conclusion:** what the statement ultimately asks the reader to believe.
2. **Premises:** facts offered as support.
3. **Inference or causal link:** how the premises are claimed to support the conclusion.
4. **Component claims:** factual subclaims that may need separate verification.

Check components individually to gather evidence, but then judge the statement as a whole. A list of individually true and false subclaims is not, by itself, sufficient to assign MIXED. If the statement's central conclusion is supported but its stated explanation is materially false or its causal link is invalid, label the statement REFUTED because the argument being asserted is unsound; explain separately whether the conclusion itself happens to be true. Use MIXED only when materially distinct factual components have differing truth values and there is no single central conclusion whose supporting reasoning is faulty.

Example: “Venus is the closest planet to the Sun, so it has the highest surface temperature.” The conclusion that Venus has the highest average surface temperature is true, but the premise is false (Mercury is closest to the Sun) and the explanation is faulty; the overall argument is REFUTED. Venus's high surface temperature is primarily explained by its dense carbon-dioxide atmosphere and strong greenhouse effect.

## Evidence policy
Prefer evidence with direct relevance, traceable provenance, transparent methods, suitable expertise, and correct scope. Primary sources are not automatically sufficient for every claim: official documentation is strong evidence of stated product behavior, for example, but may not establish real-world effectiveness. A research paper is evidence of what that study found, subject to its design and limitations. Source code may establish behavior for a revision, not deployment in production.

For important or disputed claims, seek independent corroboration and actively look for counterevidence. Trace repeated statements to their earliest identifiable source. Do not treat copied articles, reposts, or items based on one press release as independent confirmation. Search snippets are discovery aids only. If only an abstract or snippet was accessible, disclose that limitation. Never invent quotations, URLs, dates, sources, or verification steps.

Evaluate identity/provenance, directness, relevance, currency, method, independence, incentives, and limitations. For causal claims, distinguish causation from correlation and confounding. For comparisons, check that metric, period, population, and conditions match. For consensus claims, establish whose consensus is meant.

## Verdict discipline
Use exactly one primary verdict per claim: SUPPORTED, REFUTED, MIXED, INSUFFICIENT_EVIDENCE, or UNVERIFIABLE. State scope when relevant and explain the decisive evidence. Do not infer falsity from absent search results, truth from popularity or repetition, or causality from an anecdote. Separate the truth of an attribution from the truth of the attributed statement. For conflicting evidence, compare date, method, definitions, applicability, and quality; otherwise leave the issue unresolved. For changing claims, state the relevant date/version. High-impact claims require stronger evidence and more explicit limitations.

- **SUPPORTED:** evidence supports the central claim and material reasoning.
- **REFUTED:** evidence contradicts the central claim, or a materially false premise/invalid causal link undermines the argument as presented—even if the conclusion happens to be true for another reason.
- **MIXED:** use only when distinct material factual components differ in truth value and no central conclusion is being justified by materially faulty reasoning. Do not use MIXED simply because a true conclusion is paired with a false reason.
- **INSUFFICIENT_EVIDENCE:** evidence is unavailable, too weak, or materially conflicting to decide.
- **UNVERIFIABLE:** the claim lacks a workable objective test or is too vague/subjective.

## Report template
1. **Conclusion:** direct, scoped answer and overall verdict.
2. **Claims checked:** claim text/normalized claim, verdict, concise rationale.
3. **Evidence:** sources and relevant excerpts/data; explain how each supports or contradicts the claim.
4. **Counterevidence and caveats:** material conflicts, scope conditions, and alternative explanations.
5. **Limitations and coverage:** inaccessible sources, tools that failed, claims not checked, and the extent of review.
6. **Sources:** links or stable identifiers for material evidence.
