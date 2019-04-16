Module: Secure Protocols and Formal Verification (protocols)
===============================================================================

This is a learning module on Secure Protocols and Formal Verification.  Its aim 
is to give the students an understanding of what formal verification is, its 
uses and limitations in security.

*To contribute*, please [fork the repository][ForkARepo], make your changes, 
commit them and then create a [pull request][PullRequest] in the original 
repository.

[ForkARepo]: https://help.github.com/articles/fork-a-repo/
[PullRequest]: https://help.github.com/articles/using-pull-requests/

File Structure and Building
-------------------------------------------------------------------------------

*To build* the PDFs, after cloning the repository you must clone its required 
submodules:
```shell
$ git submodule update --recursive --init
```
Then you can go into the directory of interest and run `make`. The source files 
are structured as follows:

- `<name>.tex` contains the main content.
- `abstract.tex` is an abstract of the lecture, assignment, or similar, and 
  covers the required reading instructions, thus you can include these in a 
  study guide containing all reading instructions for the course.
- `<name>.bib` contains the bibliography entries, thus this file can be 
  included along with the reading instructions.

You can run `make all` in the root of the repository to recursively build 
everything.
