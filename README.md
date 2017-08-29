#### Air Polution Text Alerts

Run in the Command Line by employing the typical sys.argv argument: 

`$ python air_polution_notification.py [zipcode] [phone #] [phoneprovider]` 

Command Line Argument should look something like this:

`$ python air_polution_notification.py 94127 5550001111 T-Mobile`

   Phone number should be 10 digits, not including 1 at the beginning, ex: 5550001111. 

Phone provider can be one of the following: ATT, T-Mobile, Verizon, Sprint, or metroPCS. 

You need sendmessages.py to run this

air_polution_notification.py runs great in conjunction with chronjob

