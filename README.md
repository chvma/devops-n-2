# devops-n-1

Hey! 

_____

Terraform/.gitignore is created to ignore:

    All local */.terraform/ directories
    All *.tfstate and .tfstate. files
    All crash log files like crash.log and crash.*.log
    All .tfvars and .tfvars.json files, which could contain sensitive data. They should not be part of version control.
    All override files like override.tf and override.tf.json, *_override.tf and *_override.tf.json as they are usually used to override resources locally.
    All CLI configuration files like .terraformrc and terraform.rc

_____

There is a new branch "Fix"
