# PowerSpec-Ultra-Proxy
This is a simple proxy program that is designed to allow the users of the PowerSpec Ultra to print with flashprint over Wifi

This script is designed to run with python 2, it is possible to port it to python 3 however I have not found the need.

NOTE: This script is heavily based on a script provided in the book Black Hat Python by Justin Seitz ( ISBN-13: 978-1-59327-590-7 )

USAGE: python printerProxy.py [Local IP] [Local Port] [Remote IP] [Remote Port] [Send First (bool)]
EXAMPLE: python printerProxy.py 127.0.0.1 9000 10.12.132.1 9000 True
