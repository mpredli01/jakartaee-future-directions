# Jakarta EE Future Directions - interest group meeting-20261029_160026UTC-Meeting Recording

**Date:** 29 October 2026, 04:00pm

## Executive Summary

- Combining MicroProfile and Jakarta EE could reduce costs, avoid competing specifications, and strengthen their shared roadmap.
- Progress remains blocked by namespace concerns, governance differences, and poor communication—not a lack of interest.
- Participants called for a shared record of concerns and clearer dialogue between both communities. No merger decision was made.

## Full Transcript

### Neil Patterson — 7:47

Today we are looking at the Microsoft profile and Jakarta Ee integration, and how we might see that progressing in the future, and what steps could be taken to ensure that that is well received and, you know, and as smooth a transition if, you know, if it happens as possible. So with that, Mike, I think you were going to also lead out with some thoughts that have been gathering over the course of the last month based on our last discussion.

### Mike The Old Man Redlich — 8:28

Yeah, I could bring up the notes from last month and go from there if that's, you know. And I know these meetings normally are 30 minutes, but, you know, if nobody minds, we can go beyond that, right? So let's see.  
And jakartaee easy.  
And.  
A weekly agenda.  
So, here was from last month, the minutes to post the recording, so, yeah, so...  
This has been an ongoing thing for about, what, a year and a half, right, Tanya, when you first told me at Java One last year, about MicroProfile, you know, moving into Jakarta Ee. And then, so here is a...  
the rationale for that. And there was a lot of history going behind it because, you know, I will say my first reaction wasn't quite, wasn't quite nice. I, but you know, it does make sense, you know, but, but yeah, so he can read here some of the stuff from last time about a lot of.  
A big technical hurdle was the namespace, and that vote did not pass. And I think it had to do with keeping the namespace to org.microprofile.spec. And so yeah, so there was a lot of things here from last month.  
The differences in the governance models, as Jan had pointed out last month, I guess there's an issue with the MicroProfile meetings steering committee being open and the Jakarta Ee steering committee meetings not.  
I mean, you know, despite the platform call every Tuesday at 11, Eastern Time is always open to everybody, that kind of thing. So, let's see. Oh, and Roberto brought up about the implementations like Small Rye for MicroProfile.  
What else was there? It was a good discussion.  
So yeah, you can see that here. I don't know what, if you want to choose a particular topic from here and continue on that. I don't know what works for best for folks here. So.

### Tanja — 11:01

I just want to, before we start discussing, I want to make a comment. So this was proposed by the MicroProfile for a while, and then Ibm was sponsored the idea. I think Emily presented the proposal. I think it was voted down.  
But I don't think the understanding of what was proposed versus what was voted on matched. Because if you talk to different groups, definitely it was debate on the namespace. It appeared that everyone voted on  
mandatory having a requirement of immediate change on the namespace, which was  
not what we voted on. It was the proposal is to initially accept Microsoft profile as is. That message did not come through.  
properly, and that's why that vote was turned down. That was discovered later on into, let's say, hallway conversations that people's assumptions and what was actually proposed did not match, and therefore voting was not necessarily reflected.  
of how the community felt about it. So anyways, a lot of time passed. I think it's the same argument, same discussion in the question. IBM is still not necessarily, well, not necessarily. IBM is not sponsoring the idea and has left.  
to the community to figure it out. Well, I guess almost, I would say rightfully, just because, you know, they tried it once. Yes, it was a mishap, but let's give others a try if the community is interested.

### Mike The Old Man Redlich — 13:13

OK, so, so if I understood everything correctly, that there was the only vote I remember is the namespace vote, but there was a vote to actually actually have that happen, the actually the merger to happen, because I must have missed that if so.

### Tanja — 13:27

Oh no, so it was from the get-go. The Jakarta Ee is more the steering committee. It has published and documented that they are welcoming micro profile into Jakarta Ee working group. When it came down to the namespace, you know, it appeared as if it's a...

### Mike The Old Man Redlich — 13:29

Mm.

### Tanja — 13:49

hard requirement from Jakarta Ee to change the namespace immediately, which was never the case. So therefore, it was voted down, the proposal was voted down, assuming it is the

### Mike The Old Man Redlich — 13:55

Right.  
OPA.

### Tanja — 14:09

A ******** requirement for Microsoft to come into the working group requires the change of the of the namespace, where when later on it was discussed.  
It was clearly communicated in various committees and groups that welcoming MicroProfile as is with their MicroProfile namespace into Jakarta Ee working group and the requirement of changing the namespace and keeping uniformity  
Will be discussed as we go along, as based on the specifications being.  
adopted into a profile or a platform, in one of the profiles or in platform. So that is a different discussion.  
Just to kind of be, yeah, does that help?

### Tobias Frech — 15:15

Um...  
Yeah, I get, I didn't attend all these discussions at that time back then, but from reading through all the minutes and so on and the discussions,

### Tanja — 15:19

Okay, thank you.  
Yeah.

### Mike The Old Man Redlich — 15:32

I.

### Tobias Frech — 15:38

in the different groups, I get the same impression. And I guess what is going on there is something like, if we do agree to join Jakarta, then it might happen that we are  
kind of a minority. And then then following namespace discussion, we might just be, yeah, not be heard anymore or don't have a majority or I don't know. And so they might have decided  
They, I understand, several people here are also contributing to Micro Profile.  
It might have been a decision or a...  
not conscious decision even to say if we completely avoid it, then we don't have to answer to that discussion anyway. I do see Roberto's hand here. I'd like to add something afterwards, but Roberto.

### Mike The Old Man Redlich — 16:46

Yes, Mayel.

### Neil Patterson — 16:47

Yeah.

### Roberto Cortez — 16:53

Hey, hello. Let me actually turn my camera on so you guys can see me. Hello.

### Mike The Old Man Redlich — 17:00

There he is.

### Tanja — 17:01

Ohh, there you are.

### Neil Patterson — 17:01

Ee.

### Roberto Cortez — 17:04

So I based it on the chat, the Fred, which is the ballot Fred. You can put that on the minutes and you can read it, right? Well, well, Tanja, I do respect what you're saying, but maybe people change their minds, but I mean, the ballot itself is very well, really well written out.

### Mike The Old Man Redlich — 17:09

No.  
Yes, okay.

### Roberto Cortez — 17:25

people knew what they were voting for. Mostly if you read the responses, everybody explained why they're voting one way or the other, right? And for my understanding, at least for reading and for knowing...  
the community and some of the members opinions, a lot of them, they were just voting exactly because they wanted to keep the consistency on Jakarta and they wanted to make the namespace change straight away, right? That was a conscious decision when they're voting. And if you read some of the responses, you can read those responses on over there.  
Right, if these people change their opinions later, that's a different discussion, and I, and I think some of them did, right, but at least at the time.  
I think there was no misunderstanding what they were voting for, because if you read the responses and you see their justifications, it's really clear why they voted -1.

### Tanja — 18:24

Yes and no. Keep in mind that that was, I know that not necessarily always everything is written down and I am absolutely sure that the link that you're sending will support what you just described.  
But I was sitting on all the meetings and the tensions were, and emotions, I don't want to say tensions, emotions were high. So once you get to the boiling point, you know, there is hard to have, you know, kind of, I'm sure you would agree.

### Roberto Cortez — 18:50

Sure.

### Mike The Old Man Redlich — 18:51

Ee.

### Tanja — 19:02

It is hard once you cross the line, people start not being reasonable. But when everything calmed down and was discussed yet again and, you know, looked into where we started and how we ended and what we voted on,

### Mike The Old Man Redlich — 19:14

Eats.

### Tanja — 19:22

it's a definite mismatch. And I would say, you know, being in the middle and having both communities dear to me, I would say that no one was right, but that topic is ongoing. And, you know, I'm on one hand,

### Mike The Old Man Redlich — 19:30

No.  
Yeah.

### Tanja — 19:43

Just want to see what community wants and put a little bit of the paint the picture how where we started. Yes, there was a miscommunication. And yes, there were different interpretations on what had happened.

### Mike The Old Man Redlich — 20:02

Okay.

### Tanja — 20:02

And I know what was being discussed, and it didn't come out of one meeting. I totally see how MicroProfile sees one side and Jakarta sees the other side, and I can see how they're all passionate about the technology. So my interest is  
Keep that passion constructive, if possible. Yeah.

### Mike The Old Man Redlich — 20:25

So just want to ask real quick, I shared my entire screen. So if I flip between tabs on my browser, do you guys see that change or?

### Tanja — 20:34

Yes.

### Mike The Old Man Redlich — 20:34

Oh, all right. So maybe I'll unshare, just share the document. How's that sound?

### Neil Patterson — 20:38

Sure.

### Tanja — 20:38

That sounds good as well. Whatever you feel.

### Mike The Old Man Redlich — 20:39

Okay, let me stop to... Yeah, I'm not used to this, yeah.

### Tanja — 20:43

Anyways, I don't want to say that it's one way or the other. I just want to clarify what what was the in in last year or so since was discussed. This was the the the the everyone I talked to. It seems that.

### Mike The Old Man Redlich — 20:48

How do I do it now?  
That was true.  
OK, here we go.

### Tanja — 21:02

that that's what they're talking about right now, regardless of who talked what before.  
And I don't want to spend, like we already spent quite a bit of time on the past. Like it's more towards the future. And when the governance comes into play, I can also talk about the steering committee and governance from that perspective, but I would love to let everyone else.  
Um...  
debate or express their opinion here.

### Mike The Old Man Redlich — 21:39

Yeah.

### Neil Patterson — 21:40

Tobias.

### Tobias Frech — 21:43

Ohh, really? I see Roberta as to the next one.

### Roberto Cortez — 21:48

No, already talk, I mean, uh, that.

### Tobias Frech — 21:54

Okay. I'd like to steer the discussion into the direction. Why are we proposing that micro profile joins? You know, what is  
proposed even. As I understand it, MicroProfile is already a working group in the Eclipse Foundation. Is that correct?

### Tanja — 22:27

Dss.

### Tobias Frech — 22:28

Yes, it is. They're already a working group. So what is proposed and one motivation we have is a financial one, right? But looking at what has, what's going on in their  
meetings and so in the minutes and so on. I have, it's a hard time for me to justify why we spend that money sending someone from our association to these groups if the points they want to talk about are constantly  
Pushed back, because there are no time for discussing these things.  
On the other hand, I completely understand that they don't want to be in a position where they are overvoted, yeah, and just because they joined another group. And I'd be interested to learn why it would be beneficial for Microsoft.  
and Jakarta to join forces and how would that look? What would change if they're already a working group right now? How would that be different?

### Neil Patterson — 23:56

So, from...

### Tanja — 23:57

Do you want me to start or someone else, please?

### Roberto Cortez — 24:01

I can, I can, I can, I can answer that, but I'm not sure if Neil wants to talk first.

### Mike The Old Man Redlich — 24:04

Ee.

### Neil Patterson — 24:08

Yeah, sure. From...

### Roberto Cortez — 24:10

I'll, but if you want me to answer, I can answer that.

### Neil Patterson — 24:15

Can you hear me?

### Roberto Cortez — 24:16

I can.

### Mike The Old Man Redlich — 24:16

Yeah.

### Neil Patterson — 24:18

Okay, great. So I was just going to say, from, I guess, our perspective, there's a  
Having the MicroProfile integrated or, yeah, I guess integrated into Jakarta Ee broadens the scope and the influence of Jakarta Ee generally. And  
just pragmatically from a financial perspective, we, the cost of supporting 2 working groups is somewhat of a concern. You know, we go through a yearly budget request for, you know, supporting  
being, you know, contributing to both and then also staffing the meetings and so on for both. So that has been raised as a concern, you know, within our organization that  
It would be.  
From A Pragmatica perspective, it would be more cost effective definitely to have them together. And it would also be more cost effective from a engineering perspective to be able to have a single larger scoped working group.  
And set of specifications on which to to build and integrate our our runtime our our Runtimes.  
So, Roberto, go ahead.

### Roberto Cortez — 26:07

Yeah, so I'm going to give you my answer, obviously. I mean, you gave the answer financially and organization-wide. Let me give you the answer, which is mostly the technical one, right? If you think about these in a technical way, there is no much chance to have like 2 separate things, right? Obviously, you can organize them as much as you want.  
But the issue is when we have these two working groups, they kind of, they may end up compete with each other, right? Which is not something that we want. And that's at least my opinion. Let me give you like a very quick example, right? So some time ago we were discussing.  
you should come up with a converter spec, right? Well, where does that converter spec should land? She'll go on Jakarta, she'll go on MicroProfile, right? Same thing for any AI spec, like obviously AI is something that's now consuming our lives, right?

### Neil Patterson — 27:03

Yeah.

### Roberto Cortez — 27:07

So, where should that go? Should it go to Jakarta or should it go to go to Michael Profile, right? So, obviously, what, and then what I'm gonna tell you, and then you're not gonna like, but I'm gonna tell you, but because we couldn't decide on where any of these things should land, right? So, if this converter spec just dies, right, because...  
What, what nobody, nobody could decide on where it should land, right? It's always Jakarta say it should land this way because we want to show progress and wherever, and then micro profile say which should land in this in this place because it's going to, we already have a micro profile config which already used converters, so, and we have already have jobs already used converters, so we're gonna just extract where we are.  
out there. And in the end, you have zero work done, right? Because we couldn't make a simple decision when any of these things should land. And obviously, you don't want them to have two competing specifications on the same thing, right? So that obviously.

### Mike The Old Man Redlich — 28:05

And...

### Roberto Cortez — 28:10

Now, if you think now, as an example, we were discussing as well in the last call of about Jakarta config or Micro Profile config, right? So, obviously, the Jakarta platform requires a configuration specification which already exists on the Micro Profile, right? But it doesn't suit what exactly Jakarta needs. So, what should Jakarta do? Should...  
adopt, she'll just create something new and that was being tried in the past, right? But the issue here is because you came up with these two working groups, they have like a lot of similarities and obviously, and actually MicroProfile config consumes Jakarta stuff, right? So in some ways, they're like competing and in some other ways, they're just like...  
Um...  
We're using at least micro profile, we're using Jakarta, not the other way around. And that's one of the things that we're trying to do, right? So in terms of in technical terms, right, there is no particular reason, there is no good reason for these two working groups to be separate, right, especially because they use or they want to use.  
things that both of them have, but at the moment, because they're separate, now we have all these discussions about namespaces and where each spec should land and wherever, right? So I hope that this clears a little bit your questions, at least on the technical side.

### Tobias Frech — 29:35

Mm.

### Roberto Cortez — 29:37

About having like one or two groups or whatever, I know that.

### Tobias Frech — 29:40

So it's clearly beneficial if the working groups as they are right now would work together more closely. And if decisions would be made if something goes ahead, right?

### Roberto Cortez — 30:00

Yeah, I mean, they were not working more closely. They were working as a single group, right? So there will be no discussion about where a spec should land, right? There will be no discussion about if you can use these or you can use that one, right? Because everything is already over there. I know that already talking too much. I will give my word to Tanya in a bit. Just like one little bit terrible one to answer is.

### Neil Patterson — 30:05

Right.

### Roberto Cortez — 30:22

Because he also mentioned that, and correct me if I'm wrong, we were saying that micro profile community may be scared or maybe not scared. I'm not sure if it was the right word, but that we may be underrepresentative if we move to Jakarta, right? But actually, that's already the case.  
Because many, or actually most of the members that are on Micro Profile are also Jakarta members, right? And I even commented these in the last call, which is if the Jakarta members that are also part of Micro Profile come up with a ballot that says, let's move Micro Profile to Jakarta and do all the renames and whatever.  
They can do that and win the vote because there's a lot already enough members that are on both working groups that have that list if you're picking up.

### Mike The Old Man Redlich — 31:09

Yeah.  
Yeah.

### Roberto Cortez — 31:19

The last thread of the vote, right? They could have put the resolution, or they could put like a ballot forward with the whatever they wanted to do, and they'll have enough votes to do it in that way, right? But they have, but nobody, nobody want, nobody did that still, and that's why one of the reasons why IBM got out of the.

### Mike The Old Man Redlich — 31:28

Ee.  
Mm.

### Roberto Cortez — 31:40

Future in that sense, because I mean, IBM tries in one route, right? It didn't work out, and as Tanja said, okay, we're just gonna drop from the, well, drop in the sense that, okay, we're just gonna go out of the way, and then the rest of the community, the rest of the working groups, or the rest of the members, then come in and propose something different.  
But that didn't happen still.

### Mike The Old Man Redlich — 32:03

Yeah, I just wanted to mention real quick, Tanya, sorry, that the perfect example of what you were just saying was the MicroProfile JWT Bridge spec, which was supposed to put together Jakarta Security and MicroProfile JWT authentication.

### Tanja — 32:04

Yeah.

### Mike The Old Man Redlich — 32:22

And I thought that was an excellent idea. I was even part of those calls, you know, to, you know, for that, but it was decided that it was going to be under a micro profile as a standalone spec. So, but how that got decided, I don't know or I don't remember, but, but yeah, but that's, you know, for every new spec, you know, like, just like you were saying, where's that going to land?

### Tanja — 32:45

Yeah, and not just that, like I want to point out that at this point, we are dealing with bigger problems that we are not addressing at all due to this, I would say, 8 year long or eight or nine years long debate.

### Mike The Old Man Redlich — 32:57

Okay.

### Tanja — 33:04

that got really hot in last year, year and a half or two. But, you know, instead of strategizing on the long-term roadmap together and having a Microsoft profile as part of it as a more complete platform and debate how are we collectively deal with AI,

### Mike The Old Man Redlich — 33:09

Ee.

### Neil Patterson — 33:09

Aem.

### Tanja — 33:28

how we can address quantum or how do we strategize and position ourselves in the enterprise world. Talk about whether this is even relevant technology for the  
Agentic Ai and and having agents picking up our technology when suggesting and and and you know dealing with the securities and creating material of that that sorts, we're still.  
having the same debate. So I guess my goal is, while I would love to see everything under one roof, just because our story is stronger, our positioning is stronger, we don't have to have this fight. Oh, if we are...  
Being on on on the on the sponsoring this conference, can can we take micro profile swag or who is paying for this or that? And and I think that's all energy draining. That's my personal perspective, right? I would respect.  
anything that community does, but again, in today's time and age, I think we should collectively focus our energy on much more important things and as well the financial part.  
Yes, absolutely, things can be saved, and that would be really important at this point for many companies.  
Yeah, that's about everything. And in terms of the governance, I would, we can talk about that, right, as well. From, and correct me here if I'm wrong, but talking to our members, I am getting that Jakarta the way it is. Yes, it could be more open and  
We're working towards that. I'm not saying everything will be mirroring MicroProfile because MicroProfile was very untypical working group. And the feedback that I'm getting from the community is that they consider Jakarta Ee working group highly functional.  
Not ideal, but highly functional working group. So I'll finish with that.

### Ondro Mihalyi - OmniFish — 36:22

You see.

### Tobias Frech — 36:22

Hi, Android, perhaps you wanna say something?

### Mike The Old Man Redlich — 36:25

Yes.

### Ondro Mihalyi - OmniFish — 36:25

Yeah.  
I think you raised a hand before me, so if you go, I'm sorry I came late, it was like half an hour or two into it and go on.

### Tobias Frech — 36:34

Okay, so perhaps I'll just make it really short. I've heard there is an invitation from the Jakarta Ee working group, and I understand that to join the two working groups, the Microsoft working group would have to  
decide to join. And if I look at the minutes of the MicroProfile Working Group, I don't see any discussion ongoing about that topic. So I'd simply like to ask people from the MicroProfile Working Group,  
What's holding you back?

### Roberto Cortez — 37:20

One, one, I mean, I have, I didn't even have any idea there was an invitation from Jakarta to join to join the working group, I mean.

### Mike The Old Man Redlich — 37:20

Vlasic.

### Roberto Cortez — 37:32

When, when, when was that invitation? I mean...

### Mike The Old Man Redlich — 37:34

What?

### Tanja — 37:36

Oh, I can show you. Like that was the very first. So MicroProfile has approached the Jakarta working group with this proposal. On that same meeting, the steering committee and any other subsequent committee and the meeting, if you look at the notes,

### Mike The Old Man Redlich — 37:39

Oh.

### Ondro Mihalyi - OmniFish — 37:41

Yep.

### Tanja — 37:56

welcomed the idea. There was even a resolution from the Jakarta Ee steering committee welcoming MicroProfile into Jakarta Ee working group. It was at that time left for MicroProfile to make a decision on it.  
That was, in the meanwhile, there was that voting, Roberto, not just to to to forget that that was the.

### Roberto Cortez — 38:22

But I thought that was something more recent, I mean.

### Tanja — 38:27

Oh, it's ongoing. From the Jakarta E steering committee perspective, that has never changed.

### Roberto Cortez — 38:29

Hey.  
Okay, because I mean, and that's one of the other issues, right? I mean, because...  
I don't attend the Jakarta calls. I mean, I'm not even sure if these calls are public for me to join, right? So maybe Emily will join, or maybe John, but at least I don't remember these being discussed on the Micro Profile calls. And I guess, I guess, I guess that's an issue, right? Because...  
And that's another problem, because you have like these things that are being discussed and all these different calls, and then you don't know what else is happening, but at least from what I know on the, or at least from what's been been discussed on the micro profile calls and and on the mailing list right after that.  
ballot that was proposed and it was failed. It was up for other micro profile working group members to come and propose how they will join in Jakarta.  
And the other, and and and and not not other not any other member, uh, right now come up forward with the proposal.

### Tanja — 39:49

So my understanding, and you might be right because I'm not attending micro profile calls. Like if you, if anyone attends the platform call, which is open and happening every single Tuesday, it is an ongoing topic and lately John is attending on a regular basis.  
You know, we have a standing agenda item. Anyone from Microsoft profile on whether it's integration, whether it's config or anything, so that's the standing agenda. From any other committee, whether it's the steering,  
specification has nothing much to do. Like there was an ongoing topic on the specification committee as well, but it died off just because there was never anything to report on. I'm sure it would be, you know, we're basically at the mode where we're waiting for some.

### Roberto Cortez — 40:37

Presentation group.

### Tanja — 40:52

indication from Microsoft profile that that's on your end, it is still of interest. And as Tobias was saying, I'm occasionally looking at the meeting minutes, it never comes up on the agenda. So it is a standing agenda on the steering committee as well. So tell me what

### Roberto Cortez — 41:07

No, so, so sorry to clarify then, and maybe, maybe that's the issue because now we're communicating properly and I think that we're running circles here, which is, and you did mention this at the beginning, right, after Ibm put forward the proposal, right?

### Tanja — 41:21

Yeah.

### Roberto Cortez — 41:27

So IBM got out of the picture to let other members to come up with their own proposal from the Micro Profile Working Group on how Micro Profile will join Jakarta, right? But at this time, no other member came forward with the proposal and I haven't seen any other members, maybe, maybe gone from the...

### Tanja — 41:44

Yeah, Jan was working on it from what I understand.

### Roberto Cortez — 41:47

From yes, he mentioned some time ago that he was going to work on a proposal, but he never he never came up forward with anything, so I'm not sure still doing anything around that or not, but since you did mention as well that the sentiment of of the Jakarta members did.

### Mike The Old Man Redlich — 41:49

Thank you.

### Tanja — 41:54

Okay.

### Roberto Cortez — 42:05

change or was not allowed, there was a mean understanding with the original ballot. Maybe we can just pick up again on that and come up again with the same proposal and maybe that will get accepted this time. I don't know.

### Neil Patterson — 42:24

Yeah, at some level, that would be ideal.

### Mike The Old Man Redlich — 42:27

Yeah, no, I attend the micro profile community calls and, well, there were technical calls, community calls, and now they do it once every other week now. I think it's, yeah, and, but yeah, I haven't heard anything about moving that proposal forward. So maybe that needs to be revisited so that.  
Maybe, you know, we can move this world.  
So, Andrew, I think you had your hand up.  
It's not in front of his camera, but...

### Tanja — 43:15

And by the way, just to kind of support a little bit of the willingness or interest of Jakarta working group, last year we had the whole year, that was one of our strategic goals. And, you know, we're kind of  
let's put it mildly, quite disappointed that we couldn't move this needle a little bit more. And there is ongoing discussion and almost right now it is more members are in favor within steering committee to keep that topic as  
the strategic goal. We would love to formulate it properly so it gives us ability to articulate the status right now, but it's very ambiguous because we don't know how to articulate it. Like we don't know where is the missing link. So these meetings from that perspective are useful.

### Neil Patterson — 44:12

Ee.

### Tanja — 44:20

Because to me, what I'm hearing, everyone wants the same thing, but things are not happening. I cannot move the needle because I am officially Jakarta program manager and I don't want to be kind of...

### Roberto Cortez — 44:26

Okay.  
Sure.

### Tanja — 44:38

up to appear one-sided or anything like that. This has to be a community decision.

### Roberto Cortez — 44:47

Okay, so I was going to suggest for you to show up on the micro profile calls, but I mean, if you if you if you're on that position, I know that that might be a little awkward, but I think that I think that.

### Tanja — 44:58

Yes.

### Roberto Cortez — 45:03

Which, I mean, it is the Eclipse Foundation that's in the middle of all of this, in the sense that...  
The working groups, I mean, you are the glue of everything, right? So, my recommendation is, can someone on the Eclipse Foundation like join both calls and act as a bridge between both groups, at least?  
for the first few times, because from what I'm hearing, I mean, we're not communicating properly between both working groups. So I think we need to have an enabler here. And maybe it doesn't have to be anyone from the Eclipse Foundation. Maybe it can be someone else. But I think there must be someone.

### Tanja — 45:29

What?

### Roberto Cortez — 45:48

that makes these two groups communicate and that joins both calls and like brings and takes things from one to the other because at this point nothing like this is happening.

### Mike The Old Man Redlich — 45:58

Ee.

### Tanja — 46:01

Yes, so let me tell you what's stopping. So once upon a time, and I'm not bringing history back, you know, if you send me as a member of community micro profile kind of an e-mail where like kind of invites.  
join this call and that is supported by whoever is attending the call and this is what we want to talk about. Yes, I can do that. But remember that it was requested for, at some point it was requested from the Micro Profile Working Group for.  
Eclipse Foundation staff to stand off because community runs on their own. And that is what is being respected. So don't get me wrong as I'm bitter about it or anything like that. I'm not. I'm just kind of, I don't want to be a burden or appear as something negative.

### Roberto Cortez — 46:51

Right.

### Ondro Mihalyi - OmniFish — 46:51

Yeah.  
If I can step to this a little bit, I fully agree with you, Tanja. I think this is like, it is your interest to merge the working groups, but you are not to decide, so you can only kind of moderate and help the decision to happen. So even if Eclipse Foundation representatives join the call, there should still be people from the

### Tanja — 47:09

Yes.

### Ondro Mihalyi - OmniFish — 47:17

Jakarta Ee working group. And I would like to have some people from at least steering and specification committee there because those are basically those who decide on some changes or some statements in Jakarta Ee. And I saw so Mayel.

### Mike The Old Man Redlich — 47:24

Open.

### Tanja — 47:34

Actually, no, Andre, the only people who can decide on the technical perspective are the platform people, right? Like, so the Tuesday call, spec people.

### Ondro Mihalyi - OmniFish — 47:44

I don't think so.  
And I'll tell you why. There's Neil Patterson in the chat I saw commenting that Ibm stands. There's one obstacle, at least, created by the specification committee that they voted that micro profile specifications, if they join,

### Tanja — 47:48

Tell me.

### Ondro Mihalyi - OmniFish — 48:08

they need to rename the prefix. But still the problem like it is related to the platform, but it's the specifications committee that decides on this.

### Tanja — 48:19

No, hold on, we we talked about that, Andre, you were late, we clarified, yeah.

### Ondro Mihalyi - OmniFish — 48:24

I'm sorry. I just want to comment on this, how I see it. The problem is like we already discussed since then, that this was a year ago, we discussed on micro-profile mailing list. I see now that I talked to also a few people in the specification committee, they were voting on the premise that the micro-profile specifications would join the Jakarta platform.  
the platform set of specifications, but they don't have to. They can do it later. So mostly people agreed that MicroProfile could join, specs would join the EE working group with the prefixes they have, and later when they, like we want to move them to the platform,  
Yes, then they would have to change the prefix. So I don't remember what was the vote about, if it was for all the specifications or only on the platform specifications. But if it was for all the specifications, maybe we can ask the spec committee to reconsider and change.  
the votes to only count specifications that would be in the platform and remove the restriction on other standalone specifications like micro profile. But this is just an illustration of things where things can get confusing when some specification, some committee talks within each other is not even public.  
people can join it, they decide on something. And then steering committee may have some other opinion and Michael has another opinion. The problem with our committees in Jakarta is they are not public. I don't think even mainly they are public. I'm not sure. But we have Jakarta community calls. I don't attend them, so I don't know if they're really happening. They are public.  
a micro profile call is public. So if we decide that we do it on the micro profile call, I think there should be people from the steering and specification committee. Currently, I think specification is more crucial because there's an obstacle to solve. But we should focus on all these obstacles because I see that

### Mike The Old Man Redlich — 50:25

Yeah.

### Ondro Mihalyi - OmniFish — 50:29

Everybody wants to do this. It's just I hear people like they see there might be problems with the prefix, there might be problems with the process, like the committees that they are not open, and MicroPub wants open.  
Goals, so maybe we would need to change the Jakarta Ee process to.  
Kind of make people from Microsoft comfortable.  
So just to identify all these objections and problems, why people would be wary to merge Microsoft with Jakarta Ee, because these are technical things. Everybody wants to do it, but they have some concerns. So we need to 1st list the concerns, explain them, if they are real.  
or just not substantial. And then if they are real, try to address them and basically make it a normal brainer than to, so that MicroProfile working group just raises the ballot to join the Jakarta working group votes is approved because there are no obstacles and  
And we done.

### Mike The Old Man Redlich — 51:47

Um, I uh, Tobias, I he uh.  
I think, I think it was you, but with a couple of links on the chat, I will include that.  
And, uh...  
So, wait, I'm on a different screen, sorry.

### Tobias Frech — 52:06

Yeah, I'm just trying to figure out who said what and who believes who said what and who's holding the ball and so on. I get the impression it's pretty unclear what was decided and what was not. And perhaps

### Mike The Old Man Redlich — 52:07

Yeah.  
Right, right, yeah.  
Ohh, that one.  
Yeah.

### Tobias Frech — 52:26

It needs a fresh new approach and get both, if I sides don't, yeah, you know how I mean, to get both sides at the table, especially the ones that have a lot of doubts about if that's a good idea and get them.  
To talk, what?  
what would be the motivations to do it, and what would need to be decided or changed before it can be done, and what can be discussed afterwards, or what has to be in place so that no one...  
has to fear that if they do that step, then later on they can't stop it anymore.

### Ondro Mihalyi - OmniFish — 53:16

Yeah, and I feel that the tracking is key because currently all the information is scattered. Now we have this Jakarta Future Directions call. We have minutes from this meeting, but then later we will discuss it in another call, and then it's really hard to review what was discussed and what are all the...  
wants to discuss in the future. So I would like to settle on one meeting minutes and use it anytime we discuss it in any call and always link to it in mailing list discussions so that we capture all the ideas, all the objections, everything, the progress.  
In one place.

### Mike The Old Man Redlich — 53:56

Yep, we have that already, Andro, in the Github repository in the bi-weekly agenda markdown file. There's the recording and the meeting minutes from September, and then we'll obviously do the same for this particular call. I'm also going to share the Google Doc with everybody.

### Neil Patterson — 53:57

Yeah, we can. Yeah.

### Ondro Mihalyi - OmniFish — 54:09

Okay.

### Mike The Old Man Redlich — 54:17

Here, so that you can take a take a few minutes to maybe correct any inaccuracies that I may have typed, or you know, we may have not captured that kind of thing, so...

### Ondro Mihalyi - OmniFish — 54:29

Is this a like a Github repository or a wiki that can be easily edited?

### Mike The Old Man Redlich — 54:33

Yes, it's a Github repo. I'll.  
Get the get the main link.

### Ondro Mihalyi - OmniFish — 54:40

I think it should be easily edited. I like Google Docs because anybody can like comment on them and then somebody can approve.

### Mike The Old Man Redlich — 54:47

Yes, yeah, that's a, but the main, there is a main repository that has presentations, transcripts, the bi-weekly agenda, that kind of thing. It's a good, you know, good place for that. So we'll set it in here. So put that in the chat.

### Ondro Mihalyi - OmniFish — 55:03

Yeah, you can, if we can put that link in the minutes, and I think it would be best if we put it in every minute that we discuss it, like in Microsoft call, if we discuss it, put the like small agent and put the link so that everybody can access it and find it whenever they look, they would see this link to the Github repository.

### Mike The Old Man Redlich — 55:07

Okay, sure.  
The link.

### Ondro Mihalyi - OmniFish — 55:23

We need to promote this because otherwise people will get confused where things are. But if they just try to find it and they will just find the link to the repository, everybody will find the same link.

### Mike The Old Man Redlich — 55:28

Yeah.

### Neil Patterson — 55:34

So I'm going to bring it bringing this up to to Emily. I mean, she from an Ibm perspective, she's the one that bridges the gap between the two. And so I will make her aware of these discussions. She's already aware of the previous meeting as she

### Mike The Old Man Redlich — 55:43

Aem.

### Neil Patterson — 55:52

that was participating. But, you know, bottom line, from what I understand from Alistair and Emily and Jared and others, the, you know, we to really move this forward from our perspective, either, you know, another working group member is going to have to make a new proposal.  
Or we would need to, if we want to revisit our original proposal, then we would need to basically have another vote to rescind the previous results and then, and then, you know, move forward with.  
the proposal again. So I'll raise it to Emily. Hopefully she can bring it forward to the steering committee and to my profile and ideally make some progress on this.

### Mike The Old Man Redlich — 56:51

Perfect. Yeah, all that stuff.  
Okay, so I got these up. I can I can add those to the minutes after we're done. Good.

### Neil Patterson — 57:02

Yeah, and then I'll.

### Mike The Old Man Redlich — 57:03

Actually, we're coming up on the top of the hour.  
Look, um...  
I, I just...

### Neil Patterson — 57:10

And I do have to drop.  
Oh, yes.

### Mike The Old Man Redlich — 57:30

And meet and talk offline on that, so.

### Neil Patterson — 57:30

Yeah.  
Okay, sounds good.

### Mike The Old Man Redlich — 57:34

Yeah, so, but yeah, thanks for everybody coming out today. I appreciate your time. You know, I know, Andre, you had mentioned something about the, it's 5 P.m. by you, now maybe 6.

### Ondro Mihalyi - OmniFish — 57:47

Yeah, it was hard for me to join at 5 this week.

### Mike The Old Man Redlich — 57:49

Wait.  
Yeah, yeah, I guess we should, I don't know, Neil, maybe that's something we can discuss as well, maybe starting earlier. Because there's nobody from the West Coast, as far as I know. So if we start at 10 A.m., 11 A.m. Eastern, you know, so, but yeah.

### Neil Patterson — 57:58

Yeah.  
Yeah.

### Ondro Mihalyi - OmniFish — 58:04

No, actually, it would be easier for me if it was on normal time, because it's we shifted the time to winter time. The next week, I think you shift, so it will come back to six hours, so it will be OK for me.

### Tanja — 58:12

Yes.  
Yes.

### Neil Patterson — 58:15

It'll come back, yeah.

### Tanja — 58:16

It will, it will come back to normal.

### Mike The Old Man Redlich — 58:16

Oh, okay, yeah, that's it.  
Yes, come on, whatever normal like.

### Ondro Mihalyi - OmniFish — 58:20

For me, 5:00 these days is not ideal.

### Mike The Old Man Redlich — 58:24

Yeah, right. Then that's no, that's totally understandable. Yeah. So, but, but yeah, so, but yeah, so stay tuned for, you know,

### Neil Patterson — 58:30

Sounds good.

### Mike The Old Man Redlich — 58:37

you know, for the next meeting. And Altania, I'll send you once we have a date, then I can send it, you know, send it to you to put on the calendar. I think it's been too long since this originally came up a year and a half ago. And, you know, I feel it's time to get this going.  
Despite my initial objections, if you remember, Tanja.

### Tanja — 59:00

Yeah, no, no. I mean, everyone had the initial objections and, you know, I think we all need to look into this from the bigger picture and not necessarily like...

### Mike The Old Man Redlich — 59:02

Yeah.  
Yeah.  
Ee.

### Tanja — 59:14

What's the value in the industry? What's the value in the messaging? I think there was no conference I was at where this was not pointed to as a divisive topic and soar on the whole technology.  
for no reason whatsoever. Emotional, yes, but I think at this point, emotions need to be put on the side and we need to do what's the right thing for all of us.

### Ondro Mihalyi - OmniFish — 59:45

Exactly. I think what slowed it down significantly is that everybody wanted it, but everybody had their own view how it should happen and their own conditions. And we stopped finding ways how to remove the obstacles and solve the concerns.

### Tanja — 1:00:04

And also, not to be bitter, but I want to point out from even Jakarta Ee perspective, after all these years, we're finally creating a long-term roadmap. So can you imagine if we all focused our energy on things like that?

### Mike The Old Man Redlich — 1:00:22

Yeah.  
Yeah.

### Tanja — 1:00:24

you know, as opposed to whether and how we can work together, and we already are. So I would love for this group to be more constructive from that perspective and figure out how we can stay relevant in this new era ahead of us.

### Mike The Old Man Redlich — 1:00:25

Yeah.

### Neil Patterson — 1:00:46

Yeah, sounds good.

### Mike The Old Man Redlich — 1:00:48

Perfect.

### Tanja — 1:00:50

Okay, thank you very much, everyone. Okay, bye.

### Neil Patterson — 1:00:50

Thank you all.

### Mike The Old Man Redlich — 1:00:51

Okay.

### Neil Patterson — 1:00:53

Take care.

### Ondro Mihalyi - OmniFish — 1:00:54

Thank you, Paul. Bye.

### Tobias Frech — 1:00:54

Thank you, bye bye.

Neil Patterson stopped transcription
