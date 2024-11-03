import pywhatkit as kit
import time

group_name = 'grup adi'
message = 'mesajiniz'

while True:
    current_time = time.localtime()
    hour = current_time.tm_hour
    minute = current_time.tm_min + 1

    if minute >= 60:
        minute -= 60
        hour += 1

        kit.sendwhatmsg_to_group(group_name, message, hour, minute)

        time.sleep(20)
