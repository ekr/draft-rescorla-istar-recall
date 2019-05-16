---
title: Updated Recall Procedures for IETF Leadership
abbrev: New Recall
docname: draft-rescorla-istar-recall-latest
category: info

ipr: trust200902
area: General
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: "E. Rescorla"
    name: "Eric Rescorla"
    organization: "Mozilla"
    email: ekr@rtfm.com

 -
    ins: "M. StJohns"
    name: "Michael StJohns"
    organization: "Consultant"
    email: mstjohns@comcast.net

normative:
  RFC2119:

informative:



--- abstract

This document proposes a new set of recall procedures for members
of the IESG and IAB. Instead of a revised nomcom process, these
procedures are based on the body expelling their own members.


--- middle

# Introduction

Section 7 of {{!RFC7437}} describes a recall procedure for IAB and
IESG members. This procedure involves a petition from 20
nomcom-eligible community members followed by the formation of a
recall committee using procedures similar to those of the nomcom.
This procedure has never been executed, although in at least one case
the petition phase got fairly far before the relevant member resigned.

One might draw a number of conclusions here, including:

- There is very little need for any kind of recall, except in the
  most exceptional circumstances.

- The recall system is so unwieldy that it is undeployable even
  in the most egregious cases.

This document takes the position that while recalls should be relatively
rare, some mechanism is needed, but that the current mechanism is
not well-constructed, both because it is hard to initiate and because
it is slow (partly by design), with the result that it often seems
easier to just wait for the next nomcom cycle. In addition, because
of the stochastic nature of the nomcom, it is a potential source of
abuse by those wishing to relitigate the past nomcom.

This document proposes an alternate structure which is designed
to deal with just egregious cases (e.g., total member checkout,
major misconduct) but is also faster because it doesn't involve
spinning up the nomcom machinery (twice, once to recall and once
to replace). In this structure, the IAB/IESG would vote to
expel the offending member with consent from the other body.
The rationale here is that the body themselves is in the best
position to know when a member really needs to be removed.

The intent is that this be an alternative to the existing recall
procedure, thus preserving a community mechanism for removing
members.


# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.


# Expulsion Procedure

In this model, any formal member of either the IAB or the IESG,
with the exception of the IETF chair, may be expelled by that body.
Specifically, for the IESG, this means all area directors other than
the IETF chair and for the IAB this means all IAB members other than
the IETF chair, liaisons, and ex officio members.

The body MAY use any procedures of its choice to debate the issue, but
the final vote MUST be by a 2/3 majority of the formal members
other than the affected member. Prior to that vote, the member MUST
be notified and have an opportunity to provide a statement to be
considered by the voting members.

Members MAY appeal their expulsion to the body which would ordinarily
confirm nomcom appointments (the IAB for IESG members and the ISOC
Board of Trustees for IAB members). This appeal MUST be filed within
7 days or the expulsion becomes effective.

In case of an appeal, the body proposing the expulsion shall send a
note to the confirming body explaining its reasons for the expulsion.
The member being proposed for expulsion shall have access to that
statement and shall be allowed to submit a statement explaining why
the expulsion should not be sustained.  The member shall have 3
business days after receipt of the explusion statement to submit their
statement.

The confirming body shall complete their deliberations within one
calendar week of receiving the expulsion statement and response. If
the confirming body does not vote to confirm the expulsion by a 2/3 majority
by the end of this deadline, the expulsion shall not be sustained.

The contents of the statement on the reasons for expulsion shall be
held confidential by both bodies.  However, the member being proposed
for expulsion in their sole discretion, MAY make their statement
public.

Deliberations and votes by both bodies -- including the fact that
expulsion is being considered -- shall be private (and among only the
members voting) and only the fact of a successful vote yea shall be
reported publicly.  The number of votes for or against shall not be
reported.  If at any time the member resigns from the position prior
to the completion of an appeal, the fact of the expulsion process
shall not be reported.

Upon either the expiration of the appeal period or an affirmative
vote by the confirming body, the expulsion takes effect
immediately. At this point, their seat is treated as a mid-term
vacancy and handled according to Section 3.5 of {{RFC7437}}.

If an expulsion vote is taken and fails and/or an expulsion is not
sustained by the confirming body, no expulsion of that member may
be proposed for 6 months after the initiation of the proceedings.

The Chair of the IETF may not be removed by expulsion.

# Effectiveness Date

This process applies to members selected by Nomcoms after the
publication date of this document.


# Security Considerations

This document introduces a new mechanism for removing IAB and IESG
members, so is a potential way to suppress existing views. Supermajority
requirements and the possibility of appeal limits the impact of this.



# IANA Considerations

This document has no IANA actions.



--- back

