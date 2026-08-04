---
title: "Announcing Hurl 6.1.0"
url: "https://hurl.dev/blog/2025/03/14/announcing-hurl-6.1.0.html"
date: "2025-03-14"
feed_url: "https://hurl.dev/blog/feed.xml"
---
Announcing Hurl 6.1.0 Mar. 14, 2025 The Hurl team is thrilled to announce Hurl 6.1.0 ! Hurl is a command line tool powered by curl , that runs HTTP requests defined in a simple plain text format: GET https://example.org/api/tests/4567 HTTP 200 [Asserts] header "x-foo" contains "bar" certificate "Expire-Date" daysAfterNow > 15 ip == "2001:0db8:85a3:0000:0000:8a2e:0370:733" jsonpath "$.status" == "RUNNING" # Check the status code jsonpath "$.tests" count == 25 # Check the number of items jsonpath "$.id" matches /\d{4}/ # Check the format of the id What’s New in This Release Redacting Sensitive V
