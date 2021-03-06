- [x] basic stack (flask-redis)
- [x] add plivo SDK based scripts
- [x] wercker-integrated builds / tests
- [x] landing page / web-page structures
- [x] integrate landing page, customer page and agent page using Jinja2
- [x] minimal functionalities to dial a number / SIP endpoint
- [x] skeleton of all the functionalities in run.py
- [x] plivo dashboard
  - [x] buy numbers
  - [x] add applications
  - [x] add SIP endpoints
  - [x] connect numbers to SIP endpoints
  - [x] test demo apps
    - [x] demo dial
    - [x] demo speak
    - [x] demo play 

- [x] heroku integration
  - [ ] redis based verified account

***

- [x] host on an instance (since no heroku verified account present)
- [x] add functionalities to call queue handling method
- [x] add agent login status models
- [x] associate datetime with userQueue in redis # NOT NEEDED
- [x] connect flask routes to SDK
- [x] Issue: User logged in, but when page refreshed, login dialogue appears (although in backend, the user is logged in).
- [x] Issue: customer login/logout affects agentReady status
- [x] Issue: when call is answered, the agentReady status isn't changed. So other calls ring for sometime, hear "welcome", get ringing tone and then it hangs up. Creates confusion.
- [ ] Issue: call queue doesn't support polling. Just being updated. Not being processed -- Use Call Transfer API

***

- [x] investigate busy / unavailable issue
- [x] investigate same SIP being called when different(UK/US) numbers dialed
  - [x] use of fallback URL
  - [ ] use of an alternate tone (.ogg) file

***

- [x] test modules
  - [x] call receive 
  - [x] call dial
  - [x] call hold
  - [x] call hangup