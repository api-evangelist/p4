---
title: "Gigaflow: Pipeline-Aware Sub-Traversal Caching for Modern SmartNICs"
url: "https://p4.org/gigaflow-modern-smartnics/"
date: "2026-03-05"
author: "Roxanne Joncas"
feed_url: "https://p4.org/feed/"
---
Contributed by: Annus Zulfiqar, University of Michigan Challenge: Modern virtual switches cannot efficiently offload millions of dynamic wildcard rules to SmartNICs because hardware caches are too small, leading to high miss rates and costly software fallbacks. Solution: Gigaflow introduces pipeline-aware sub-traversal caching with Longest Traversal Matching (LTM), decomposing vSwitch pipeline traversals into reusable segments that maximize SmartNIC table utilization and significantly improve ca
