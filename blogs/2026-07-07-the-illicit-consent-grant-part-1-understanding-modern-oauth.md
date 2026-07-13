---
title: "The Illicit Consent Grant Part 1: Understanding Modern OAuth Consent Phishing"
url: "https://slashid.dev/blog/illicit-consent-grant-part-1/"
date: "2026-07-07"
author: "SlashID Team, Vincenzo Iozzo"
feed_url: "https://www.slashid.dev/blog/rss.xml"
---
An illicit consent grant abuses OAuth 2.0's delegated authorization model: instead of stealing who you are, the attacker steals what you can do. There is no software bug to patch, and the attack sails past MFA because it intercepts authorization, not authentication. This post breaks down why consent phishing works and evades detection, walks through the three-move attack chain from lure to token, and dissects the CoPhish case study that weaponizes Microsoft Copilot Studio — then shows how SlashID defends before, during, and after the grant.
