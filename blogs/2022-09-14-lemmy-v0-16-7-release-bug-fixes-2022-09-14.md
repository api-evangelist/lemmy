---
title: "Lemmy v0.16.7 Release : Bug fixes (2022-09-14)"
url: "https://join-lemmy.org/news/2022-09-14-_Lemmy_Release_v0.16.7_-_Bug_fixes"
date: "2022-09-14"
feed_url: "https://join-lemmy.org/feed.xml"
---
Lemmy v0.16.7 Release : Bug fixes (2022-09-14) Written by @dessalines and @nutomic, 2022-09-14 A few bug fixes: Fix missing auth on new post refresh. ( #764 ) Change CSP rule for connect-src (websocket) to wildcard (fixes #730 ) ( #737 ) Increase default search rate limit. ( #2424 ) Rejected federated pm from blocked users (fixes #2398 ) ( #2408 ) Handle Like, Undo/Like activities from Mastodon, add tests (fixes #2378 ) ( #2380 ) Dont allow login if account is banned or deleted (fixes #2372 ) ( #2374 ) Fix panics in search_by_apub_id() (fixes #2371 ) ( #2373 )
