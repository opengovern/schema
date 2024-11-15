# Columns  

<table>
	<tr><td>Column Name</td><td>Description</td></tr>
	<tr><td>id</td><td>The security findings provider-specific identifier for a finding.</td></tr>
	<tr><td>arn</td><td>The Amazon Resource Name (ARN) for the finding.</td></tr>
	<tr><td>company_name</td><td>The name of the company for the product that generated the finding.</td></tr>
	<tr><td>confidence</td><td>A finding&#39;s confidence. Confidence is defined as the likelihood that a finding accurately identifies the behavior or issue that it was intended to identify.</td></tr>
	<tr><td>created_at</td><td>Indicates when the security-findings provider created the potential security issue that a finding captured.</td></tr>
	<tr><td>compliance_status</td><td>The result of a compliance standards check.</td></tr>
	<tr><td>updated_at</td><td>Indicates when the security-findings provider last updated the finding record.</td></tr>
	<tr><td>criticality</td><td>The level of importance assigned to the resources associated with the finding.</td></tr>
	<tr><td>description</td><td>A finding&#39;s description.</td></tr>
	<tr><td>first_observed_at</td><td>Indicates when the security-findings provider first observed the potential security issue that a finding captured.</td></tr>
	<tr><td>generator_id</td><td>The identifier for the solution-specific component (a discrete unit of logic) that generated a finding.</td></tr>
	<tr><td>last_observed_at</td><td>Indicates when the security-findings provider most recently observed the potential security issue that a finding captured.</td></tr>
	<tr><td>product_arn</td><td>The ARN generated by Security Hub that uniquely identifies a product that generates findings.</td></tr>
	<tr><td>product_name</td><td>The name of the product that generated the finding.</td></tr>
	<tr><td>record_state</td><td>The record state of a finding.</td></tr>
	<tr><td>schema_version</td><td>The schema version that a finding is formatted for.</td></tr>
	<tr><td>source_url</td><td>A URL that links to a page about the current finding in the security-findings provider&#39;s solution.</td></tr>
	<tr><td>verification_state</td><td>Indicates the veracity of a finding.</td></tr>
	<tr><td>workflow_state</td><td>[DEPRECATED] This column has been deprecated and will be removed in a future release. The workflow state of a finding.</td></tr>
	<tr><td>workflow_status</td><td>The workflow status of a finding. Possible values are NEW, NOTIFIED, SUPPRESSED, RESOLVED.</td></tr>
	<tr><td>standards_control_arn</td><td>The ARN of the security standard control.</td></tr>
	<tr><td>action</td><td>Provides details about an action that affects or that was taken on a resource.</td></tr>
	<tr><td>compliance</td><td>This data type is exclusive to findings that are generated as the result of a check run against a specific rule in a supported security standard, such as CIS Amazon Web Services Foundations.</td></tr>
	<tr><td>finding_provider_fields</td><td>In a BatchImportFindings request, finding providers use FindingProviderFields to provide and update their own values for confidence, criticality, related findings, severity, and types.</td></tr>
	<tr><td>malware</td><td>A list of malware related to a finding.</td></tr>
	<tr><td>network</td><td>The details of network-related information about a finding.</td></tr>
	<tr><td>network_path</td><td>Provides information about a network path that is relevant to a finding. Each entry under NetworkPath represents a component of that path.</td></tr>
	<tr><td>note</td><td>A user-defined note added to a finding.</td></tr>
	<tr><td>patch_summary</td><td>Provides an overview of the patch compliance status for an instance against a selected compliance standard.</td></tr>
	<tr><td>process</td><td>The details of process-related information about a finding.</td></tr>
	<tr><td>product_fields</td><td>A data type where security-findings providers can include additional solution-specific details that aren&#39;t part of the defined AwsSecurityFinding format.</td></tr>
	<tr><td>related_findings</td><td>A list of related findings.</td></tr>
	<tr><td>remediation</td><td>A data type that describes the remediation options for a finding.</td></tr>
	<tr><td>resources</td><td>A set of resource data types that describe the resources that the finding refers to.</td></tr>
	<tr><td>severity</td><td>A finding&#39;s severity.</td></tr>
	<tr><td>threat_intel_indicators</td><td>Threat intelligence details related to a finding.</td></tr>
	<tr><td>user_defined_fields</td><td>A list of name/value string pairs associated with the finding.</td></tr>
	<tr><td>vulnerabilities</td><td>Provides a list of vulnerabilities associated with the findings.</td></tr>
	<tr><td>source_account_id</td><td>The account id where the affected resource lives.</td></tr>
	<tr><td>title</td><td>A finding&#39;s title.</td></tr>
	<tr><td>partition</td><td>The AWS partition in which the resource is located (aws, aws-cn, or aws-us-gov).</td></tr>
	<tr><td>region</td><td>The AWS Region in which the resource is located.</td></tr>
	<tr><td>account_id</td><td>The AWS Account ID in which the resource is located.</td></tr>
	<tr><td>og_account_id</td><td>The Platform Account ID in which the resource is located.</td></tr>
	<tr><td>og_resource_id</td><td>The unique ID of the resource in opengovernance.</td></tr>
	<tr><td>kaytu_metadata</td><td>Platform Metadata of the AWS resource.</td></tr>
</table>