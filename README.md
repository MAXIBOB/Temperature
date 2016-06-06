# Temperature
#Display's the current temperature
from sense_hat import SenseHat
sense=SenseHat()
while True:
    temp=sense.get_temperature()
    sense.show_message(str(int(temp)))
