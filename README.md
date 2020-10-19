```sh
$ make
$ sudo cp 8812au.ko /lib/modules/$(uname -r)/kernel/drivers/net/wireless
$ sudo depmod
$ echo 8812au | sudo tee -a /etc/modules
```
