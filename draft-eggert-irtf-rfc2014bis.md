---
title: IRTF Research Group Guidelines and Procedures
abbrev: IRTF Research Group Guidelines
docname: draft-eggert-irtf-rfc2014bis-latest
category: info

ipr: trust200902
area: IRTF
obsoletes: 2014
workgroup: Internet Research Task Force (IRTF)

stand_alone: yes
pi: [toc, sortrefs, symrefs, docmapping]

author:
    ins: L. Eggert
    name: Lars Eggert
    org: NetApp
    email: lars@netapp.com
    uri: https://eggert.org/

informative:
    IRTF-RFCs:
        title: IRTF RFC Process
        author:
            org: IRTF
        target: http://trac.tools.ietf.org/group/irtf/trac/wiki/IRTF-RFCs

    IRTFOPEN:
        title: IRTF Open Meeting
        author:
            org: IRTF
        target: https://datatracker.ietf.org/group/irtfopen/about/

    IRTF-DISCUSS:
        title: IRTF General and New-Work Discussion List
        author:
            org: IRTF
        target: https://www.irtf.org/mailman/listinfo/irtf-discuss

    IAB:
        title: Internet Architecture Board Description
        author:
            org: IAB
        target: https://www.iab.org/about/description/


--- abstract

The Internet Research Task Force (IRTF) has responsibility for organizing groups
to investigate research topics related to the Internet protocols, applications,
and technology. IRTF activities are organized into Research Groups. This
document describes the guidelines and procedures for formation and operation of
IRTF Research Groups. It describes the relationship between IRTF participants,
Research Groups, the Internet Research Steering Group (IRSG) and the Internet
Architecture Board (IAB). The basic duties of IRTF participants, including the
IRTF Chair, Research Group Chairs and IRSG members are defined.

This document obsoletes RFC2014.


--- middle

# Introduction

This document defines guidelines and procedures for Internet Research Task Force
(IRTF) Research Groups. It obsoletes {{!RFC2014}}, which originally documented
them. The IRTF focuses on longer term research issues related to the Internet,
while its parallel organization, the Internet Engineering Task Force (IETF),
focuses on shorter term issues of engineering and standards making.

The IRTF is composed of a number of focused, long-term, small Research Groups.
These groups work on topics related to Internet protocols, applications,
architecture and technology. Research Groups are expected to have the stable,
long-term membership needed to promote the development of research collaboration
and teamwork in exploring research issues. Participation is by individual
contributors, rather than by representatives of organizations.

The IRTF is managed by the IRTF Chair in consultation with the Internet Research
Steering Group (IRSG). The IRSG membership includes the IRTF Chair, the chairs
of the various Research Groups and possibly other individuals
("members-at-large") from the research community.

The IRTF Chair is appointed by the Internet Architecture Board (IAB)
{{?RFC2850}}{{IAB}}, the Research Group chairs are appointed as part of the
formation of Research Groups (as detailed below) and the IRSG members-at-large
are chosen by the IRTF Chair in consultation with the rest of the IRSG and on
approval by the IAB.

In addition to managing the Research Groups, the IRSG MAY from time to time hold
topical workshops focusing on research areas of importance to the evolution of
the Internet, or more general workshops to, for example, discuss research
priorities from an Internet perspective.

This document defines procedures and guidelines for the formation and operation
of Research Groups in the IRTF. The duties of the IRTF Chair, the Research Group
Chairs and IRSG members are also described; the first is also described in more
detail in {{?RFC7827}}.  Except for members-at-large of the IRSG, there is no
general participation in the IRTF, only participation in a specific Research
Group. However, since around 2010, the IRTF has begun to hold "open meetings"
during IETF meetings {{IRTFOPEN}}, and a mailing list was created for discussion
of IRTF-wide topics {{IRTF-DISCUSS}}, both allowing the community to engage with
the IRTF.

{{?RFC4440}} provides additional important background information that the
readers of this document should familiarize themselves with. {{?RFC7418}}
provides an introduction to the IRTF for IETF participants, focusing on the
differences between the two organizations.

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be
interpreted as described in {{!RFC2119}}.


## IRTF Approach

The reader is encouraged to study The Internet Standards Process {{!RFC2026}} to
gain a complete understanding of the philosophy, procedures and guidelines of
the IETF and its approach to standards making.

The IRTF does not set standards, and thus has somewhat different and
complementary philosophy and procedures. In particular, an IRTF Research Group
is expected to be long-lived, producing a sequence of "products" over time. The
products of a Research Group (often abbreviated as "RG") are research results
that may be disseminated by publication in scholarly journals and conferences,
as white papers for the community, as Informational RFCs, and so on. In
addition, it is expected that any concrete technologies developed in a Research
Group will be brought to the IETF as input to IETF Working Group(s) or in the
form of birds-of-a-feather (BoF) sessions for possible standardization. However,
Research Group input carries no more weight than other community input, and goes
through the same standards setting process as any other proposal.

IRTF Research Groups are formed to encourage research in areas of importance to
the evolution of the Internet. Clearly, anyone may conduct such research,
whether or not they are members of a Research Group. The expectation is that by
sponsoring Research Groups, the IRTF can foster cross-organizational
collaboration, help to create "critical mass" in important research areas, and
add to the visibility and impact of the work.

IRTF Research Groups may have open or closed memberships. Limited membership may
be advantageous to the formation of the long term working relationships that are
critical to successful collaborative research. However, limited membership MUST
be used with care and sensitivity to avoid unnecessary fragmentation of the work
of the research community. Allowing limited membership is in stark contrast to
IETF Working Groups, which are always open; this contrast reflects the different
goals and environments of the two organizations -- research vs. standards
setting.

To ameliorate the effects of closed membership, all Research Groups are REQUIRED
to regularly report progress to the community, and are encouraged to hold
occasional open meetings (most likely co-located with IETF meetings). In
addition, the IRTF may host open plenaries at regular IETF meetings during which
research results of interest to the community are presented. Finally, multiple
Research Groups working in the same general area may be formed, if appropriate.

Even more than the IETF, the work of the IRSG is expected to be marked by
informality. The goal is to encourage and foster valuable research, not to add
burdensome bureaucracy to the endeavor.


## IRTF and Intellectual Property Rights

The IRTF follows the IETF Intellectual Property Rights (IPR) disclosure rules,
as described in Section 3.2 of {{?RFC5743}}. This is a summary of these rules as
they relate to IRTF research group discussions, mailing lists and Internet
Drafts:

* If a participant includes their own or their employer's IPR in a contribution
  to an IRTF research group, then they must file an IPR disclosure with the
  IETF.

* If a participant recognizes their own or their employer's IPR in someone
  else's contribution and they are participating in the discussions in the
  research group relating to that contribution, then they must file an IPR
  disclosure with the IETF. Even if they are not participating in the
  discussion, the IRTF still requests that they file an IPR disclosure with the
  IETF.

* Finally, the IRTF requests that a participant file an IPR disclosure with the
  IETF if they recognize IPR owned by others in any IRTF contribution.

Participants may file an IPR disclosure here:
http://www.ietf.org/ipr/file-disclosure

See {{!RFC8179}} for definitions of "IPR" and "contribution" and for the
detailed rules (substituting "IRTF" for "IETF").


# Research Group Formation

Research Groups are the activity centers in the IRTF. A Research Group is
typically created to address a research area related to Internet protocols,
applications, architecture or technology area. Research Groups have the stable,
long-term membership needed to promote the development of research collaboration
and teamwork in exploring research issues. Participation is by individual
contributors, rather than by representatives of organizations.

A Research Group may be established at the initiative of an individual or group
of individuals. Anyone interested in creating an IRTF Research Group MUST submit
a charter for the proposed group to the IRTF Chair along with a list of proposed
founding members. The charter SHALL be reviewed by the IRSG and then forwarded
to the IAB for approval. If approved, the charter is placed on the IRTF Web
site.

This process allows the IRTF Chair considerable freedom in how to decide to
charter new work, and different approaches have been tried. One approach seems
to have worked well recently, and is therefore briefly described here as an
example: Under this approach, the IRTF Chair permits the proponents of new
Research Groups to start a mailing list under the irtf.org domain, schedule
meetings during IETF weeks and elsewhere for their new group, and otherwise act
as if they were already formally chartered. These RGs are referred to as
"Proposed RGs" in the IETF Datatracker, on the meeting agenda, etc. and while
they often create a wiki page for themselves, their charter is not posted on the
IRTF web site, in order to distinguish them from officially chartered RGs. After
roughly a year, the IRTF Chair reviews the progress, activity levels and general
operation of the Proposed RG, and decides to formally charter or abandon the
effort.



## Criteria for Formation

In determining whether it is appropriate to create a Research Group, the IRTF
Chair, the IRSG and the IAB SHALL consider several issues:

* Is the research area that the Research Group plans to address clear and
  relevant for the Internet community?

* Will the formation of the Research Group foster work that would not be done
  otherwise? For instance, membership drawn from more than a single institution,
  more than a single country, and so on, is to be encouraged.

* Do the Research Group's activities overlap with those of another Research
  Group? If so, it may still be appropriate to create the Research Group, but
  this question must be considered carefully since subdividing efforts often
  dilutes the available technical expertise.

* Is there sufficient interest and expertise in the Research Group's topic with
  at least several people willing to expend the effort that is likely to produce
  significant results over time? Research Groups require considerable effort,
  including management of the Research Group process, editing of Research Group
  documents, and contribution to the document text.

The Internet Architecture Board (IAB) SHALL also review the charter of the
proposed Research Group to determine the relationship of the proposed work to
the overall architecture of the Internet Protocol Suite.


## Charter

A charter is a contract between a Research Group and the IRTF to conduct
research in the designated area. Charters MAY be renegotiated periodically to
reflect changes to the current status, organization or goals of the Research
Group.

The formation of a Research Group requires a charter, which is initially
negotiated between a prospective Research Group Chair and the IRTF Chair. When
the prospective Chair and the IRTF Chair are satisfied with the charter form and
content, it becomes the basis for forming a Research Group.

A IRTF Research Group charter consists of five sections:

1. Research Group Name

   A Research Group name SHOULD be reasonably descriptive or identifiable.
   Additionally, the group SHALL define a short acronym (consisting of printable
   US-ASCII characters) to reference the group in the IRTF directories, mailing
   lists, and general documents. The name and acronym MUST NOT conflict with any
   past or existing IETF or IRTF names and acronyms. It is helpful if the
   acronym ends with "RG", to help distinguish Research Groups from IETF Working
   Groups.

2. Chair(s)

   The Research Group may have a small number of Chair(s) to perform the
   administrative functions of the group. The email address(es) of the Chair(s)
   SHALL be included.

3. Mailing list(s)

   Each Research Group SHALL have an address (possibly a Chair's) for members of
   the Internet community to send queries regarding the Research Group. For
   instance, for requests to join the group.

   A Research Group, whether limited-membership or open, SHALL have an Internet
   mailing list open to all interested parties. This list is used for an open
   discussion of the issues and announcements of results as they become
   available. Included SHOULD be the address to which an interested party sends
   a subscription request for the interest list and the procedures to follow
   when subscribing, and the location of the interest mailing list archive. It
   is RECOMMENDED that this mailing list be hosted under the irtf.org domain, so
   its archive will remain available in the future.

   It is expected that a limited-membership Research Group MAY also have a
   mailing list limited to the regular meeting participants on which substantial
   part of the work of a Research Group is likely to be conducted via e-mail.

4. Membership Policy

   The Charter MUST define the membership policy (whether open or limited), and
   the procedure to apply for membership in the group. While limited membership
   is permitted, it is in no way encouraged or required.

5. Description of Research Group

   The focus and intent of the group SHALL be set forth briefly. By reading this
   section alone, an individual should be able to decide whether this group is
   relevant to their own work. The first paragraph SHOULD give a brief summary
   of the research area, basis, goal(s) and approach(es) planned for the
   Research Group. This paragraph will frequently be used as an overview of the
   Research Group's effort.

   To facilitate evaluation of the intended work and to provide on-going
   guidance to the Research Group, the charter SHALL describe the proposed
   research and SHALL discuss objectives and expected impact with respect to the
   Internet Architecture.


# Research Group Operation

Research Groups are autonomous and each determines most of the details of its
own operation with respect to session participation, reaching closure, norms of
behavior, etc. Since the products are research results, not Internet standards,
consensus of the group is not required. Rather, the measure of success is the
quality and impact of the research results.

A number of procedural questions and issues will arise over time, and it is the
function of the Research Group Chairs to manage the group process, keeping in
mind that the overall purpose of the group is to make progress towards realizing
the Research Group's goals and objectives.

There are few hard and fast rules on organizing or conducting Research Group
activities, but a set of guidelines and practices have evolved over time that
have proven successful. These are listed here, with actual choices typically
determined by the Research Group members and a Chair.


## Meeting Planning {#mtgplan}

For coordinated, structured Research Group interactions, a Chair MUST publish to
the group mailing list a draft agenda well in advance of the actual meeting. The
agenda needs to contain at least:

* The items for discussion;

* The estimated time necessary per item; and

* A clear indication of what documents the participants will need to read before
  the meeting in order to be well prepared.

A Research Group will conduct much of its business via its electronic mail
distribution list(s). It is also likely to meet periodically to accomplish those
things that are better achieved in more interactive meetings, such as
brainstorming, heated altercations, etc. Meetings MAY be scheduled as telephone
conference, video teleconference, or face-to-face (physical) meetings.

It is REQUIRED that all Research Group meetings be recorded in written minutes,
to keep informed members who were not present and the community at large and to
document the proceedings for present and future members. These minutes SHOULD
include the agenda for the meeting, an account of the high points of the
discussion, and a list of attendees. Unless the Research Group chair decides
otherwise, the minutes SHOULD be sent to the interest list and made available
through other channels, e.g., the IETF proceedings web pages.


## Meeting Venue

Each Research Group SHALL determine the balance of email and face-to-face
meetings that is appropriate for making progress on its goals.

Electronic mail permits the easiest and most affordable participation;
face-to-face meetings often permit better focus, more productive debate and
enhanced working relationships.

Face-to-face meetings are encouraged to be held co-located with the regular IETF
meetings to minimize travel, since IRTF members are often also active in the
IETF, and to encourage the cross-fertilization that occurs during hallway and
after-hours interactions. Furthermore, as described above, even
limited-membership Research Groups are encouraged to hold occasional open
meetings; an IETF meeting would serve as an ideal venue for such an event.

Face-to-face meetings that are collocated with academic conferences or workshops
have also worked well for some Research Groups, particularly those with
substantial academic participation. Such groups are still encouraged to
occasionally collocate a meeting with an IETF meeting, in order to facilitate
the cross-fertilization between research and engineering that the IRTF is
chartered to stimulate.


## Meeting Management

The challenge of managing Research Group meetings is to balance the need for
consideration of the various issues, opinions and approaches against the need to
allow forward progress. The Research Group, as a whole, has the final
responsibility for striking this balance.


# Research Group Termination

If, at some point, it becomes evident that a Research Group is not making
progress in the research areas defined in its charter, or fails to regularly
report the results of its research to the community, the IRTF Chair can either:

1. Require that the group recharter to refocus on a different set of problems,

2. Request that the group choose new Chair(s), or

3. Disband the group.

The IRTF Chair is encouraged to make this decision after consulting with the RG.
However, if the RG disagrees with the chair's decision, it MAY appeal to the
IAB.


# Staff Roles

Research Groups require considerable care and feeding. In addition to general
participation, successful Research Groups benefit from the efforts of
participants filling specific functional roles.


## IRTF Chair

The IRTF Chair is responsible for ensuring that Research Groups produce
coherent, coordinated, architecturally consistent and timely output as a
contribution to the overall evolution of the Internet architecture. In addition
to the detailed tasks related to Research Groups outlined below, the IRTF Chair
MAY also from time to time arrange for topical workshops attended by the IRSG
and perhaps other experts in the field.

{:vspace="1"}
Planning
: The IRTF Chair monitors the range of activities. This may include encouraging
the formation of Research Groups directly, rather than waiting for proposals
from IRTF participants.

Coordination of Research Groups
: The IRTF Chair coordinates the work done by the various Research Groups.

Reporting
: The IRTF Chair reports on IRTF progress to the to the IAB and the wider
Internet community.

Progress tracking
: The IRTF Chair tracks and manages the progress of the various Research Groups
with the aid of a regular status report on documents and accomplishments from
the Research Group Chairs. The resulting reports are made available to the
community at large at regular intervals. The IRTF Chair MAY use the IETF
Datatracker to manage the status of Internet Drafts authored by the various
Research Groups {{?RFC6322}}.


## IRSG Member

Members of the IRSG are responsible for advising the IRTF Chair on the
chartering of new Research Groups and other matters relating to the smooth
operation of the IRTF. They are also responsible for helping review documents
that are being published on the IRTF Stream {{?RFC5743}}. In addition, most IRSG
members are also Research Group chairs.


## Research Group Chair

A Research Group Chair is concerned with making forward progress in the areas
under investigation, and has wide discretion in the conduct of Research Group
business. A Chair MUST ensure that a number of tasks are performed, either
directly or by others assigned to the tasks. This encompasses at the very least
the following:

{:vspace="1"}
Ensuring the Research Group process and content management
: A Chair has ultimate responsibility for ensuring that a Research Group
achieves forward progress. For some Research Groups, this can be accomplished by
having a Chair perform all management-related activities. In other Research
Groups -- particularly those with large or divisive participation -- it is
helpful to allocate process and/or secretarial functions to other participants,
after approval from the IRTF Chair. Process management pertains strictly to the
style of Research Group interaction and not to its content. Research Group
Chairs remain responsible for all actions a Secretary performs on their behalf.

Moderate the Research Group email list
: A Chair SHOULD attempt to ensure that the discussions on a list are relevant
and do not devolve to "flame" attacks or rat-hole into technical trivia. A Chair
SHOULD make sure that discussions on the list are summarized and that the
outcome is well documented (to avoid repetition).

Organize, prepare and chair face-to-face and on-line formal meetings
: A Chair SHOULD plan and announce meetings well in advance. (See {{mtgplan}}
for procedures.)

Communicate results of meetings
: A Chair and/or Secretary MUST ensure that minutes of a meeting are taken and
published to the participants.

Distribute the work
: It is expected that all Research Group participants will actively contribute
to the work of the group. Research Group membership is expected to be a
long-term commitment by a set of motivated members of the research community. Of
course, at any given time, more of the work is likely to be done by a few
participants with particular interests, set of skills and ideas. It is the task
of the Chair to motivate enough experts to allow for a fair distribution of the
workload.

Document development
: Research Groups produce documents and documents need authors. However,
authorship of papers related to the work of a Research Group is one of the
primary reasons that researchers become members, so finding motivated authors
should not be a problem.

  It is up to the Research Group to decide the authorship of papers resulting
  from Research Group activities. In particular, authorship by the entire group
  is not required.

  The Research Group Chair MAY use the IETF Datatracker to manage the status of
  Internet Drafts authored by the group {{?RFC6322}}.

Document publication
: The IRTF Chair, RG Chair and/or Secretary SHALL work with the IESG, IANA and
the RFC Editor to ensure documents to be published as RFCs conform with RFC
publication requirements, such as the conflict review defined in {{!RFC5742}}
and to coordinate any editorial changes suggested by the RFC Editor.

The publication process has been changing over the years and is expected to
continue to change on occasion. In addition, the IRTF Chair has freedom to
decide how IRTF documents are reviewed and approved before being sent onward for
publication. For at least the last ten years, the detailed publication process
has been documented on a wiki page {{IRTF-RFCs}}.


## Research Group Editor/Secretary

Taking minutes and editing jointly-authored Research Group documents often is
performed by a specifically-designated participant or set of participants
appointed by an RG Chair and approval from the IRTF Chair.


# Research Group Documents

## Meeting Documents

All relevant documents for a meeting (including the final agenda) SHOULD be
published and be made available as Internet Drafts at least two weeks before a
meeting starts. If a meeting is collocated with an IETF meeting, the agenda and
document submission deadlines communicated for that IETF meeting take
precedence.

It is strongly RECOMMENDED that a Research Group Chair make sure that all
meeting materials are made available via the IETF Datatracker's proceedings
system, which also handles "interim" meetings not collocated with IETF meetings.
All relevant documents (including the final agenda and the minutes of the
meeting) SHOULD be placed there. This has the advantage that all participants
can retrieve all files and thus make sure they have all relevant documents.


## Request For Comments (RFC)

The work of an IRTF Research Group usually results in publication of research
papers and other documents, as well as Informational or Experimental Request For
Comments (RFCs). The RFC series is the archival publication record for the
Internet community. Since 2009, IRTF RFCs have been published on a separate IRTF
Document Stream {{?RFC5743}}. A document can be written by individuals in a
Research Group, by the group as a whole with a designated Editor, or by others
not involved with the IRTF. The designated author(s) need not include the group
Chair(s). Initial publication as an Internet Draft is preferred, if only to
facilitate review, before asking for RFC publication.

NOTE: The RFC series is a publication mechanism only and publication does not
determine the status of a document. Status is determined through separate,
explicit status labels. In other words, the reader is reminded that all Internet
Standards are published as RFCs, but NOT all RFCs specify standards.

The RFC's authors are expected to work with the RFC Editor to meet all
formatting, review and other requirements that the RFC Editor, IAB or IESG may
impose. {{?RFC5743}} describes the approach that Research Groups follow when
they want to publish RFCs on the IRTF Stream. In summary, after the group has
decided that a given document is ready, a Chair initiates an IRSG Review. After
approval by the IRSG, the IESG reviews the document for conflicts with the
Internet Standards Process as described in {{!RFC5742}}. After the IESG review
concludes, the document undergoes final publication preparation at the RFC
Editor.


# IANA Considerations

This document has no IANA considerations.


# Security Considerations

Security issues are not discussed in this memo.


# Acknowledgments

This document is based on the October 1996 RFC "IRTF Research Group Guidelines
and Procedures" by A. Weinrib {{!RFC2014}}, which in turn was based on the March
1994 RFC "IETF Working Group Guidelines and Procedures" by E. Huizer and D.
Crocker {{?RFC1603}}.

Lars Eggert has received funding from the European Union's Horizon 2020 research
and innovation program 2014-2018 under grant agreement No. 644866 ("SSICLOPS").
This document reflects only the authors' views and the European Commission is
not responsible for any use that may be made of the information it contains.


--- back

# Changes from RFC2014

|---
| Rev | Changes
|---
| -05 | More feedback from Niels ten Oever. Fixed typos. RFC5793 -> RFC8179. Converted to kramdown-rfc2629.
| -04 | Addressed feedback from Mat Ford, Niels ten Oever and Martin Thomson.
| -03 | Changed the stream to IRTF and status to Informational, per discussion with the IAB at the Cambridge, MA retreat. Added funding acknowledgment.
| -02 | Added text about and reference to {{?RFC7418}}. Add pointer to IRTF RFC process wiki. More wordsmithing.
| -01 | Use {{!RFC2119}} terms instead of local definitions. Fix idnits (missing IANA section, say that we obsolete {{!RFC2014}}, etc.) Update obsoleted references. Update acknowledgments. Remove text about the Internet Monthly Report (IMR). Remove text that says that a RG should have 4-5 members, and that proposed charters should include the names of such "charter members". Add suggestion that RG acronyms end in "RG". Change recommendation that RGs have 1-2 chairs to instead say "a small number", to allow cases where more than two chairs are useful. Update text on IRTF RFC Stream publication {{!RFC5742}}{{?RFC5743}}. Add text on IRTF IPR policies. Add pointers and text to {{?RFC4440}} and {{?RFC6322}}.
| -00 | Document contains the entire, unmodified contents of {{!RFC2014}}, except for (1) boilerplate and layout changes that are due to the conversion to xml2rfc and (2) changed author information. It is being submitted so that it will be easier to view diffs of the content changes that will be introduced in subsequent versions.

