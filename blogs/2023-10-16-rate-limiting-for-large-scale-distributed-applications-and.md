---
title: "Rate Limiting for Large-scale, Distributed Applications and APIs Using GCRA"
url: "https://slashid.dev/blog/id-based-rate-limiting/"
date: "2023-10-16"
author: "Paulo Costa, Vincenzo Iozzo"
feed_url: "https://www.slashid.dev/blog/rss.xml"
---
Rate limiting is a key defense against bots and threats for APIs and backends. Traditional IP-based rate limiting techniques are insufficient today because they can be easily bypassed. In this article, we discuss the state of the art when it comes to rate limiting and how we have implemented a modern, distributed, identity-based rate limiting plugin for Gate.
