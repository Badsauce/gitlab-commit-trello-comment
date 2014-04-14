# Introduction

gitlab-commit-trello-comment will monitor your gitlab commit with card number(like #234) and push a format comment to that card of your trello board.

# License

gitlab-commit-trello-comment is released under the [GPL v2](http://www.gnu.org/licenses/gpl-2.0.html).

# Documentation

(1) Modify the script
---------------------

Copy the config.py.sample to config and fill your gitlab and trello info:

Trello Key can be found [here](https://trello.com/1/appKey/generate)

Trello Token can be generated using ` https://trello.com/1/authorize?key=substitutewithyourapplicationkey&scope=read%2Cwrite&name=My+Application&expiration=never&response_type=token `

(2) create the gitlab webhook
-----------------------------

In gitlab, as admin, go to "Hooks" tab, create hook as: http://your.ip.goes.here:port 

(3) Run The App With a WSGI Server
-----------------------------

(4) Format your commit
-----------------------------

When you commit to your gitlab repo include `#<card number>` ex. `#3` to push the commit to that trello card

# Trouble getting it working?

Let me know what's happening and I'll try to help. Email me at ninjazoby@gmail.com

