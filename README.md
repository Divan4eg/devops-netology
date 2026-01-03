# devops-netology
task number 8
Будут проигнорированы следующие файлы
1. Служебная директория .terraform и все ее содержимое
2. Файлы состояния (tfstate) в любых директориях. Попадут как файлы вида 123.tfstate, так и вида 123.tfstate.321
3. Файлы логов сбоев (crash log) в любых директориях. Попадут как основной лог, так и дополнительные вида crash.123.log
4. Файл с переменными (123.tfvars) и его json-вариант (123.tfvars.json) в любых директориях
5. Файлы переопределений (override.tf, override.tf.json) в любых директориях. Также плпадут файлы вида 123_override.tf и 123_override.tf.json
6. Файл .terraform.tfstate.lock.info в любой директории
7. Файлы .terraformrc и terraform.rc в любой директории

