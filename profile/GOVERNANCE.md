# Hosting governance

## Why this repository is on elastocera

While internal hosting is unavailable, this codebase lives under the
[elastocera](https://github.com/elastocera) GitHub organization as a private
repository with controlled access. This is an interim arrangement, not the
long-term plan.

## What this means for the materials

The tools in this repository generate branded deliverables (PDF, AsciiDoc, 
Markdown). The deliverables themselves are produced at runtime, on the machine
of the user running the tool, against that user's own data.
Neither customer data nor pre-generated deliverables are stored in this
repository at any time.

The source code itself contains styling, layouts, and reference templates
that carry the company brand. That is the reason public hosting is not
acceptable today.

## Long-term direction

Two paths under consideration, not mutually exclusive:

1. Migrate to internal hosting whenever possible.
2. Remove company brand styling from the source so the generated
   deliverables are styling-neutral. With brand assets out, the repo
   becomes eligible for public OSS hosting.

Whichever path lands first determines the destination.

## Contact

For questions about the hosting arrangement: open an issue in this repository.