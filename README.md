This is a bare metal (no pico sdk) c++ implementation of a capacitive touch lamp. This project is just an attempt to hone my bare metal arm skills in preparation for more advanced projects I need to create in the future. This works by measuring the time it takes for the voltage to change on a pin. This time is affected when a large body like a human is near by, which we use to change the brightness of the lamp. 