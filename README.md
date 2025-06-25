# Web Crawler

This is a [guided project](https://www.boot.dev/courses/build-web-crawler-golang) I completed as a part of the Boot.dev back-end developer curriculum. The project is a web crawler that makes HTTP requests and parses HTML to generate reports on the amount of found internal links. This project focuses on CLI argument parsing, HTTP requests, and HTML parsing.

[![golang](https://badgen.net/badge/go/1.24/cyan?icon=https://go.dev/blog/go-brand/Go-Logo/SVG/Go-Logo_LightBlue.svg)](https://go.dev/)

## Features

- Fetches and parses HTML from a given URL
- Provides a report on the number of internal links found

## Usage

Go version 1.24 or higher is required to run this application, and `~/go/bin` should be in your PATH.

To install the application, run this command in your terminal:

```bash
go install github.com/kei-the-gae/web-crawler@latest
```

To run the application, use the following command:

```bash
web-crawler <baseURL> <maxConcurrency> <maxPages>
```

Where `baseURL` is the URL to start crawling from, `maxConcurrency` is the maximum number of concurrent requests, and `maxPages` is the maximum number of pages to crawl.
