# BugReportNotStoppingAtBreakpoints
This is my first library on GitHub!
This a little library was originally built to replicate a bug in Studio 8.1.4 where it doesn't stop properly at breakpoints.
It turns out the bug was due to a library preference $v3events which was set true.
In the current version of this library, $v3events is set false so the problem no longer occurs.
