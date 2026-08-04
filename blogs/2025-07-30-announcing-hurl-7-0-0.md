---
title: "Announcing Hurl 7.0.0"
url: "https://hurl.dev/blog/2025/07/30/announcing-hurl-7.0.0.html"
date: "2025-07-30"
feed_url: "https://hurl.dev/blog/feed.xml"
---
Announcing Hurl 7.0.0 Jul. 30, 2025 In this hot summer, the Hurl team is super happy to announce Hurl 7.0.0 ! Hurl is a command line tool powered by curl , that runs HTTP requests defined in a simple plain text format: GET https://example.org/api/tests/4567 HTTP 200 [Asserts] jsonpath "$.status" == "RUNNING" # Check the status code jsonpath "$.tests" count == 25 # Check the number of items jsonpath "$.id" matches /\d{4}/ # Check the format of the id # Some tests on the HTTP layer: header "x-foo" contains "bar" certificate "Expire-Date" daysAfterNow > 15 ip == "2001:0db8:85a3:0000:0000:8a2e:037
