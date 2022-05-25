# LV_shifter-TTL_to_RS422

Top view:<br />
<img src="img/standard%20top.jpg" width="450" /><br />
Bottom view:<br />
<img src="img/standard%20bottom.jpg" width="450" /><br />
## Configuration

### Simple 3.3V to 5V Levelshifter:
<img src="img/Levelshiftersolder.jpg" width="450" />

### Digital LED over long cable with RS422:
Sender: From ESP (3.3V pin) -> Levelshift to 5V -> Translate to RS422 -> send out.<br />
Receiver: receive RS422 -> translate back -> control 5V digital LED.

Sender solder config       |  Receiver solder config
:-------------------------:|:-------------------------:
![Sender solder config](img/sendersolder.jpg)   |  ![Receiver solder config](img/receiversolder.jpg)

