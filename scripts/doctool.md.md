*This file is automatically generated from [`doctool.md`](doctool.md).*

This is a block comment.  The parser strips the sequence,
[optional whitespace, `*`, optional single space] from
every line that has it.

For lines that don't, no big deal.

    Leading whitspace will be preserved here.

We can create a bullet list in here:

* This is a bullet


Single-line block comments are also ok.

A block comment whose first line doesn't have a `*` receives
no stripping of `*` characters on any line.

* This is a bullet



A triple-slash comment starts with `///` followed by an
optional space (i.e. one space is removed if present).
Multiple consecutive lines that start with `///` are
treated together as a single doc comment.

Separate doc comments get separate paragraphs.