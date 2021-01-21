---
title: "Discussion: Private Data and Policies (September 2020)"
tagline: "A Data Together 2020 Reading Group Discussion"
date: 2021-01-21T07:00:00-23:00
draft: true
authors: ["Kelsey Breseman", "Data Together"]
---

How have particular implementations of data privacy policies impacted humans, economics, and legal systems? What are appropriate expectations around data privacy, and who should inform, create, or enforce policies?

<!--more-->

## Readings

Grounding

*   Brookman & Hans, Center for Democracy & Technology (2013) [Why Collection Matters: Surveillance as a De Facto Privacy Harm](https://cdt.org/insights/report-why-collection-matters-surveillance-as-a-de-facto-privacy-harm/) on why data collection matters
*   (optional) Hochfellner, Lane, and Kreuter, Responsible Data Science, NYU Center for Data Science (2019) [Privacy and Confidentiality](https://dataresponsibly.github.io/courses/documents/spring19/Lecture4.pdf) slides 1-9, 14, 18-19, 35-37 definitions and introductions to challenges and tools

Attempted and proposed solutions

*   Sobers, Varonis (a cybersecurity company) (2020) [A Year in the Life of the GDPR: Must-Know Stats and Takeaways](https://www.varonis.com/blog/gdpr-effect-review/) a review of one year of GDPR implementation
*   Office of the Press Secretary, The White House (2012) [We Can’t Wait: Obama Administration Unveils Blueprint for a “Privacy Bill of Rights” to Protect Consumers Online](https://obamawhitehouse.archives.gov/the-press-office/2012/02/23/we-can-t-wait-obama-administration-unveils-blueprint-privacy-bill-rights) Obama White House proposed approach
*   O'Connor, Digital and Cyberspace Policy Program, Council on Foreign Relations (2018) [Reforming the U.S. Approach to Data Protection and Privacy](https://www.cfr.org/report/reforming-us-approach-data-protection) a critique of current U.S. approach and suggestion for path forward
*   (optional) Balkin & Zittrain, The Atlantic (2016) [A Grand Bargain to Make Tech Companies More Trustworthy](https://www.theatlantic.com/technology/archive/2016/10/information-fiduciary/502346/) on applying the legal concept of a fiduciary to information as well as to finances (intersection with [Trust conversation](https://datatogether.org/posts/10_trust/))

Other optional readings

*   (optional) FTC (2017) [Informational Injury Workshop](https://www.ftc.gov/news-events/events-calendar/2017/12/informational-injury-workshop#:~:text=The%20Federal%20Trade%20Commission%20hosted,Acting%20FTC%20Chairman%20Maureen%20K.&text=The%20FTC%20invites%20comments%20from,topics%20covered%20in%20the%20workshop.) insight on how the U.S. government collects public comment on this topic
*   (optional) [Challenging algorithmic profiling: The limits of data protection and anti-discrimination in responding to emergent discrimination](https://journals.sagepub.com/doi/pdf/10.1177/2053951719895805)

---

{{< rawhtml >}}
<img alt="A yellow wall with a tiny window in the lower right" src="/images/blog/11_private_data_policies.jpg" width="100%">
{{< /rawhtml >}}

*Photo by [Mark Fletcher-Brown](https://unsplash.com/@markfb?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)*

---

## Introducing the readings

**KELSEY**: Today we’ll be talking a lot about **risk** and **harm** from failures in the **handling of private data**. Jonathan, do you want to start by talking about some of the readings?

**JONATHAN**: I really liked **[Why Collection Matters: Surveillance as a De Facto Privacy Harm](https://cdt.org/insights/report-why-collection-matters-surveillance-as-a-de-facto-privacy-harm/)**. The paper takes the question, why do we care about private data and privacy policies, and reframes it to ask, **do we need to prove that there's a harm? What things are risky by default?** You can either assume harm is only introduced when a bad thing happens, or that harm is introduced the moment that there is a risk of a bad thing happening.

The General Data Protection Regulation (GDPR) was a major attempt to address some of the privacy concerns people have around their data. But based on **[A Year in the Life of the GDPR: Must-Know Stats and Takeaways](https://www.varonis.com/blog/gdpr-effect-review/)**, **63% of Europeans still don't feel like their data is properly protected**. How do we write regulation in such a way where it could be uniformly applied so there's confidence that this is providing some layer of security? How do we think about regulation from a harm perspective, and then also, how do we make it not so hard for people to actually implement?

That ties into Jonathan Zittrain on how to think about proper regulation, **[A Grand Bargain to Make Tech Companies More Trustworthy](https://www.theatlantic.com/technology/archive/2016/10/information-fiduciary/502346/)**. A lot of times, because of an intention to not stifle innovation, **we tend to bias towards under-regulating.** Zittrain suggests **information fiduciaries** as a legal framework we might use as a stick to keep tech companies from acting against our interests.

I think a lot of the time, we think about environmental regulation as, **after we've done a bad thing, how do we apologize?** This feels similar.

**There's a hodgepodge of existing data privacy rules** across sectors of data. We have HIPAA that thinks about things in  a medical context, we have CAPA thinking about children. But truly, data is quite arbitrarily sliced up. **Maybe what we need is a meta-model of personally identifiable information**, a definition and rules for how to treat it.


## Appropriate regulation at different scales

**KELSEY**: There’s a quote from Nissenbaum in the [Privacy and Confidentiality](https://dataresponsibly.github.io/courses/documents/spring19/Lecture4.pdf) slideshow: "notification is either comprehensive or comprehensible, but not both". How do we make this both functional and parseable? **How can we have a regulation that actually works, that people understand and that companies can implement?**

Jonathan, you mentioned **this tendency to not regulate things if we don't have to.** I've set up a lot of different communities from scratch. When I’m setting up a new community, I do write a code of conduct right away, because it's a signal that this is a space that takes inclusivity seriously. But beyond that, **I explicitly try not to make rules for things that aren't problems yet**. It's a lot of work to make and enforce regulations, and it doesn't create the atmosphere that you're trying to create, where community members actually depend on and trust each other.

But I don't think that scales; **for larger polities, I think you need to think more about potential harms up front;** you don’t have the same kinds of ties that implicitly bind a small community.

We always talk about what scales here. You can have trust within a unit of five people, but **you can't have the same kind of trust within a unit of 1000 people.** And of course, a country is much, much bigger than that.

With these organically growing communities, it can be a really communitarian exercise to think about, what are the rules that we need as we grow? But **what we're talking about on a government level is always retrofitting.** There's no new regulation that doesn't negatively impact some business, and some individuals via those businesses. But failure to introduce regulation might also negatively impact individuals. So regulation is a really different question at that level of scale.


## Attempting to quantify harm

**JONATHAN**: We also see data breaches. It's not a theoretical; it is a thing that is happening. The tradeoff seems to be, **what is the sum of the total harm, versus how hard it is to implement some of these protections?** If we were to aggregate the number of people harmed in the Equifax breach, how bad is that harm versus the economic harm of companies implementing protections?

I assume the security features were on someone's to do list at Equifax, but lower priority. Most likely, it was lower priority because of the tradeoff between the cost of the fix and the cost of the risk of leaked data.

**KELSEY**: We were talking earlier about how ridiculously busy we are right now, while in the process of implementing technological infrastructure. I took [an antiracism workshop by the Adaway Group](https://adawaygroup.com/rework/) this summer, and one of the things that I hadn't heard before was this concept that **busyness is a tool of white supremacy**.

One of the ways that can be true is, if you're the person in the position of implementing the change, you're worried about yourself and what your boss is going to say if you don't get the change done on time, so you don’t give it enough time and attention to ensure the work embeds your values. That's one of the ways that we get these data vulnerabilities. **Somebody's just trying to get stuff done in a system that says, sooner is better.** As long as we don't notice a big gaping hole, merge the code.

**JONATHAN**: **The harm introduced can really vary depending on what data and in what context. That can make it really hard to quantify harm.** It matters what data ends up getting leaked, and what it can be used for.


## Trust as a common pool resource

**GREG**: [Data Together has talked about the concept of the knowledge commons before](https://datatogether.org/posts/01_knowledge_commons/), right? It’s a branch of Ostrom’s common pool resource management school of academic thought that builds off of Nissenbaum's work. Some of those folks have recently taken [Nissenbaum's framework for contextual integrity](https://nissenbaum.tech.cornell.edu/papers/Privacy%20and%20Contextual%20Integrity%20-%20Frameworks%20and%20Applications.pdf) as the important thing about privacy in this interconnected world: **is information that I share in this specific context going to be appropriately translated or blocked from being used in a different context?**

This lends itself to **thinking about privacy, trust, and people's dignity as a common pool resource** of sorts. It can be easily squandered and polluted, and there are ways to cope with the threats to that vulnerable resource, and those ways entail institutional design.

**Maybe a company is capable of stewarding some piece of this puzzle, but that steward needs to be monitored**, based on what we know about vulnerable resources. You can have an appropriator who has the power to deal with this resource, but who will monitor that appropriator? Who will monitor the monitors? How are rules about what is being monitored set? **Are those rules set by people whose stakes are involved in the management of the resource?**

I appreciate having this frame. But common pool resources are tricky even in simple scenarios. And the more complex it gets, the bigger the scale gets, and the more diverse interests are involved, the harder it is.

**JONATHAN**: I'd be curious to know what your thoughts were on Zittrain's concept of **information fiduciaries,** applying the concept of the fiduciary, “a person or business with an obligation to act in a trustworthy manner in the interest of another”, to data. It doesn't have to be trustless; it's "trustless", because there's a huge economic camera that could in theory be swung against you, if you abuse that trust.

**KELSEY**: Ideologically, I really like the fiduciary concept. But I’ve seen this pattern before where companies talk about their interest in “pre-complying” with regulations that aren't yet imposed. Typically, they’re **trying to ward off real regulation by creating their own loophole-ridden version of it first.**

I'm a cynic, but a human optimist. I'd like to believe that nobody's trying to do evil things, even within their corporate role. So I don't disbelieve that it could happen.


## Present harms from privacy failures

**GREG**: The phrase I usually use along those lines is Gramsci's: it's **a skepticism of the intellect and optimism of the will.**

I have to say, the optimism of my will is really depressed right now. I'm not a technologist, but over the last five years, I've inserted myself into technology conversations. **I've been bringing up these questions about privacy in a very specific cross section of health, human and social services** with the technology and innovation types. And nobody was having conversations about harm.

For the first couple of years, the response in these spaces was that the cybersecurity subcommittee is taking care of that, or that issues of consent are worked out in legal through the data use agreements. But **I'm talking about harms that are lawful, and potentially from non-bad actors.** And these harms weren’t being accounted for.

I tried to learn from GDPR  and started to bring back principles of **revocability, making data transfer monitorable,** Nissenbaum's distinction between **comprehensive versus comprehensible.** But when I bring in these principles, **people get really quiet.**

The technical people get quiet because **they’re not sure it’s possible to account for some of the things that I'm pointing out.** And the policy people get really quiet because they don’t know what to say to the points that I'm making about **the gaps between what's compliant with regulation versus what's ethical.**

Right now, there's some hand waving that goes on behind the notion of individual consent. But **individual consent, as a model, doesn't work as a method of  giving people agency and thinking through potential repercussions, tradeoffs, and unanticipated consequences.** And I don't see other models out there for how communities can make decisions about this stuff.

After Obamacare passed, **hospitals and health insurance companies seemed to suddenly realize that people become sick because they're poor,** and suddenly cared about people not coming back to the hospital. So now they’re trying to send people to social services. They want to get every community organization onto the same integrated platform so that they can refer people directly and know exactly what happened with social services and case management. But that creates some major data risks.

This is healthcare; **“do no harm” should be a first principle. But it doesn’t come up in these conversations around data integration.**

**JONATHAN**: I'm curious if you could go into that more. How do the harms manifest?

**GREG**: There's a range of possible harms. Most people, when they think of harms, think of hacking and other intentional data leaks. But there's also **deanonymization.** Especially when **we're talking about bringing data from all these different systems and linking them together,** deanonymization is a major risk.

I'm also thinking beyond deanonymization, of the tremendous potential harms that can come from the use of aggregate data from all these different systems in **algorithmic decision making** and regulation.

Recently, [Native American women coming in for COVID tests were separated from their children by the New Mexico health system](https://www.nydailynews.com/coronavirus/ny-coronavirus-native-arizona-hospital-separated-babies-mothers-20200615-sibyk6meejco5cvecbzny7tbd4-story.html), because some algorithm decided that those children were at risk. **Every time a Native American woman came in to get tested for COVID, they were separated from their child.** This might not have been a conscious intention; that policy might have emerged from decisions made by machine learning that maybe nobody is specifically accountable for.

**JONATHAN**: Anyone who's tried to write an algorithm knows exactly how caveat-intense it might be to try to encode good decision making. But **when that algorithm is brought into use, those caveats can fall away.** People often accept that because the computer spit out a score, that’s what they should do.

**GREG**: There's lots of talk in this space about “improving health outcomes”. **Often, what that really means is saving money for the hospital system.** Poor people, especially poor Black people, are associated with more health problems. Because of this, **algorithms end up shunting them out of certain kinds of care contexts and into others.** The hospital system determines that the care is going to be more expensive, and that the potential intervention is less impactful. **It might stack up all these problems and determine that they don't deserve to get care**.

**How is the aggregate set of this data being used to allocate resources in ways that might re-entrench existing patterns?** There are all kinds of ways in which it just serves as more input into a system that already yields inequitable outcomes. And so privacy doesn't really cut it.

But I've made the case, and now people are turning to me, and they're saying, Okay, what should we do? And I don't know.

When you get technology innovators and healthcare executives on a panel talking about how awesome healthcare interoperability is, these issues don't come up. When I ask these questions, they don’t seem to have thought about the potential for these things to go wrong. **It's the nurses who come up to me and say, thank you for asking that question**. It's the people who've seen things go wrong over and over again who see that problems are going to come up.

How do we get those nurses into governing bodies? When privacy comes up, that's what I'm wondering: **how do we get the people who actually deal with the outcomes involved in the process of making decisions?**

That is a very unpopular question, I'm finding.


## The precautionary principle

**KELSEY**: Back before I was in this scene, I read [a book of environmentalist essays](https://www.goodreads.com/book/show/2946563-how-shall-i-live-my-life), one of which was all about the [precautionary principle](https://en.wikipedia.org/wiki/Precautionary_principle). It's an argument that says, **if you can't prove that it's harmless, you shouldn't do it**.

At the time, I was very much in the tech startup scene, and was also very much on that train of: throw stuff out there. Make your name as fast as you can. If people are willing to give you money, ship it. At the time, my reaction was that if we followed that principle, we would never do anything. You can never prove that something is harmless. I don’t totally disagree with my former self, but I understand the call for the precautionary principle a lot more.

**JONATHAN**: I often think about self driving cars. They will either be here very soon or never, because it really does come down to, **how do you define harm? And what are reasonable levels of harm?** By default, **there is some harm that's involved in accepting the status quo.** Take genetically modified food. How many people would be unable to have food security without this genetically modified option? In specific contexts, **it might be worth asking if we are implicitly saying that the status quo is the acceptable thing.**

**GREG**: Have y'all seen the [Feminist Data Manifest-No](https://www.manifestno.com/)? I’m on the leftmost edge of my field, but the authors of this are far to my left, and they seem correct. It starts, "**We refuse to operate under the assumption that risk and harm associated with data practices can be bounded to mean the same thing for everyone, everywhere, at every time.**” And it gets harder from there. And I'm reading through this, and agreeing. And at the end of it, I don't know what I'm left with, as someone who wants to reduce harm in these fields.

They're basically making the case for **refusal and rejection**, and it seems solid to me, which is worrisome. **Where does that leave me as someone who's trying to do ethical work?**

**KELSEY**: I think you're right, Greg. I think the Manifest-No is totally right. I don't think it means you can't do anything with data; I think it means you have to do really participatory things with data.

**GREG**: Right. And in the field that I'm in, I was already struggling just to be say, **let's create a group of people who aren't just users, but who are setting priorities for this entire system and evaluating outcomes.** Maybe that's a version of this. But I am concerned that the forces in power are inherently going to have the upper hand when it comes to complex information systems, no matter what kind of participatory action research you throw at them. In a situation where we've gone from passive white supremacy to active white supremacy in this country, I think that leaves those of us who believed in innovation in a very difficult spot.

But give me some bright spots! What's working? Who's doing it right?


## Examples of good

**KELSEY**: Have you heard of **[Buurtzorg](https://www.buurtzorg.com/)**? They’re a key example that is used in a book called [Reinventing Organizations](https://www.reinventingorganizations.com/). Basically, a group of nurses was experiencing a lot of those types of issues, and also experiencing a lot of labor justice issues. They got together and formed this nurse cooperative. It now covers a pretty large amount of the Netherlands. **They’ve created this really direct line of communication between actually doing the care and managing how care is done.** I don't think that cooperatives are by themselves a panacea, but I think that's a big piece of what we're trying to reach for in a participatory democracy model.

**GREG**: There’s [Design Justice](https://mitpress.mit.edu/books/design-justice). The many networks of thought and activism that Sasha points to there was really helpful for me to bring into some spaces. They specifically linked to [Our Data Bodies](https://www.odbproject.org/), which is a really good start to bring some of these ideas into a digestible framework.

**KELSEY**: [Max Liboiron's lab](https://civiclaboratory.nl/author/maxliboiron/) in Canada does a lot of data justice and true academia moving the needle on who's allowed to be participatory in what spaces. I also like what we're doing with the [Environmental Enforcement Watch](https://environmentalenforcementwatch.org/), we're trying to get different people involved with EPA enforcement data.

**JONATHAN**: As the dynamics of power change, you do see some incentive alignment. With iOS 14; Apple is doing what it thinks is best for the privacy of its customers, and it's using that as a unique selling point. It doesn't mean that it's not opinionated, and there could be divergence of how Apple is forming its opinion. What enforcement mechanisms do we have if we think that Apple is doing something that's not far enough? But **as this becomes a hotter and hotter topic, there is more consumer power**.


## Challenging individual consent

**GREG**: **Infrastructure is the set of things that stand behind the software, and that’s where we need to start.**

I have to explain this a lot in my field. Everybody wants to talk about what the software will look like that everybody will use. But the data exchange pipes, the data lake, all that is infrastructure. So are the meetings where you review what's happening in the pipes and in the lake, and so is the process of making decisions over what should happen in the lake and what should be able to go through the pipe. **It's not just the data itself, but the way we use the data that's really at stake here**.

I think that's also reflected in **this notion that individuals should consent once to something that was spelled in some contract that was signed five years ago** when the software was procured.

**KELSEY**: Which you didn't read in the first place, probably.

**GREG**: In this notion of individual consent, **it’s taken as a given that people should own their own data.** But think about a woman going into a social service provider who has three kids, an ex-husband, the kid has a boyfriend, there's a caregiver involved. **Her data is tied up in all those people's data.** If she's going to talk to her social worker about this stuff, or her health care provider, they're going to ask her these questions, because if they want to address her social determinants of health. They need to know all this information about her home situation, her family life. So she's sharing all this data about other people. That's her data. She consented to share it. But what about them? **We have no framework for thinking about how to protect people whose data is entangled with other people.**

**KELSEY**: Jonathan was talking earlier about that positioning of harm. **Does the harm exist when it occurs? Or does it exist when the opportunity for harm is first created?**

**GREG**: Explain this to me a little bit more?

**JONATHAN**: Imagine you have a store. People buy stuff from you , so you get a bunch of credit card information, where you’re shipping it to, their full name, all that good stuff. **Is the harm introduced at the moment when Kelsey hacks me and that data is leaked? Or is the harm introduced the moment I didn't encrypt your data**, such that even if she hacked my system, she wouldn't be able to read anything?

**GREG**: Right. So it's, is the bad thing, making the harm possible?

**JONATHAN**: Yeah. And there is this interesting question of, **what data permissions do we give to each other?** Earlier, I needed a contact, and Kelsey volunteered someone's email to me. There is some social trust that we imbue on people; in a human context, that feels normal. But if I was to look at Kelsey's contact list and see every person she's emailed in the last year, that’s clearly very different. So, what are the socially acceptable versions of what we share? And **in what contexts do I have the right of veto?**

Back in 2011 or so, Facebook was trying to make the social graph into an API that anyone could plug into. That's an interesting example of the same issue. Do I get to volunteer the fact that we are friends to the world, or to some application?

**GREG**: Yeah, and how do we navigate that tension between comprehensiveness and comprehensibility? **I want people to have tools so that they can gradually think through the implications of different things.** When I'm presented with: “do you agree to these terms of service?” I'm going to agree if I need to get in there, because I’m presented with this disempowering binary choice.

Are there examples of methods that enable people to navigate between what they can immediately comprehend and the broader comprehensive universe of potential implications?

**JONATHAN**: **Open source licensing might be a helpful model**. Companies have widely varying policies around use of your data. You’re meant to read and consent to each set of legal terms. But I'm not going to try to understand the 15 different flavors of Microsoft's terms of use versus Facebook's.

**What you really want is some sort of general framework that can be applied over and over again**: a standard set of permissions, like the [creative commons](https://creativecommons.org/choose/) or [other common open source licenses](https://opensource.org/licenses).

**If we had standardized privacy policies and terms of use, I could more explicitly give consent, because I would know what I was signing up for.** We could also use tools to automatically flag when certain types of policies are embedded in dependencies or other things inside of projects. You can even imagine, in a browser, you might be able to configure default preferences, and then explicitly be able to, review who have you given what rights to, and be able to revoke those permissions.


## Personal culpability versus abstraction of responsibility

**KELSEY**: In our [trust conversation](https://datatogether.org/posts/10_trust/), we mostly ended up agreeing that trust is a human-to-human thing. **What if there was personal rather than corporate responsibility for violation of laws and regulations?**

**GREG**: You mean like, shouldn't Mark Zuckerberg go to jail?

**KELSEY**: Yeah. If it can be proven that he had control over the thing, and didn't fix it, and/or didn't anticipate the problem, or if he was the expert who should have known, **Shouldn't he be personally vulnerable in the same way as his users are personally vulnerable** when our data is used?

**GREG**: And his board members.

**KELSEY**: Even just saying that, it's not like he made the code. It's not like he personally audited it.

**JONATHAN**: I do think there is a level of organizational abstraction that's hard to deal with, too. In a recent congressional hearing, they interviewed all these tech CEOs. Bezos was asked point blank: does Amazon use pricing data from the website for some specific purpose? And **he replied, "it is a matter of policy that we don't," but he wouldn't explicitly say, "I know for a fact that we don't"**.

Maybe this is exactly the point. You may have a policy, but **if there's no consequence for violating the policy, then you're not actually implementing.** If someone discovered it, yes, they would be reprimanded or whatever. But no one has their neck on the line.

**KELSEY**: A big chunk of EDGI's work over the last few years has been showing that [the EPA is basically failing to enforce environmental regulations](https://envirodatagov.org/publication/a-sheep-in-the-closet-the-erosion-of-enforcement-at-the-epa/). **You can make a regulation, but what happens next?**

**JONATHAN**: **The economist in me really loves the idea that the thing that the government is somehow collapsing the rational with the moral** to make it so incentivized or disincentivized that the good thing is the thing that you get. But it's really hard to predict all the ways people will figure out how to do the bad thing without facing penalties.

We need to figure out both how to make it cheaper for people to be compliant, and also make it more expensive to not do that right thing.

It feels like one of the most useful things that government can do is **explicitly rebalance an equation that is unbalanced**. But at what point does that get undercut depending on who's in power and their actual commitment to trying to get into a specific outcome?

I do wonder what negative ramifications it could have to create more personal culpability. There's this counterbalance of, to what degree are we okay just solidifying Facebook's lead here? **The hurdles for new entrants into the space will be quite high.**


## Spreading the ideas

**GREG**: How can I talk to people about the risks of deanonymization?

**KELSEY**: You said you feel like you've been the first person in a lot of these spaces to think about harms that aren't just legal harms. I feel very similarly in some of my technologist spaces. Technologists often get their tech roles because they already have access to the materials and the community. Some of the people building tech just haven't thought far beyond how cool it is that you can do the thing. I've had a lot of conversations that sound like the ones you’re describing.

What you’re doing, **integrating into different communities to ask these questions,** is a source of hope for me. That's what I want Data Together to be too, for people, a space to really think about this stuff.

**GREG**: I feel like we need grief counseling for technologists. **More people need to go through the process of mourning for the internet that we grew up believing in, and for the notions that inspired us to do this work.** We have to grieve. We have to let it go, and see what comes up through that process. What are we left with?

---

*Data Together is a community of people imagining a better future for data. We engage in a monthly [Reading Group](https://github.com/datatogether/reading_datatogether) on themes relevant to information and ethics. Participants’ backgrounds range decentralized web protocols, data archiving, ethical frameworks, and citizen science.*

*This reading group is something your own collective can do too! We encourage you to draw on [our notes for this month's topic](https://github.com/datatogether/reading_datatogether/blob/main/notes/semester_03_2020/5-privacy-2020-09-22.md). Our notes list readings, call out themes, and suggest discussion questions.*

*This blog post is derived from our conversation, but is not a replica of it; we rearrange and paraphrase throughout. You can view the recorded call [here](https://youtu.be/Qiw-WKBQ8A4).*
