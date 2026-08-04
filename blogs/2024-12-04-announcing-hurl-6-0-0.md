---
title: "Announcing Hurl 6.0.0"
url: "https://hurl.dev/blog/2024/12/04/announcing-hurl-6.0.0.html"
date: "2024-12-04"
feed_url: "https://hurl.dev/blog/feed.xml"
---
Announcing Hurl 6.0.0 Dec. 04, 2024 Christmas is early this year: the Hurl team is thrilled to announce Hurl 6.0.0 ! Hurl is a command line tool powered by curl , that runs HTTP requests defined in a simple plain text format: GET https://example.org/api/tests/4567 HTTP 200 [Asserts] header "x-foo" contains "bar" certificate "Expire-Date" daysAfterNow > 15 jsonpath "$.status" == "RUNNING" # Check the status code jsonpath "$.tests" count == 25 # Check the number of items jsonpath "$.id" matches /\d{4}/ # Check the format of the id What’s New in This Release Generating Dynamic Values with Functio
