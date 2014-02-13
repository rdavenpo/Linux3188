Linux3188
=========

Test kernel 3.0.36+ for RK3188

This is an overclocked (1.7GHz, keep at 1.4GHz for stock)  and undervolted (~10%) kernel for my IPPLI Mars i2 3188T. 

# You need to be root
echo 1416000 > /sys/devices/system/cpu/cpu0/cpufreq/scaling_max_freq

If you don't get video signal, you need to turn blank off like this:

# You still need to be root
echo 0 > /sys/class/graphics/blank

