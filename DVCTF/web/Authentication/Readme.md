Soal


Can you find a way to authenticate as admin?

http://challs.dvc.tf:1337/


Solution

Tujuan kita adalah login sebagai admin, disini saya coba langsung masuk dengan username admin password admin namun muncul warning 'How dare you?'. Sepertinya saya sudah berasa dalam jalan yang benar kini saya coba menambahkan sql injection 

payload :
    username : admin
    password : ' or 1=1 --

HMMM... langsung bisa ternyata, dan flag terdapat ketika inspect element dan terdapat flagnya pada comment 

    dvCTF{!th4t_w4s_34sy!}