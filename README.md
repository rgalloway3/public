# David Paper's Public Splunk Repository

Welcome! 

You'll find various dashboards and whitepapers that I've created for customers here. Feedback is always appreciated.

## Dashboards

* [Extended Search Reporting](). This dashboard looks at Search load in Splunk with a different lens than Monitoring Console. Included are 

  * Two takes on a search efficiency metric
  * Searches by frequency vs duration (easily find the search running every 5 mins that looks back 1 week)
  * Users who don't include the four default indexed fields in their search
  * Two takes on search duration, bucketing by time blocks and counts
  * Visualization of when searches are scheduled across the entire SH, per app and per user
  * Searches grouped by cron schedule type, sorted by name (easy to find searches that do almost the same thing by name and are ripe for consolidation)
  * Heavy weight dashboards that cause role search concurrency or disk and server-wide limits to be hit when loading

## Whitepapers

* [Disk Diagnosis: Digging Deep with Monitoring Console and More](https://github.com/dpaper-splunk/public/blob/master/whitepapers/Digging%20Deep%20into%20Disk%20Diagnoses.pdf). This whitepaper, also published at https://www.splunk.com/pdfs/technical-briefs/disk-diagnosis-digging-deep-with-monitoring-console-and-more.pdf, walks a Splunk admin through using the Monitoring Console and Linux CLI tools to closely observe disk performance to determine if a number of metrics are within an acceptable range. 

* [Splunk Upgrade Pre-, In-situ-, and Post- Validation Steps](https://github.com/dpaper-splunk/public/blob/master/whitepapers/Upgrade%20pre-%2C%20in-situ-%2C%20and%20post-%20validation%20steps.pdf). This whitepape provides specific checklists for items to review before, during and after Splunk Enterprise core upgrades to pave the way for a smooth upgrade. It does not provide specific upgrade procedures which will be customized to the environment, but takes a more holistic approach to answer the questions of "Am I good to go for an upgrade? How do I know an upgrade went successfully? What should I look for to compare before and after my upgrade?"
