---
title: "Announcing Hurl 8.0.0"
url: "https://hurl.dev/blog/2026/04/27/announcing-hurl-8.0.0.html"
date: "2026-04-27"
feed_url: "https://hurl.dev/blog/feed.xml"
---
Announcing Hurl 8.0.0 Apr. 27, 2026 The Hurl team is thrilled to announce Hurl 8.0.0 ! Hurl is a command line tool powered by curl , that runs HTTP requests defined in a simple plain text format: GET https://example.org/api/tests/4567 HTTP 200 [Asserts] jsonpath "$.status" == "RUNNING" # Check the status code jsonpath "$.tests" count == 25 # Check the number of items jsonpath "$.id" matches /\d{4}/ # Check the format of the id POST https://example.org/api/tests { "name": "foo" } HTTP 201 [Asserts] header "x-foo" contains "bar" certificate "Expire-Date" daysAfterNow > 15 ip == "2001:0db8:85a3:0
