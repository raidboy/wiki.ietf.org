---
title: Changes to documents based upon modern language choices
description: When authors replace one term with a new term, this page records the choices that were made, why, and in which technology choice.
published: true
date: 2022-09-19T13:53:12.424Z
tags: 
editor: markdown
dateCreated: 2022-09-19T13:53:12.424Z
---

# Why

As of 09/2022 (and earlier), RFC authors are asked by RFC-editor the following question if the document under AUH48 review contains one or more of the words considered to be problematic according to NISTai:

[rfced] Please review the "Inclusive Language" portion of the online Style Guide <https://www.rfc-editor.org/styleguide/part2/#inclusive_language> and let us know if any changes are needed.

This wiki page serves to track terms for which this happened or could happen and suggestions how to change or not change terms involving this potentially problematic words.

# Glossary

NISTai - <https://www.nist.gov/nist-research-library/nist-technical-series-publications-author-instructions>

# Language Choices

|original term | replacement term | technology involved | Where used | Who |
|===
| native | built-in (suggested by NISTai) | "native" has been used in more than 800 RFC as an adjective for various nouns to create technical terms indicating some variant of the noun that typically is considered to be more original, intended, less-complex or otherwise preferred. | > 800 | Toerless Eckert |
| native IP multicast | NA | This term was introduced in the 1990'th by the industry as a marketing term to indicate an instance of IP multicast in a network where it does not use tunnels. At that time, the common method for IP multicast routing over the Internet where dedicated system attached as "router on a stick" to the IP network (such as Sun Workstations), running DVMRP {{RFC1075}} as the IP multicast routing protocol. Native IP multicast in contrast was used to indicate the use of IP multicast routing protocols on the routers of that IP network itself, preferrably using protocols such as PIM-SM ({{RFC2362}}). | ?. Do not replace when used to describe the type of IP multicast deployment in a historical context, but consider introducing new terms, such as "underlay IP multicast" if the term "underlay has been defined in the context of the document accordingly |  {{RFC2764}}, {{RFC3941}}, {{RFC5401}}, {{RFC8313}}, but also > 9,000 matches on google | Toerless Eckert |
| | underlay | | | Toerless Eckert |

# HOWTO

This page uses markdown format. See <https://www.markdownguide.org/basic-syntax/>

