% Title = "Initial Thoughts on Completely Virtual IETF Meetings"
% abbrev = "Thoughts on Completely Virtual Meetings"
% category = "info"
% docName = "draft-manycouches-completely-virtual-meetings-00"
% ipr= "trust200902"
% workgroup = "manycouches"
%
% date = 2016-10-31T00:00:00Z
%
% [[author]]
% initials="D."
% surname="York"
% fullname="Dan York"
% organization="Internet Society"
%  [author.address]
%  email = "york@isoc.org"
%   [author.address.postal]
%   city = "Keene, NH"
%   country = "USA"

.# Abstract

This document captures initial thoughts about having IETF meetings that
are completely virtual. It explores the issues involved with both a
"planned" virtual meeting and an "emergency" virtual meeting. 

{mainmatter}

#  Introduction

What would a "completely virtual" IETF meeting look like? What would be
issues? What would be the advantages? How could it work?

The "manycouches" design team was convened to explore these issues and
understand what might be involved in holding a completely virtual meeting.
On 20 July 2017, members met with the IESG for a joint discussion at the 
IETF 96 meeting in Berlin. This document outlines many of the key issues and questions for discussion that emerged out of that Berlin meeting as well as
mailing list conversations.

Discussions identified two types of potential meetings the IETF could have 
that would be completely virtual:

1. PLANNED VIRTUAL MEETING - A "regular" meeting of the IETF that would be planned to be completely virtual.
2. EMERGENCY VIRTUAL MEETING - There could be a situation where a planned physical meeting suddenly needs to be virtual due to physical or political situations. For example, a natural disaster shortly before a meeting might cause people to not be able to attend.

Tools and processes may be very similar between the two types of meetings.
A key difference is that for an "emergency" meeting there may be the desire to 
replicate the planned schedule of the physical meeting as closely as possible.

It is unclear if the IETF might ever choose to hold a planned virtual meeting, 
but this document is designed to facilitate the discussion around what that
might look like.

## Benefits

Proponents of planned virtual meetings point to benefits such as:

- No requirement to travel, removing an economic issue for many.
- All participants are on an equal footing (versus current situation where physical participants have more interaction capability than remote attendees).
- Ability to think differently about how the schedule of the meeting might look.

The sections below outline many of the questions and ideas, some of which may
be benefits.

## Challenges

There are many challenges with hosting a completely virtual meeting. Some key
issues are:

- Inability to have the "high bandwidth" conversations enabled by face-to-face meetings.
- No ability to have "hallway conversations" and casual meetings with other participants.

The remainder of the document outlines many of the challenges and associated
questions.

Several participants voiced the opinion that replacing a physical meeting would
be pretty much impossible.


##  Conventions and Terminology

The key words "**MUST**", "**MUST NOT**", "**REQUIRED**", "**SHALL**", "**SHALL NOT**",
"**SHOULD**", "**SHOULD NOT**", "**RECOMMENDED**", "**MAY**", and "**OPTIONAL**" in this
document are to be interpreted as described in RFC 2119 [@!RFC2119].

Additionally, the key words "**MIGHT**", "**COULD**", "**MAY WISH TO**", "**WOULD
PROBABLY**", "**SHOULD CONSIDER**", and "**MUST (BUT WE KNOW YOU WON'T)**" in
this document are to interpreted as described in RFC 6919 [@!RFC6919].

# Program

## Meeting Structure

With a completely virtual meeting, the structure of the meeting does not 
have to comply with the traditional IETF meeting schedule. It could, for
instance, stretch out over the entire 24 hours of a day. Questions for 
discussion include:

- Is the meeting still structured over a week?
- Do the meetings still exist within certain hours?
- Do multiple meetings exist at the same time as they do now?

Again, in the case of an unplanned "emergency" virtual meeting the desire
may be to stick with the already-planned schedule. But for a planned 
virtual meeting the schedule can be open for discussion.

There was some discussion that a meeting could span more than the 
traditional week. However, the counterpoint is that keeping it within 
a week gives a focused block of time that people could allocate for 
participation in the virtual event.

## Timezones

What timezone does a virtual meeting operate in? Or does it operate in 
multiple timezones?

One suggestion was that each working group might choose its own timezone
based on the best timezone for the main contributors and leaders. (Although
this might then limit participation from other areas of the world.)

## Deadlines

What do deadlines look like for a completely virtual meeting? Are the
deadlines for agendas and drafts kept as they are for a regular meeting?

## Plenaries

What does a plenary look like in a virtual meeting? The same large session
as today?


# User Journey / Experience

## Participating in multiple sessions

It is currently possible for remote participants to join into multiple 
working group sessions at the same time. Users simply run Meetecho in 
multiple browser windows or multiple computers. How does this impact
users' experience?

## Side meetings

It is quite common for groups to decide during an IETF meeting to go 
off and have a side meeting. 

- How can this capability be reproduced in a virtual environment? 
- Could the system allow people to create ad hoc meetings in some fashion?

## Hallway conversations

The casual hallway conversations are a key component of IETF physical 
meetings. How can some version of this capacity be made available?

## Unstructured time

How do you incorporate some concept of "unstructured" time where people 
can meet and connect?

## Serendipity - discovering other users

Part of a physical meeting involves discovering other people with common
interests or backgrounds. How do you help people find others?

## Microphone lines

How do "mic lines" work in a completely virtual meeting? Would this in fact
be a benefit as all attendees would be in the same queue?

## Mentoring

How would the "mentor" program work in a virtual meeting? The same as with
a physical meeting?

## Inclusivity

How do you bring new people into sessions? How do people learn about side meetings?
About hallway conversations?

#  Technical Considerations

Many technical questions need to be discussed.

## Infrastructure

What is the infrastructure used to host a completely virtual meeting?
Are current systems such as Meetecho sufficient? Would new infrastructure
need to be established?

What kind of bandwidth would need to be available?

## Capabilities

Do virtual attendees have video connections? voice? chat?

## Network Operation Center (NOC)

Where does the NOC "exist" for a completly virtual meeting? What is its role?

# Administrative

## Centralized Resources

What is the impact of a virtual meeting on centralized resources such as
support staff? What is the full role of the Secretariat during the meeting?

## Finances

- What would the impact be on IETF finances?
- Would we charge the same amount to attendees as a regular meeting?


#  Security Considerations

There are many considerations related to security and privacy that need
to be factored in to a virtual meeting.

## Availability

How do we ensure that an attack such as a distributed denial of service (DDoS) doesn't take out the entire virtual meeting? What about an attack against a
particular region?

## Integrity

How do you know that the person who is logged into whatver system is 
used is in fact who they say they are? In a physical meeting:

- We can see the person and physically identify them.
- Users wear name badges that were issued at registration time.
- There are typically other people who may know many individuals.

How are these physical considerations replicated in a virtual meeting?


#  IANA Considerations

There are no IANA considerations associated with this document.

{backmatter}

# Acknowledgements

The author thanks all of the participants of the manycouches design
team as well as the IESG members who participated in the discussion
on 20 July 2016 at IETF 96 in Berlin.

# Development Note

This document is being developed using a repository on Github at:
https://github.com/danyork/draft-york-manycouches-completely-virtual-meetings
Comments, issues and pull requests are welcome.