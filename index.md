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
