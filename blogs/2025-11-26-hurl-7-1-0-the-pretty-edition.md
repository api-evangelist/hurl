---
title: "Hurl 7.1.0, the Pretty Edition"
url: "https://hurl.dev/blog/2025/11/26/hurl-7.1.0-the-pretty-edition.html"
date: "2025-11-26"
feed_url: "https://hurl.dev/blog/feed.xml"
---
Hurl 7.1.0, the Pretty Edition Nov. 26, 2025 The Hurl team is thrilled to announce Hurl 7.1.0 ! Hurl is a command line tool powered by curl , that runs HTTP requests defined in a simple plain text format: GET https://example.org/api/tests/4567 HTTP 200 [Asserts] jsonpath "$.status" == "RUNNING" # Check the status code jsonpath "$.tests" count == 25 # Check the number of items jsonpath "$.id" matches /\d{4}/ # Check the format of the id # Some tests on the HTTP layer: GET https://example.org HTTP 200 [Asserts] header "x-foo" contains "bar" certificate "Expire-Date" daysAfterNow > 15 ip == "2001
