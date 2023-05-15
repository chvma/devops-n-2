# devops-n-1

Hey!


_____

Terraform/.gitignore is created to ignore:
1. All local **/.terraform/* directories
2. All *.tfstate and *.tfstate.* files
3. All crash log files like crash.log and crash.*.log
4. All .tfvars and .tfvars.json files, which could contain sensitive data. They should not be part of version control.
5. All override files like override.tf and override.tf.json, *_override.tf and *_override.tf.json as they are usually used to override resources locally.
6. All CLI configuration files like .terraformrc and terraform.rc
