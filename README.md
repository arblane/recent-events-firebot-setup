#   recent events firebot setup

#   Description
Recent events that have occurred on stream for Firebot

#   Compatibility
- Firebot 5.64.0-nightly.25.02.18+

#   Install
+   Download the latest Release item or
    + RecentEvents.firebotsetup
    + recentEvents.html
+   Import the downloaded firebotsetup file
    +   You will need to edit the preset effect to change the location of where you want to store the html and text files. This will be handled via an import question.

#   Usage

##  Streamer Info
+   This setup is configured to utilize a timer (default 5 minutes) to show the recent events html segment on stream.
    +   Customize:
        +   Duration between showing recent events
        +   Duration to show the recent events
        +   Colors, fonts, position on screen, etc.
        +   Add the Preset Effect List to a start up event like Startup Firebot with the 'event' set to 'load' (without quotes) and 'value' set to nothing. This will allow Firebot to reload from local storage the recent events.
+   Background
    +   This setup currently utilizes persistence via individual text files.

##  Overlay
+   This firebotsetup makes use of the Firebot overlay
