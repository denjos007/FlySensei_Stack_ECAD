Actuation stack for the stackable blimp controller

# Functional Specifications
- PWM driver: PCA9685BS 16 channel 
- I2C control input with selectable channels
- 2S 3S and 4S LiPo input voltage capability
- 8 Servo channels with 5V power
- 8 BLDC or 4 Brushed motor channels with direct VBATT
- Optional 2S battery monitor: MAX17049G+T10
- Optional high current solder points for battery input

# Caution
- Check battery polarity before inserting the connecting the lipo battery
- When using 3S or higher voltage battery, remove the attached fuel gauge IC. Its rated only for 2S

# Contributors
Joseph Prince Mathew - jprincem@masonlive.gmu.edu