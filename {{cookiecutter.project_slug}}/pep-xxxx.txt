PEP: XXX
Title: {{cookiecutter.pep_title}}
Version: $Revision$
Last-Modified: $Date$
Author: {{cookiecutter.pep_author}} <{{cookiecutter.pep_author_email}}>
BDFL-Delegate: <PEP czar's real name> (Optional)
Discussions-To: <email address> (Optional)
Status: Draft
Type: {{cookiecutter.pep_type}}
Content-Type: text/x-rst
Requires: <pep numbers> (Optional)
Created: {% now 'utc', '%d-%b-%Y' %}
Python-Version: <version number> (Optional)
Post-History: {% now 'utc', '%d-%b-%Y' %}
Replaces: <pep number> (Optional)
Superseded-By: <pep number> (Optional)
Resolution: <url> (Optional)


Abstract
========

A short (~200 word) description of the technical issue being addressed.  To
actually start writing your own PEP, please follow guidelines in PEP 1 [1]_
and PEP 12 [2]_


Specification
=============

The technical specification should describe the syntax and semantics of any
new language feature.  The specification should be detailed enough to allow
competing, interoperable implementations for at least the current major Python
platforms (CPython, Jython, IronPython, PyPy).


Motivation
==========

The motivation is critical for PEPs that want to change the Python language.
It should clearly explain why the existing language specification is
inadequate to address the problem that the PEP solves.  PEP submissions without
sufficient motivation may be rejected outright.


Rationale
=========

The rationale fleshes out the specification by describing what motivated the
design and why particular design decisions were made.  It should describe
alternate designs that were considered and related work, e.g. how the feature
is supported in other languages.

The rationale should provide evidence of consensus within the community and
discuss important objections or concerns raised during discussion.


Backwards Compatibility
=======================

All PEPs that introduce backwards incompatibilities must include a section
describing these incompatibilities and their severity.  The PEP must explain
how the author proposes to deal with these incompatibilities.  PEP submissions
without a sufficient backwards compatibility treatise may be rejected
outright.


Reference Implementation
========================

The reference implementation must be completed before any PEP is given status
"Final", but it need not be completed before the PEP is accepted.  While there
is merit to the approach of reaching consensus on the specification and
rationale before writing code, the principle of "rough consensus and running
code" is still useful when it comes to resolving many discussions of API
details.

The final implementation must include test code and documentation appropriate
for either the Python language reference or the standard library reference.


References
==========

.. [1] PEP 1, PEP Purpose and Guidelines, Warsaw, Hylton
   (http://www.python.org/dev/peps/pep-0001)

.. [2] PEP 12, Sample reStructuredText PEP Template, Goodger, Warsaw
   (http://www.python.org/dev/peps/pep-0012)


Copyright
=========

This document has been placed in the public domain.



..
   Local Variables:
   mode: indented-text
   indent-tabs-mode: nil
   sentence-end-double-space: t
   fill-column: 70
   coding: utf-8
   End:
