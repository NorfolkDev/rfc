---
title: An RFC Schema
date: "2022-08-05"
author: Alex Scotton
type: Organisation
---

# Summary

Introduce a schema and process for handling RFCs within the community.

# Schema

This document represents the schema for a nor(DEV): RFC in some strange
self-propagating nature.

Updates to the schema will occur in subsequent RFCs if and when required.
An example of the current schema is [at the root of this repository](../RFC.md).
The document should then be referred to when proposing a new RFC.

[YAML front matter](https://assemble.io/docs/YAML-front-matter.html) should be
used to provide metadata for the RFC. The body of the RFC is currently open to
the author's discretion but should be used to explain the change desired.

```yml
---
title: An RFC
date: "2022-08-05"
author: An Author
type: <Organisation|Discord>
---
```

If the RFC proposal includes updates to features already tracked within this
repository, then the [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
should also include these changes when relevant or possible.

# Process

The process for accepting and implementing RFCs is:

1. Create Pull Request (or remove the draft status from the PR)
2. RFC is open for discussion
3. The RFC is merged and applied given:
  - All (upto a max of 5) colloborators have approved
4. The RFC is applied by the admin team and "merged"