# -*- coding: utf-8 -*-
"""
@author: apera
"""

import paho.mqtt.client as paho

broker="broker.hivemq.com"
port=1883

def on_publish(client,userdata,result):                                 
    print("OK DATA\n")
    pass

co = 5000
client1 = paho.Client("PC")                             
client1.on_publish = on_publish                                         
client1.connect(broker,port)                                            
ret= client1.publish("",co)                     


