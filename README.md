# RSS Validator

A web application and command-line utility for validating RSS documents.

## Why does this project exist?

The World Wide Web Consortium (W3C) maintains an RSS feed validation service (https://validator.w3.org/feed). rss-validator is a web application and command-line utility written in Go that mirrors the functionality provided by this service. In addition, rss-validator utilizes [github.com/nickolashkraus/rss](https://github.com/nickolashkraus/rss), a Go library for marshaling, unmarshaling, and validating RSS documents.

## TODO
- [ ] Create rss-validator website (rss-validator.com)
  * See:
    * w3c/feedvalidator/css
    * w3c/feedvalidator/docs
    * w3c/feedvalidator/docs-xml
  - [ ] Add ability to *Validate by URI*
  - [ ] Add ability to *Validate by direct input*
