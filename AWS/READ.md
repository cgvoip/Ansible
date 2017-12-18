======================
If parameters are not set within the module, the following environment variables can be used in decreasing order of precedence AWS_URL or 
---
EC2_URL, AWS_ACCESS_KEY_ID or AWS_ACCESS_KEY or EC2_ACCESS_KEY, AWS_SECRET_ACCESS_KEY or AWS_SECRET_KEY or EC2_SECRET_KEY, AWS_SECURITY_TOKEN or EC2_SECURITY_TOKEN, AWS_REGION or EC2_REGION

======================
Ansible uses the boto configuration file (typically ~/.boto) if no credentials are provided. See http://boto.readthedocs.org/en/latest/boto_config_tut.html

---
AWS_REGION or EC2_REGION can be typically be used to specify the AWS region, when required, but this can also be configured in the boto config file

