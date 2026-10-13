```text
HANDOFF
turns: 20
learns by: definitions, occasional examples; concise explanations; assumes heliophysics background

domain: point processes | level: 2 | milestone: 2 reached | anchor: none
point process | claim: no | prior: none | end: introduced | "no quote"
event time | claim: no | prior: incorrect | end: deployed | "event time is when we see it"
counting process | claim: no | prior: none | end: introduced | "no quote"
inter-arrival time | claim: no | prior: none | end: introduced | "no quote"
Poisson process | claim: no | prior: none | end: introduced | "no quote"
independent increments | claim: no | prior: none | end: unused | "no quote"
memoryless | claim: no | prior: none | end: unused | "no quote"
Fano factor | claim: no | prior: none | end: deployed | "the one day feno effect"
overdispersion | claim: no | prior: none | end: introduced | "no quote"
other deployed: none
other open: events versus counts; interpretation across window widths

domain: statistical inference | level: 2 | milestone: 2 reached | anchor: null model
negative log-likelihood | claim: no | prior: none | end: deployed | "differences between NLL and EDM"
Earth Mover's Distance | claim: no | prior: none | end: deployed | "differences between NLL and EDM"
null model | claim: no | prior: none | end: misused | "which of the null model is more indicative of the variance rate"
other deployed: none
other open: probability density; nats; compare; rate envelope; why −ln(p) decreases as p increases; metric tradeoffs; reporting finite-only NLL; limitations of latitude-only scores
Progress: Student correctly predicted that zero density makes NLL blow up. Student explained that EMD uses latitude distances rather than NLL. The direction of the NLL penalty remains unresolved. No student construction of opposing metric changes has been produced.

domain: solar cycle physics | level: 2 | milestone: 2 reached | anchor: hemispheric cycle
emergence | claim: no | prior: none | end: deployed | "different emergence events got recorded together"
hemispheric cycle | claim: no | prior: none | end: introduced | "no quote"
alignment coordinate | claim: no | prior: none | end: introduced | "no quote"
other deployed: none
other open: observational delay
Progress: Distinguished physical emergence from first recorded observation after correcting misconceptions about observing the photosphere. Replication by hemispheric cycle and s as a pure time shift have been introduced but not demonstrated.

Progress on results: The student stated that the Fano-factor comparisons make memory difficult to establish, initially framing the task as choosing the more indicative null. The tutor clarified that changing the smoothing width changes the rate envelope and that conclusions must be assessed across both comparisons. The student then explained that the one-day excess does not establish memory in physical emergence because distinct emergence events could be recorded together through observation limitations. This is post-run reasoning, not a pre-run prediction.

Pending: Finish the remaining Section 2 metric-tradeoff discussion and Section 6 reasoning, especially independent increments and a counterexample to the claim that Fano factors alone establish a Poisson process. Tasks 1–9 have now been implemented and run by the student.
```

Post-run status (2026-10-12): The completed notebook was copied into this submission folder. Its saved outputs show all 36 nonempty code cells executed without recorded errors, and the homogeneous Poisson check passed. A results-and-interpretation markdown cell was appended to the submission copy, combining the saved numerical results with the student's discussion above. All original code cells and outputs were preserved. The remaining tutor discussion is recorded as pending rather than complete.
