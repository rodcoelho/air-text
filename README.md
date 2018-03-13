 ### Air Polution Text Alerts
#### Requirements

- This is meant to be run in conjunction with Cron Tabs or Cron Jobs (recommended: run once every 24 hours, at 7am)
- Use latest version of Python 3
- Once you've cloned the repo, create a dummy gmail account to send emails from - don't use an email address you care about - The best option is 
to learn to use keyring or securely store your email and password.


#### Instructions 

1) `git clone https://github.com/rodcoelho/air-text.git`
2) In `sendmessages.py`, change the username and password to a dummy gmail account (non-personal). In the gmail account settings, disable security features that keep you from sending emails via the terminal.
3) Use Cron Tabs to re-run the following:


`$ python air_polution_notification.py [zipcode] [phone #] [phoneprovider]` 

Command Line Argument should look something like this:

`$ python air_polution_notification.py 94127 5550001111 T-Mobile`

Phone number should be 10 digits, not including 1 at the beginning, ex: 5550001111. 

Phone provider can be one of the following: ATT, T-Mobile, Verizon, Sprint, or metroPCS. 

