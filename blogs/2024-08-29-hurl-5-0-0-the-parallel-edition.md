---
title: "Hurl 5.0.0, the Parallel Edition"
url: "https://hurl.dev/blog/2024/08/29/hurl-5.0.0-the-parallel-edition.html"
date: "2024-08-29"
feed_url: "https://hurl.dev/blog/feed.xml"
---
Hurl 5.0.0, the Parallel Edition Aug. 29, 2024 The Hurl team is thrilled to announce Hurl 5.0.0 ! Hurl is a command line tool powered by curl , that runs HTTP requests defined in a simple plain text format: GET https://example.org/api/tests/4567 HTTP 200 [Asserts] header "x-foo" contains "bar" certificate "Expire-Date" daysAfterNow > 15 jsonpath "$.status" == "RUNNING" # Check the status code jsonpath "$.tests" count == 25 # Check the number of items jsonpath "$.id" matches /\d{4}/ # Check the format of the id What’s New in This Release Run Tests in Parallel Better Error Display JSON Report Di
