# Tagging

### Required Tags
- availability : {none, availability-zone, auto-recovery, auto-scaling, global}
- cost-center : $unit-number
- customer : $unit-number
- environment : {production, stage, test, development}
- expected-traffic : {none, internal_outbound, internal_inbound, external_outbound, external_inbound, aws-backplane}
- git-repo : $resource-source-code
- Name : $resource-name-as-per-convention
- orchestration : {cloud-formation, sdk, cli, aws-console}
- service-name : $name-of-the-application-or-service
- service-type : $value-based-onthe-tech-stack-the-service-is-deployed-to
- technical-owner : {business-intelligence, database-administrators}
- Patch Group : #required for EC2 - depending on the day the server can be patched
- backup : #required for EC2 and DB


### Optional
- auto-destroy-at : #Military time ex 0425 or 1345
- auto-shut-down-at : #Military time ex 0425 or 1345
- auto-start-at : #Military time ex 0425 or 1345
- commit-hash : $hash-generated-by-git
- data-integrity : {low, moderate, high}
- safe-to-destroy : {yes, no} # used in cases where purging is required based on a proj or product
- security-confidentiality: {public, internal, confidential}
- EBSRetain : {Null, DND, do not delete} # used for EBS retention after the EC2 instance is destroyed.


## for this project
- name : muthu-lab-aws-data-engg-lifecycle-1-<service>
- project : muthu-lab-aws-data-engg-lifecycle-1
- environment : dev
- safe-to-destroy : yes

