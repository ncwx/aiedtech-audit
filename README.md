# Child-Rights and AI-Governance Audit Framework for AIEdTech

This repository contains the framework, protocols, templates, sampling materials and criterion-level results supporting the study:

*Beyond Usefulness: Auditing Five AIEdTech Tools for Primary and Secondary Education Teachers*

The study develops and applies a structured external black-box audit for teacher-facing and teacher-mediated generative AI tools used in K–12 education.

## Repository contents

### framework/
- `audit_pillars.pdf` — conceptual structure of the Child Rights and AI Governance pillars and domains.
- `audit_framework.xlsx` — complete 35-criterion audit framework, including audit questions, rating thresholds, evidence sources and legal/policy bases.

### protocols/
- `audit_scope.pdf` — research scope, unit of analysis and audit boundaries.
- `evidence_collection_protocol.pdf` — standardized documentation-analysis, product-walkthrough and evidence-recording procedure.
- `behavioral_testing_protocol.pdf` — structured behavioral tests, prompts, conditions and evaluation rules.
- `product_walkthrough_synthetic_dataset.pdf` — standardized synthetic data used during product walkthroughs.

### sampling/
- `tool_selection_matrix.xlsx` — staged process used to identify and select the five audited tools.

### templates/
- `audit_workbook_template.xlsx` — reusable workbook for applying the audit framework to additional tools.

### results/
- `audit_results.xlsx` — completed evidence, criterion-level ratings and summary results for the five audited tools.

## Evidence model

Evidence was collected from three sources:

- **D — Documentation:** first-party provider documentation.
- **W — Product Walkthrough:** observable interface, settings, disclosures and controls.
- **B — Structured Behavioral Testing:** standardized prompts and recorded GenAI responses.

Evidence sources were kept separate during collection so that provider claims, observable interface features and generated behaviour were not collapsed into a single judgement.

## Rating scale

The standard evaluative scale comprised:

- *Supported*
- *Partially supported*
- *Not supported*
- *Not evidenced*
- *Not applicable*

*Not evidenced* is distinct from *Not supported*. Where an internal process could not be established through external evidence, the criterion was recorded as *Not evidenced* rather than treated as evidence that the process did not exist.

## Reproducing the audit

To apply the methodology to another tool:

1. Confirm that the tool falls within the scope defined in `audit_scope.pdf`.
2. Review the complete criteria in `audit_framework.xlsx`.
3. Conduct documentation analysis according to `evidence_collection_protocol.pdf`.
4. Conduct the systematic product walkthrough using the synthetic dataset where required.
5. Run applicable structured behavioral tests using `behavioral_testing_protocol.pdf`.
6. Record all evidence in `audit_workbook_template.xlsx`.
7. Apply the predefined criterion-level thresholds.
8. Review equivalent criteria across audited tools or cases to ensure consistent interpretation.

## Methodological scope

The methodology is an external black-box audit. It does not establish definitive legal compliance and cannot directly inspect inaccessible internal processes such as complete training-data provenance, server-side processing or internal risk-management systems.

Commercial products may also change over time. Findings therefore reflect the versions, access conditions and evidence available during the audit period.

## Citation

Citation information will be added following publication.