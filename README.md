# Comment_Explosion

A Twitter Bot that grabs the comments displayed on the frontpages of leading Swiss news sites, makes a list of them all, and has the highly sophisticated robot **com_expl** tweet out the most commented piece [here](https://twitter.com/com_expl) with the average of comments per article at exactly 0800, 1200, 1800 CET every day.

Sites that are currently considered:

* [20 Minuten](http://www.20min.ch)
* [Tages-Anzeiger](http://www.tagesanzeiger.ch)
* [Watson] (http://www.watson.ch)
* [Blick] (http://www.blick.ch)
* [20 Minutes](http://www.20min.ch/ro/) (These are considered separately)

Tweets for German language sites are posted at 800, 1200 and 1800 CET.
Tweets for French language at 830, 1230, 1830 CET.

## Update-Log:

0.1
* Dealt with Tagi-Comment-Int-Problem
* Using the site's Twitter handles

0.2
* Added Blick
* Now calculates the total comments (over all the site Frontpages) and returns the percentage of the top story.

0.3
* Added 20minutes
* Added Tweets in French

