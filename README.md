This is a reiserfs kernel module compiled for the Bananapi. 

uname -a
Linux bananas 3.4.103 #4 SMP PREEMPT Thu Dec 18 12:55:58 CST 2014 armv7l GNU/Linux

To use, after booting insmod the module:

sudo insmod reiserfs.ko

After running the above, you will be able to mount reiserfs on your bananapi. 
