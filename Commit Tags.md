# Commit Message Tags

I have mainly two types of repositories: collection of notes from my studies,
and projects. These tags represents all possible types of commits but there's
no need to have all of them in a repo. Some are more granular while some are
more inclusive to suit all purposes.

## Common For All

### Add

New files are added (as maybe additional information) but do not represent a
new topic/feature

### Addendum

Additions to existing files

### Delete

Deletions to existing files

### Rename

Existing files are renamed

### Correction

Lines in existing files are changed; Corrections similar in nature should be grouped
in a single commit under this tag. For ex. spelling mistakes, logical mistakes, etc.

### Finish

Marks the completion of the intent of a branch. A pull request for a topic branch
must not be accepted unless one of its commits has this tag. A topic branch is made
to add a topic. A branch made for any other purpose need not contain this tag to
be merged.

## Specific For Projects

### Feature

A feature is merged into the integration branch

### Release

Marks a finished product ready for distribution and usage

### Task

A task is completed

### Refactor <!-- markdownlint-disable MD024 -->

Code structure is changed but the functionality remains the same. Include changes
made for readability as well.

### Test

Unit tests are added

### Stable

Marks a stable (runnable) version on the feature branch. This exist because some
commits in the feature branches may add incomplete code or have failing tests.

## Specific For Notes

### Topic

A new topic is introduced to the master branch

### Update

More than one type of change is made to existing files; An update should contain
a logical change made over file(s) that involves more than one of the above operations.
The individual changes referring to the above tags, if need be, can added to the
body.

### Refactor

Files are internally unchanged but their locations are changed. This can include
renaming parent directories and/or rearranging files into new or existing directories
