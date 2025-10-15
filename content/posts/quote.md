---
title: "Quote"
date: 2025-04-17
draft: false
categories: ["journal"]
weight: 2
---

{{ $quotes := .Site.Data.daily_quotes.quotes }}
{{ $start := (date "2025-10-15" "2025-10-15") }} # Start date is October 15, 2025
{{ $daysSinceStart := (sub (now.Unix) ($start.Unix)) | div 86400 }} # Days since start date
{{ $index := mod $daysSinceStart (len $quotes) }} # Calculate index
{{ $quote := index $quotes $index }}

### Today's Quote
> {{ $quote }}
