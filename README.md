# Autonomous-Takeoff-and-Land-Python-Script
Python script to run on companion computer and send custom mavlink messages

# YouTube Video Guide
please follow this link to youtube video to get detailed information about this script and execution on the actual vehicle

https://www.youtube.com/watch?v=LqtGI_iaqj0&t=1s

NOTE:if error regarding mutables mappingg while executing the code then please use below command to fix it.

sed -i 's/collections.MutableMapping/collections.abc.MutableMapping/' /usr/local/lib/python3.11/dist-packages/dronekit/__init__.py

This command is used to replace deprecated collections.MutableMapping with collections.abc.MutableMapping in the dronekit package for Python 3.11 compatibility.

