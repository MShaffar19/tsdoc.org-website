---
layout: page
title: '@deprecated'
navigation_source: docs_nav
---

| Standardization: | [Core]({% link pages/spec/standardization_groups.md %}) |
| Syntax kind: | [Block tag]({% link pages/spec/tag_kinds.md %}) |


## Usage

This block tag communicates that an API item is no longer supported and may be removed in a future release.
The `@deprecated` tag is followed by a sentence describing the recommended alternative.  It recursively applies
to members of the container.  For example, if a class is deprecated, then so are all of its members.
