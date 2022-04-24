# DRV_600_R1
Custom 600W BLDC motor controller for a one wheel gyro balancing robot test bed (work in progress)

Wish list:
- 500W power
- 48V supply
- USB communication
- PWM control
- Regen braking
- incremental and absolute encoder
- 20kHz data rate

The design:
- Texas Instrument DRV8301 driver
- STM32F4 ARM Cortex-M4 microcontroller
- 60V 46A MOSFETs
- Current sensing and protection

Top level

![image](https://user-images.githubusercontent.com/55325587/164989589-04745210-32e1-4f7b-88fe-be3dcdc6d203.png)

MCU

![image](https://user-images.githubusercontent.com/55325587/164989607-a98b38f7-359b-4bf6-972d-356396afadfd.png)

![image](https://user-images.githubusercontent.com/55325587/164989788-84661120-2902-4c46-8271-8738ca696724.png)

Driver

![image](https://user-images.githubusercontent.com/55325587/164989621-db390e4c-3fb3-4b96-bcec-972dd876c8dd.png)

Power management

![image](https://user-images.githubusercontent.com/55325587/164989631-767c8a3d-d418-44a6-84f3-9e7690869667.png)

Brake

![image](https://user-images.githubusercontent.com/55325587/164989648-5083d5b9-47a5-449d-9f0d-33462c6dd0a4.png)

Interface

![image](https://user-images.githubusercontent.com/55325587/164989654-5de5612c-4302-4c13-b2b2-3c1ec5cd19a8.png)

Layout

![image](https://user-images.githubusercontent.com/55325587/164989858-fd98bcb3-187a-4bca-8ccd-4a3f21efcbe5.png)

PCB

![image](https://user-images.githubusercontent.com/55325587/164989886-2b181071-946e-441a-beef-625849b1f0ed.png)

![image](https://user-images.githubusercontent.com/55325587/164989904-ed495df2-e90b-45c7-8442-50a0682ab068.png)

![image](https://user-images.githubusercontent.com/55325587/164989933-4c5f1d24-b72b-4f9c-b28a-f188d156761c.png)
