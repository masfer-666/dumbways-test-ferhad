Dalam mengatur kebutuhan user sebagai administrator maupun non administrator, hal pertama kali yang akan saya lakukan adalah mengelompokan user tersebut kedalam group sebagai contoh untuk user root akan dikelompokan ke dalam group root & untuk user biasa akan dikelompokan kedalam user_only, sehingga administrator server dapat melihat user tersebut.


command:

###add user to group###

usermod -aG only_user test5

usermod -aG root ferhad

###check user in group###

grep only_user /etc/group

grep root /etc/group
