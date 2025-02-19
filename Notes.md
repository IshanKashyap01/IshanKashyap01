# Commit Tags for Notes

## Add

New files are added (as maybe additional information) but do not represent a
new topic/feature

## Addendum

Additions to existing files

## Delete

Deletions to existing files

## Rename

Existing files are renamed

## Refactor

Files are internally unchanged but their locations are changed. This can include
renaming parent directories and/or rearranging files into new or existing directories

## Correction

Lines in existing files are changed; Corrections similar in nature should be grouped
in a single commit under this tag. For ex. spelling mistakes, logical mistakes, etc.

## Update

More than one type of change is made to existing files; An update should contain
a logical change made over file(s) that involves more than one of the above operations.
The individual changes referring to the above tags, if need be, can added to the
body.

## Finish

Marks the completion of the intent of a branch. A pull request for a topic branch
must not be accepted unless one of its commits has this tag. A topic branch is made
to add a topic. A branch made for any other purpose need not contain this tag to
be merged.

## Topic

A new topic is introduced to the master branch
