## Robert Rothermel
### Azure DevOps & Platform Engineer — CI/CD and Azure platform engineering for regulated, compliance-driven environments

Personal engineering portfolio. This profile is where my clean-room reference implementations live —
Azure DevOps CI/CD, AKS, IaC, and compliance-grounded automation, each isolated so the mechanics are
easy to review.

**[quantize.engineering](https://www.quantize.engineering)** · [Résumé (PDF)](https://www.quantize.engineering/Robert-Rothermel-Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/robert-rothermel-quantize) · robert@quantize.engineering

Five years of production Azure: I led an on-prem datacenter → Azure migration, built the CI/CD
pipeline that took releases from ~2 hours to ~20 minutes, and implemented the cloud-side SOC 2
controls that pass an auditor's review. **AZ-104** certified; **AZ-400** in progress.

### Selected reference implementations

Independent, clean-room builds — each isolates one hard problem from production-grade Azure DevOps
work. Not the property of any prior employer. Repositories publish here as they clear a validation
pass; available on request in the meantime.

| Build | What it demonstrates |
|---|---|
| **Gated AKS Node-CVE Remediation** | A CVE-patched AKS node image treated as a promotable, gated artifact — canaried in a tainted nodepool, regression-tested, PDB-protected on promotion; a fail-closed KQL telemetry gate; stages mapped to SOC 2 controls (CC7.1, CC8.1). |
| **Canary Deployment with Automated Health Gating** | .NET → App Service canary slot, 10% live traffic, telemetry-driven promote-or-rollback with no human in the go/no-go loop. |
| **Blue/Green Private Azure Landing Zone** | Private-only hub-and-spoke (AKS · Container Apps · Databricks) over private endpoints, Pulumi (C#), CrossGuard policy-as-code enforcing "private-only." |
| **Terraform: State, Drift & Refactor Lab** | Backend state locking, `for_each`/`dynamic`, `import` of out-of-band resources, drift handling, and a zero-diff module refactor with `moved` blocks. |

### Stack

`Azure` (AKS · App Service · Front Door · Entra ID · Defender · Monitor/KQL) · `Bicep` · `Terraform` · `Pulumi` · `Azure DevOps` · `GitHub Actions` · `C#/.NET` · `PowerShell` · `SOC 2`

<sub>Personal portfolio of Robert Rothermel. "Quantize" is a one-person practice — this profile is where the engineering work lives, not a company with staff or customers.</sub>
