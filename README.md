# devops-netology

` **/.terraform/*` - Игнорирование всего, что вложено в каталог .terraform (который может находится на любом уровне вложенности от gitignore)

`*.tfstate` -  игнорировать файлы с расширением .tfstate
`*.tfstate.*` - игнорировать файлы с наличием в названии ".tfstate"

`crash.log` - игнорировать файл ".crash.log"
`*.tfvars` - игнорировать файлы с расширением .tfvars 

`override.tf` - игнорировать файл ".override.tf"
`override.tf.json` - игнорировать файл "override.tf.json"
`*_override.tf` - игнорировать файл, заканчивающийся на "_override.tf"
`*_override.tf.json` - игнорировать файл, заканчивающийся на "_override.tf.json"

`.terraformrc` - игнорировать файлы с расширением .terraformrc
`terraform.rc` - игнорировать файл "terraform.rc"
