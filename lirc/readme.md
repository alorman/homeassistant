Add this to the /etc/modules files

     lirc_dev
     lirc_rpi gpio_in_pin=18 gpio_out_pin=21


Add this to the /boot/config.txt files

     dtoverlay=lirc-rpi,gpio_in_pin=18,gpio_out_pin=21

