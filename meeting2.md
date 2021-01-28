---
title: Second Meeting, Friday November 13 2020
parent: Meeting Notes
has_children: true
nav_order: 2
---

# **Second Meeting: Friday, November 13⋅2:00 – 3:00pm UTC**

Unique IDs when generated automatically are typically hard to remember (see IP addresses <-> domain names).
These mappings from ID to name need to be stored somewhere. Here we discussed using github as a quick MVP implementation for storage of all the required metadata (e.g. block hashes, API endpoints for each chain etc). A simple daemon would be used to query blockchain nodes of the different cosmos networks and then save the processed information in a repository (called registry).
