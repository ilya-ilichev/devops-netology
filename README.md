# devops-netology
**/.terraform/*
# Игнорирует собственные директории terraform в любом расположении

*.tfstate
*.tfstate.*
# Игнорирует файлы с расширением .tfstate, *.tfstate.* игнорирует любой файл или директорию чье имя включает в себя .tfstate.

crash.log
# Игнорирует любые файлы с именем crash.log

*.tfvars
# Игнорирует все файлы с расширением .tfvars

override.tf
override.tf.json
*_override.tf
*_override.tf.json
# Игнорирует любые файлы с именами override.tf, override.tf.json, а так же файлы включающие в свое имя _override.tf, _override.tf.json

.terraformrc
terraform.rc
# Игнорирует файлы с именами .terraformrc, terraform.rc
