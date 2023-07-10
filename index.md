---
layout: page
title: "GuidedTrack status"
---

*Here you can find out what's up with GuidedTrack. We aim to post an update
within fifteen minutes after the start of an incident. Please forgive us when
the wording is rough. We try not to panic, but when the machines go wild, we
don't have time polish our prose. If you have questions or comments, we invite
you to [join the GuidedTrack community
Slack](https://join.slack.com/t/guidedtrackworkspace/shared_invite/zt-1h6ft5ih3-caMIZqn6aEqJN1LZvqGaoA)
or email us at <hello@guidedtrack.com>.*

<!--
Colour emojis for quick copying:
🔴
🟡
🔵
-->

## 🟡 2023-07-10 12:08 UTC

The site is mostly behaving well. Only the pages that list answers to questions are slow or timing out. That's because we made a change to the database that had unforeseen side-effects. We've started the procedure that should repair the problem, but that's going to take up to an hour to complete.

## 🔵 2023-06-01 06:36 UTC

The site is behaving well again.

We thought we had gone through the steps to renew the SSL certificate, but for some reason, our provider was still configured with the old certificate, which expired. We'll figure out what went wrong and make sure it doesn't happen next time.

## 🔴 2023-06-01 01:41 UTC
The GuidedTrack website (including program pages) is not available due to some issues with our SSL certificate. We're working on it!

## 🔵 2023-05-23 16:40 UTC
The server is stable again.

## 🟡 2023-05-23 16:12 UTC
The server is having some trouble, which results in some programs data not being able to load or to sync their data, and possibly some timeouts. We suspect the connection with the database is poor at the moment but we're still investigating.

## 🔵 2023-05-11 17:30 UTC
The server is stable again.

## 🟡 2023-05-11 15:10 UTC
The server is having some trouble, which results in some programs data not being able to sync their data and possibly some timeouts. We suspect the connection with the database is poor at the moment but we're still investigating.

## 🔵 2023-03-12 01:07 UTC

The problem has resolved itself. I'll find out how to switch to the backup database in case this kind of problem escalates.

## 🟡 2023-03-12 00:07 UTC

The server is having some trouble, which is causing programs not to load and ‘no internet connection’ warnings. We're working on it.

What is happening is that a backend database has many cleanup operations running at once and those are slowing down everything else. Unfortunately, we don't have the level of access to the database (it's a SaaS) that would allow us to easily abort those cleanup operations.

## 🔵 2023-02-27 20:50 UTC

The site is behaving well again.

## 🟡 2023-02-27 15:23 UTC

The server is having some trouble, which is causing some programs to be unavailable. We're working on it.

## 🔵 2023-02-23 23:02 UTC

The site is behaving well again.

## 🟡 2023-02-23 22:29 UTC

The server is having some trouble, which probably affects a few users. We're working on it.

## 🔵 2023-01-19 09:50 UTC

The DNS problem appears to be fixed. Everything else continues to work normally.

## 🟡 2023-01-18 13:10 UTC

The server is up, but there seems to be a problem with DNS. When you type ‘guidedtrack.com’ in your browser, you might end up on a page that says: ‘guidedtrack.com is a totally awesome idea still being worked on. Check back later.’ Or it might seem to load forever. In either case, go to https://www.guidedtrack.com and it should work as usual. We're looking into restoring the previous behaviour.

## 🔵 2022-12-08 23:50 UTC

The site is behaving well. The problem from the previous entry still exists, but all the embedding pages it affects have been fixed. If you run into it, let us know and we'll help you fix your embedding pages.

## 🟡 2022-11-24 12:10 UTC

The site is behaving well, but there is a defect, which affects a few embedded programs (probably not yours).

If a program is embedded the old-fashioned way with a numerical ID –
```
<div class="guidedtrack program_container" id="1234">
```
– `*service` fails. We're thinking about how to address this. It's unlikely we'll fix it before Monday (28 Nov).

If your program is affected, you can work around the problem by replacing the numerical ID with the program key. How to find the program key? Go to
```
https://www.guidedtrack.com/programs/<numerical ID>/
```
and click on Preview. Now you can copy the program ID from the URL your browser has navigated to, which is in this format:
```
https://www.guidedtrack.com/programs/<program key>/preview
```

## 🔵 2022-10-25 07:24 UTC

The site is behaving well. Traffic from the study appears to have subsided.

## 🟡 2022-10-10 17:21 UTC

We've unpaused the study. We're monitoring our systems, ready to react if the additional traffic starts to affect performance.

## 🟡 2022-10-10 16:18 UTC

The site is experiencing some performance issues due to a large study, which has been paused.

## 🔵 2022-10-10 22:15 UTC

The site is behaving well. The defect described in the entry from 2022-10-08 is fixed.

## 🟡 2022-10-10 02:36 UTC

The site is behaving well. We have fix for the defect described in the last entry, but not released it yet.

This status site is now available at <https://status.guidedtrack.com>.

## 🟡 2022-10-08 10:08 UTC

The site is behaving well, but there is a defect, which program authors are noticing.

Currently the first Preview, Split or run after changing a program fails. It says: ‘Sorry, something went wrong.’ We've found the reason and are going to deploy a fix by Monday for the latest.

You can **work around the problem** by clicking Preview/Split a second time or refreshing the run page. From then on it works until the program is changed again.

We don't log all defects on this site. But this one is affecting all active program authors.

## 🔵 2022-10-07 20:44 UTC

New Relic now reports their service has come back to normal. This means GuidedTrack systems are working as expected.

## 🟡 2022-10-07 18:37 UTC

GuidedTrack is operating well, but our monitoring infrastructure, provided by New Relic, is experiencing service interruptions. This shouldn't directly affect GuidedTrack, but it prevents our team from investigating performance issues, should they arise.

As long as we don't experience a sudden spike in traffic, the site should work fine.

More insight into the incident on New Relic's side here: [status.newrelic.com](https://status.newrelic.com)

## 🔵 2022-10-07 11:46 UTC

The site is behaving well.

The status site (= what you're looking at) should also look as before and show https://guidedtrack.github.io/gtstatus in the address bar. Richard is done trying DNS settings.

## 🟡 2022-10-07 09:17 UTC

The site is behaving well.

If you're wondering why you ended up on status.littlepluses.com when opening this page: Richard is trying out some DNS settings so that he can give the person who takes care of the GuidedTrack DNS precise instructions on how to set up status.guidedtrack.com.

## 🟡 → 🔵 2022-10-07 22:08 UTC

The site was unstable for five minutes after I changed the configuration and restarted the server. Now it is behaving well again. We're working on something to make server restarts less disruptive.

## 🔵 2022-10-06 09:39 UTC

We've reduced the number of resources back to the usual amount. The site is behaving well.

## 🔵 2022-10-06 02:01 UTC

The servers are running fine.

We're planning to change how much resources are allocated to the site between
06:00 and 07:00 UTC. If you notice anything more than a few glitches, please let
us know. Of course, we'll be watching the site's performance, too.
