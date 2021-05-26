# Efficient Middle-level Interfaces for Operating Systems

### What is EMIOS?
EMIOS is a project aimed at providing a standard set of operating system protocols and interfaces mostly building upon the POSIX standard, while replacing obsolete parts.

### How do I contribute?
First and foremost, fork and talk; this material is licensed under CC-BY-SA 4.0. You may want to contact your favorite open-source projects and see their opinion on EMIOS. There are also some TODOs which are simpler to work through for this document, as well as preparatory work for sorting through further contributions.

After these steps are done (basic TODOs are done and the ideas behind EMIOS have been discussed somewhat), I (the original author) expect a working group to self-assemble; improvements and modifications based on external feedback should be submitted to this working group, which will be reviewed and merged into this document (until the group is formed, I will try to review and merge suggestions).

Finally, someone will have to implement the interfaces and ideas from this document into your favorite software. If the software is open-source, you may want to implement them yourself.

Of course, for those who have plenty of time to spare, implementing prototypes for the interfaces in this document, so that the quality of the interfaces can be practically assessed, is very welcome, too.

## Supplemental information

### Filesystem Hierarchy

There have been various views on the everything-is-a-file concept of UNIX/POSIX (from Redox to Plan 9). This document has tried to be accepting of such views; using the terminology "resource" for UNIX/Plan 9 "files" or Redox URIs/URLs.

In particular, the view of this document is that it is important both to provide a unified interface to resources, as well as ensure that resources are semantically correct.

### Related materials

* [POSIX is out of date](http://pl.atyp.us/2016-05-updating-posix.html)
* [Good-to-haves in build systems](http://www.csl.sri.com/users/gehani/papers/FMICS-2018.Wholly.pdf)
* [phk's take on Cathedral & Bazaar](https://queue.acm.org/detail.cfm?id=2349257)
* [Systems software research is irrelevant](http://doc.cat-v.org/bell_labs/utah2000/)
* [UNIX style or cat -v considered harmful](http://harmful.cat-v.org/cat-v/)
* [Structural regular expressions](http://doc.cat-v.org/bell_labs/structural_regexps/)
* [Witchcraft Compiler Collection](https://github.com/endrazine/wcc)
* [Notty](https://github.com/withoutboats/notty)