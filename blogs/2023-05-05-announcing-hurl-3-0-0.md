---
title: "Announcing Hurl 3.0.0"
url: "https://hurl.dev/blog/2023/05/05/announcing-hurl-3.0.0.html"
date: "2023-05-05"
feed_url: "https://hurl.dev/blog/feed.xml"
---
Announcing Hurl 3.0.0 May. 06, 2023 The Hurl team is happy to announce Hurl 3.0.0 ! Hurl is a command line tool powered by curl , that runs HTTP requests defined in a simple plain text format: GET https://example.org/api/tests/4567 HTTP 200 [Asserts] header "x-foo" contains "bar" certificate "Expire-Date" daysAfterNow > 15 jsonpath "$.status" == "RUNNING" # Check the status code jsonpath "$.tests" count == 25 # Check the number of items jsonpath "$.id" matches /\d{4}/ # Check the format of the id What’s new in this release: Checking SSL Attributes (Expiration Date, Issuer, etc...) Working with
