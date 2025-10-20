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
## 🔵 2025-10-20 17:49 UTC
The AWS outage appears to be resolved, and our services are now back online. We will continue to monitor the situation closely to ensure full stability before marking it completely safe.

## 🔴 2025-10-20 14:54 UTC
A major outage is currently affecting AWS infrastructure, which in turn is impacting our services. We are closely monitoring the situation and will provide updates as soon as there are any.

## 🔵 2025-09-26 12:28 UTC

Maintenance is now complete – everything should be back to normal. Let us know if you see issues: hello@guidedtrack.com.

## 🟡 2025-09-26 12:17 UTC

Planned maintenance is now beginning. We will have to take GuidedTrack offline for ~15 minutes – expect disruptions in service.

## 🔵 2025-07-22 17:09 UTC

Maintenance completed successfully. All data should now be available.

All systems are currently functioning as expected.

## 🟡 2025-07-22 16:28 UTC

GuidedTrack's data pages need to undergo maintenance, during which data on the data pages and within CSV exports will be unavailable.

We expect maintenance to last no more than 1 hour.

## 🔵 2025-06-14 10:12 UTC

Maintenance completed successfully. All data should now be available.

All systems are currently functioning as expected.

## 🟡 2025-06-13 23:41 UTC

GuidedTrack's data pages need to undergo maintenance, during which data on the data pages and within CSV exports will be unavailable.

We expect maintenance to last around 20 hours.

## 🔵 2025-06-12 15:30 UTC

After 3 hours of monitoring we can confirm everything is functioning normally.

## 🔵 2025-06-12 12:33 UTC

GuidedTrack is back up and seems to be working as expected. We'll be monitoring it closely for the next few hours.

## 🟡 2025-06-12 12:31 UTC

We need to take GuidedTrack offline for maintenance. We don't expect the disruption to last more than a minute or two.

## 🔵 2025-03-04 00:49 UTC

GuidedTrack is fully functional again. The data pages came back online some hours ago.

## 🟡 2025-03-03 10:54 UTC

The data pages are unavailable because we're making changes to the database. Writing and running GuidedTrack programs is working as normal.

The data pages will probably come back online by 19:00 UTC. In the meantime you can still download any CSV by going to:

`https://www.guidedtrack.com/programs/<program ID>/csv`

## 🔵 2025-01-16 12:33 UTC

GuidedTrack is back online.

## 🟡 2025-01-16 12:25 UTC

GuidedTrack is offline for maintenance.

As part of our latest deploy, we need to perform a database migration which requires we take the app offline. We expect to be back soon.

## 🔵 2024-06-02 04:10 UTC

GuidedTrack is behaving well. We've installed a new SSL certificate.

## 🔴 2024-06-02 02:50 UTC

Our SSL certificate has expired. You won't be able to access GuidedTrack until it's renewed. We're working on it.

## 🔵 2024-05-07 09:13 UTC

GuidedTrack is behaving well. The infrastructure change appears to have gone almost without an issue.

## 🔵 2024-04-30 22:00 UTC

GuidedTrack is behaving well so far.

We're about to make an infrastructure change that will disrupt things if it goes wrong. It could have effects for a few days. If you find anything misbehaving, please email <hello@guidedtrack.com>.

## 🔵 2024-04-12 16:30 UTC

It looks like things are back to normal.

We've migrated everything to our new setup. Emails have been going out successfully for about a day and we haven't seen any further suspicious email activity.

We're working on improving our detection tools to make this sort of incident less likely in the future. We'll publish a postmortem once we've completed the most pressing tasks and had time to reflect. If you want to get our analysis, subscribe to our mailing list by sending an email to `~guidedtrack/releases+subscribe@lists.sr.ht`.

## 🟡 2024-04-11 22:00 UTC

We've set up a different IP address to send our email from and are now routing emails through it. It looks like email is being delivered successfully. We'll monitor things and start migrating settings.

## 🟡 2024-04-10 23:50 UTC

Emails from GuidedTrack programs are being held up by our email sending provider. So if you're testing a program and not getting email from it, that's why. We'll update this page once the problem resolves.

Everything else should be behaving normally.

## 🔵 2024-02-02 11:30 UTC

Everything is behaving normally again.

## 🔴 2024-02-02 10:40 UTC 

We are still looking for a way to bypass the index rebuilding operation. We are considering setting up a new server, so new runs can be started, but old ones will keep failing until the reindexing completes. 

## 🔴 2024-02-02 07:57 UTC 

What happened is that we caused an index rebuilding operation to start, which is blocking everything. The operation is going to take up to nine more hours to run. We're looking for a way to bypass it. If we find one, GuidedTrack is going to be available again sooner.

## 🔴 2024-02-02 02:15 UTC

Programs are not loading. We're looking into it.

## 🔵 2023-12-13 09:17 UTC

GuidedTrack is behaving well. The Q&A site, https://answers.guidedtrack.com/, is back, too.

## 🟡 2023-12-13 02:53 UTC

GuidedTrack is behaving well. The Q&A site, https://answers.guidedtrack.com/, is down. We'll look into it soon, but we don't consider it on fire since the site is rarely used, as far as we know.

## 🔵 2023-10-11 08:32 UTC

The site is behaving well. The CSV export should work for data of all sizes again.

## 🟡 2023-10-10 22:00 UTC

The site is mostly behaving well, but the CSV export is broken for large files (ie. anything that takes longer than 30 s to download). We're looking into it.

## 🔵 2023-09-22 00:00 UTC

The site is behaving well. http://guidedtrack.com is working again.

## 🟡 2023-09-21 22:30 UTC

The site is behaving well if you access it at https://www.guidedtrack.com. http://guidedtrack.com, which used to redirect to https://www.guidedtrack.com, has stopped working. We're looking into it.

## 🔵 2023-07-11 11:40 UTC

The site has been behaving well for a while. The repair is finished and probably the performance is the same as before.

## 🟡 2023-07-11 22:29 UTC

The site is mostly behaving well.
The repair procedure mentioned in the previous entries (automatic indexing operation) is *still* going on. All estimates were wrong.

## 🟡 2023-07-10 13:25 UTC

Amendment to the previous entry: It looks like it's going to take up to two hours.

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
