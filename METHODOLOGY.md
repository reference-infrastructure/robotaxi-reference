# Methodology

## Purpose of This Document

This document defines the **methodological approach**
used to build and maintain the *Robotaxi Reference Framework*.

Its purpose is to:
- ensure analytical rigor
- make assumptions explicit
- enable auditability
- prevent interpretative drift over time

The methodology is descriptive and analytical,
not prescriptive or advisory.

---

## Analytical Approach

The framework follows a **system-oriented, evidence-based methodology**.

Key characteristics:
- system-level analysis over component-level detail
- structure before interpretation
- boundaries before conclusions
- evidence before synthesis

No conclusions are drawn
without explicit linkage to documented sources.

---

## Evidence Hierarchy

All analysis is grounded in a strict evidence hierarchy:

### Tier 1 — Normative Sources
- international standards (ISO, IEC, ETSI, SAE)
- binding regulations and legal instruments
- official regulatory frameworks

These sources define **hard constraints**.

### Tier 2 — Institutional Practice
- published guidance by regulatory authorities
- documented approval, reporting and oversight practices
- official compliance frameworks

These sources define **operational interpretation**.

### Tier 3 — Empirical Practice (Non-Normative)
- publicly disclosed operational data
- safety case publications
- transparency reports of active operators

These sources provide **illustrative evidence only**
and do not override Tier 1 or Tier 2 constraints.

---

## Source Validation

Each source must meet all of the following criteria:

- official publisher or issuing authority
- publicly accessible
- versioned or datable
- stable and citable
- directly relevant to robotaxi systems

All accepted sources are listed exhaustively in `SOURCES.md`.

Sources outside this list
are treated as **non-authoritative** for this release.

---

## Analytical Dimensions

Content is structured consistently across the following dimensions:

1. **System Definition**  
   What the system is — and is not.

2. **Technical Constraints**  
   Safety, cybersecurity, software lifecycle and interfaces.

3. **Regulatory Structure**  
   Legal obligations, approval models and audit requirements.

4. **Operational Reality**  
   Deployment, scaling and long-term operation.

5. **Economic Structure**  
   Cost persistence, capital requirements and sustainability.

6. **Societal Context**  
   Trust, accountability and institutional legitimacy.

Each dimension is treated as interdependent,
not as an isolated layer.

---

## Vendor Neutrality

The framework is strictly **vendor-neutral**.

Commercial entities may be referenced only when:
- unavoidable for empirical illustration
- publicly documented
- clearly labeled as non-exclusive examples

No vendor is:
- endorsed
- ranked
- promoted
- treated as representative of the market

---

## Handling of Uncertainty

Uncertainty is treated as a **structural property**,
not as a gap to be filled with speculation.

Where evidence is incomplete:
- uncertainty is stated explicitly
- boundaries are defined
- no extrapolation is performed

Future developments are not assumed,
forecasted or implied.

---

## Update and Change Discipline

This framework follows a **frozen-release model**.

- Content reflects the state of evidence at the release date.
- Changes are not incorporated continuously.
- Updates occur only via explicit new releases.

Any future update must:
- declare its release ID
- document changes explicitly
- preserve backward traceability

---

## Auditability

The methodology is designed to support auditability.

An audit must be able to:
- trace every analytical claim to a source tier
- identify assumptions clearly
- verify consistency across documents and pages

The baseline for audits is defined in `SCOPE.md`.

---

## Relationship to the Website

This methodology applies **equally** to:
- the GitHub repository
- the Robotaxi.de website
- all derived reference materials

No divergence between repo and website methodology is permitted.

---

## Freeze Status

- **Release ID:** 1.0.0  
- **Freeze Date:** 2026-02-03  
- **Status:** Frozen

This methodology is binding
for the corresponding frozen website release.
