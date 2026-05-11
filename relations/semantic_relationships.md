# Semantic Relationships

This document describes public semantic relationships between imaging concepts.

---

# Example Relationships

CT attenuation:
- measured_in → Hounsfield Units
- uses → ROI
- affected_by → reconstruction parameters
- affected_by → imaging protocol

ROI:
- belongs_to → quantitative imaging
- used_for → structured measurement
- related_to → semantic imaging workflows

Quantitative imaging:
- includes → CT attenuation
- includes → ROI statistics
- supports → AI-readable workflows

---

# Scope

These semantic mappings are intended for documentation and interoperability purposes only.
