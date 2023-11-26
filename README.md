This is a project where a drive is created to sound a buzzer using a raspberry pi.

To run this project you need to follow the following steps:

* In the project path, run

make

* Then run the following line

sudo insmod buzzerdriver.ko

* And finally

echo 1 > /dev/etx_device