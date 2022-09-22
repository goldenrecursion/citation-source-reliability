# citation source reliability

The citation_source_reliability.yml file contains a non-exhaustive list of citation sources with their reliability status. Currently, we are only using the "blacklisted" reliability status to mark which sources cannot be used in citations for triples.

Each source has the following fields:
- regex: Regular expression for identifying the source URLs.
- status: Reliability status. The current supported values are:
  - blacklisted: Sources with this status cannot be used as citations.
