# Compliance Matrix

This matrix maps core obligations to common regulations and indicates next actions.

| Obligation | GDPR | CCPA | Notes / Next Steps |
|---|---:|---:|---|
| Privacy notice transparency | Yes | Yes | Ensure `PRIVACY_POLICY.md` includes required sections and language.
| Data subject rights handling | Yes (extensive) | Yes (consumer requests) | Implement request intake and verification process. Note: current release does not collect personal data; rights workflows mainly apply if/when ads or data collection are enabled.
| Data processing records | Yes | No | Maintain records of processing activities (RoPA).
| Data breach notification | Yes (72h) | Yes (reasonable) | Create incident playbook; map notification workflows.
| DPA with processors | Yes | Recommended | Use `DATA_PROCESSING_ADDENDUM.md`. Ad networks (e.g. Google AdMob) are integrated; verify their DPA/Privacy terms. |
| Right to delete / opt-out | Yes/varies | Yes (opt-out of sale) | Implement UI and backend handling for deletion and opt-outs.
| International transfers | SCCs / adequacy | N/A | Identify transfer mechanisms and document safeguards.
| Security controls | GDPR: require appropriate measures | CCPA: reasonable security | Align `SECURITY_POLICY.md` with standard frameworks (ISO27001, SOC2) as needed.

## Next Actions
- Replace placeholders in policy files with company-specific details.
- Legal review of `PRIVACY_POLICY.md` and `TERMS_OF_SERVICE.md`.
- Implement intake process for data subject requests.
- Maintain subprocessors list and publish where required.
