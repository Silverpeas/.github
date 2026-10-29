# Security Policy

We take the security of Silverpeas seriously and thank everyone who helps us keep it safe by
reporting vulnerabilities responsibly.

## Supported Versions

Only the current stable minor version of Silverpeas is supported. Vulnerabilities are fixed only
on the branch of that version and on the master branch, and the fixes are shipped in the next
corrective release of that version. The versions prior to the current stable minor version don't
receive any fix.

| Version                                | Supported                       |
|----------------------------------------|---------------------------------|
| 6.4.x (current stable minor version)   | :white_check_mark:              |
| master (next version, in development)  | :white_check_mark:              |
| < 6.4                                  | :x:                             |

## Reporting a Vulnerability

**Please do not report a vulnerability through a public GitHub issue, a pull request, a forum or
any other public channel.**

You can report a vulnerability through either of the following channels:

1. **Our issue tracker** (preferred): open a ticket in the *Silverpeas Security* project of
   [https://tracker.silverpeas.org](https://tracker.silverpeas.org). An account is required: ask
   for one from the home page of the tracker and fill in the form. The requester must be
   identifiable; every piece of information is checked by the tracker managers and any request
   with incorrect information is rejected. Please note that the tracker isn't reachable from every
   country.
2. **GitHub private vulnerability reporting**: in the *Security* tab of the affected repository,
   click *Report a vulnerability*. Use this channel if you cannot reach our tracker. Your report
   stays private between you and the Silverpeas maintainers.

### What to include

Please report **one vulnerability per report**, with enough detail for us to reproduce it:

- the affected version(s) of Silverpeas and, if known, the affected component or source file;
- the steps or scenario(s) demonstrating the vulnerability, including any request, payload or
  configuration needed;
- the impact as you understand it (what an attacker gains, and with which privileges);
- any proof of concept. A video showing the exploitation of the vulnerability is welcome.

Incomplete reports, that we cannot reproduce, may be put on hold until more details are provided.

## How We Handle Reports

1. While we work on it, the report has the status *In progress*.
2. Once fixed, it is set to *Resolved*.
3. Once the fix is merged into both the branch of the current stable minor version and the master
   branch, it is set to *Closed*.
4. When the corrective release of Silverpeas including the fix is out, we add a note to the report
   to tell you so.

Please keep the vulnerability confidential until the corrective release is published.

## CVE

We let the reporters request and publish the CVE identifier themselves, once the corrective
release is out. Please mention the CVE identifier in your report afterward so that we can reference
it.
