---
title: "Hurl 4.2.0, the HTTP/3 Edition"
url: "https://hurl.dev/blog/2024/01/12/hurl-4.2.0-the-http3-edition.html"
date: "2024-01-12"
feed_url: "https://hurl.dev/blog/feed.xml"
---
Hurl 4.2.0, the HTTP/3 Edition Jan. 12, 2024 The Hurl team is thrilled to announce Hurl 4.2.0 ! Hurl is a command line tool powered by curl , that runs HTTP requests defined in a simple plain text format: GET https://example.org/api/tests/4567 HTTP 200 [Asserts] header "x-foo" contains "bar" certificate "Expire-Date" daysAfterNow > 15 jsonpath "$.status" == "RUNNING" # Check the status code jsonpath "$.tests" count == 25 # Check the number of items jsonpath "$.id" matches /\d{4}/ # Check the format of the id What’s New in This Release HTTP/3 Support Install With conda-forge Save Response per R
