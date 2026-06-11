---
title: "Grassroots Data Architecture"
date: 2024-01-06
tags: ["data architecture", "cloud"]
---

In public education most data operations are shaped by federal, state, or district reporting requirements. That is often a burden, but it also imposes a kind of order. Independent school systems face oversight but lack the structured accountability mechanisms that have shaped public education's data infrastructure over the last 15-20 years.

One independent school system was getting strong output from talented people, but those people spent much of their energy tracking down where individual data sources lived and what was in them, a consequence of years of underinvestment in the broader technology stack. With no external body dictating how data should be collected, each campus and business unit had built its own bespoke tools and methods, and integration happened manually whenever a specific need arose. Nothing forced the pieces to fit together.

I helped make the case for a lakehouse structure in Databricks that they implemented. The goal wasn't to force standardization for its own sake, but to give teams a shared platform they could integrate into when collaboration made sense and work independently from when it didn't. The structure supports both modes rather than insisting on one, and is far more secure than teams emailing spreadsheets to one another.

Without a mandate to standardize, the right move isn't to manufacture one. It's to build something flexible enough that teams choose to come together when it actually helps.