+++
title = "Towards a Beautiful aiottp API: Part 1"
date = "2020-06-11"
author = "Platon Bibik"
authorTwitter = "" #do not include @
cover = ""
tags = ["python", "marshmallow", "aiohttp"]
keywords = ["python", "marshmallow", "aiohttp"]
description = "Having undefined JSON schemas in your APIs is a perpetual pain. This post shows example of using aiohttp features to provide automatic schema handling."
showFullContent = false
+++

We've stumbled upon a neccesity to automatically handle schema.

We did not want to use simple OpenAPI specs, we wanted to define everything in code. And then we found this lib:

<...>