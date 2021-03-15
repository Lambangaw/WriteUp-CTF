# Soal

My password is my secret. You will never find it...

<http://challs.dvc.tf:5555/>

To validate this chall, please enter the secret code as the flag.

## Solution

Terdapat script js pada source code website namun setelah di deobfuscate ternyata ya tidak terlalu merubah apapun, salah satu tim saya nopal, memanggil salah satu variabel yang terlihat aneh pada console dan ternyata lebih mudah hehe. 

![console](images.png)

setelah mencoba mendecode beberapa strings kita tertuju pada satu bagian array yang lumayan unik dan di encode menggunakan url encoding kita decode saja dan muncullah flagnya.

    dvCTF{1t_is_n0t_4_secr3t_4nym0r3}
