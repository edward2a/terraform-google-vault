# Changelog

## v1.1.0
* Updates for google-provider 2.0
* Removed vault-admin IAM policy bindings in favour of non-authoritative IAM member resource
* Add default value update_policy

## v1.0.2
* Use network and subnetowrk to allow the usage of custom VPC
* Bucket objects were failign with content so switched to source
* Add HTTPS listener and self signed cert in nginx
* Enable UI
* Change to MIG fork

## v1.0.1
* Bucket: do regional by default and use var.region instead of multi-region/US (seriously?!)

## v1.0.0
* Original fork from https://github.com/GoogleCloudPlatform/terraform-google-vault.git
