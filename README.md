# ASP‑E1 — Agent Identity Profile Normalizer

ASP‑E1 is an extension of the Agent State Packet (ASP) that standardizes,
validates, and canonicalizes incoming agent identity packets. This ensures
every agent entering the ecosystem conforms to a single deterministic identity
format, enabling consistent downstream processing and reliable multi‑agent
interoperability.

This template is machine‑only, zero‑contact, and revenue‑generating by design.

---

## Overview
ASP‑E1 extends the Agent State Packet (ASP) by providing deterministic
normalization, validation, and canonicalization of incoming agent identity
packets. This ensures all agents entering the ecosystem conform to a unified
identity structure.

## Purpose
- Enforce strict identity formatting
- Remove unknown or malformed fields
- Validate required ASP identity components
- Produce a canonical identity packet for downstream processing

## Machine‑Only Design
This template is intended exclusively for machine‑to‑machine execution.
No human interaction, examples, or onboarding flows are included.

## Revenue Model
Each invocation triggers a micropayment under the event:
`identity_normalization`.

## Files
- README.md  
- template.json

## Extension Relationship
This template inherits from and extends the ASP root template without
modifying or altering the frozen ASP schema.
