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
