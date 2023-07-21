# Sysdig Secure for Cloud in Google

Terraform module that deploys the Sysdig Secure for Cloud stack in GCP.

Provides unified threat-detection, compliance, forensics and analysis through these major components:

* **[CSPM](https://docs.sysdig.com/en/docs/sysdig-secure/benchmarks/)**: It evaluates periodically your cloud configuration, using Cloud Custodian, against some benchmarks and returns the results and remediation you need to fix. Managed through `trust-relationship` module. <br/>

For other Cloud providers check: [AWS](https://github.com/draios/terraform-aws-secure-for-cloud), [Azure](https://github.com/draios/terraform-azurerm-secure-for-cloud)


