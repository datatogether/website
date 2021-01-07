---
title: "Discussion: Algorithmic Racism & Environmental Data Justice (March 2020)"
tagline: "A Data Together 2020 Reading Group Discussion'"
date: 2021-01-11T07:00:00-20:00
draft: false
authors: ["Kelsey Breseman", "Data Together"]
---

How do choices in technology design and implementation reflect and impact broader social structures? We explore these questions starting with readings from environmental data justice and studies of algorithmic racism.

<!--more-->

## Readings

* EDGI EDJ group, 2019: [EDJ Syllabus](https://envirodatagov.org/announcements-rollout-of-environmental-data-justice-syllabus-and-upcoming-ejxyouth-summit-online-event/)
* Sasha Constanza-Chock, 2018: [Design Justice: Towards an Intersectional Feminist Framework for Design Theory and Practice](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3189696)
* EDJ (Lourdes Vera, Dawn Walker, and many more, EDGI), 2018: [When Data Justice and Environmental Justice Meet: Formulating a Response to Extractive Logic Through Environmental Data Justice](https://drive.google.com/file/d/14erRGMYNgc6b2iJNwXGGX0leQigFdAHm/view)
* Mark Wilkinson, Michel Dumontier, and many more authors, 2016: [FAIR Principles for Scientific Data Management and Stewardship](https://www.go-fair.org/fair-principles/)
* Research Data Alliance International Indigenous Data Sovereignty Interest Group, 2019, in The Global Indigenous Data Alliance: [CARE Principles for Indigenous Data Governance](https://static1.squarespace.com/static/5d3799de845604000199cd24/t/5da9f4479ecab221ce848fb2/1571419335217/CARE+Principles_One+Pagers+FINAL_Oct_17_2019.pdf)
* Max Liboiron, 2017: [Pollution is Colonialism](https://discardstudies.com/2017/09/01/pollution-is-colonialism/)
* Dan Robitzsky for Futurism, 2019: [TikTok Secretly Hid Videos by Fat, LGBTQ, Mentally Disabled Users](https://futurism.com/the-byte/tiktok-hid-videos-fat-lgbtq-mentally-disabled)
* Edward Ongweso Jr. for Vice, 2019: [Racial Bias in AI Isn’t Getting Better and Neither Are Researchers’ Excuses](https://www.vice.com/en_us/article/8xzwgx/racial-bias-in-ai-isnt-getting-better-and-neither-are-researchers-excuses)
* Rebecca Heilweil for Vox, 2020: [Why Algorithms Can Be Racist and Sexist](https://www.vox.com/recode/2020/2/18/21121286/algorithms-bias-discrimination-facial-recognition-transparency)

---

{{< rawhtml >}}
<img alt="Top-down view into metal pins lit in red/purple" src="/images/blog/07_algorithmic_racism_edj.jpg" width="100%">
{{< /rawhtml >}}

*Photo by [Michael Dziedzic](https://unsplash.com/@lazycreekimages?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)*

---

## Introducing the readings

**LOURDES**: These readings are pillars that hold up my personal work, and inform the environmental data justice theoretical framework as a whole.

**[Design Justice](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3189696)** by Sasha Constanza-Chock is the first time where I started to really think about **design, and in this case building environmental data infrastructure, in terms of intersectionality**. When I went to the data justice conference in Cardiff, Constanza-Chock gave the keynote address, and they talked about going through airport security as trans. When you go through those giant scanners, they click on whether you're male or female. So people who are trans always get pulled to the side. I'm thinking about that in terms of intersectionality, and thinking, what if you're trans and a person of color as well?

**Design Justice positions bottom-up design as a response to these types of issues.** It asks, what does design mean? Is it engineering as well as planning? How does that inform or work within environmental data justice and building new tools that are from the lens of community members?

That takes me to the **[FAIR](https://www.go-fair.org/fair-principles/) and [CARE](https://static1.squarespace.com/static/5d3799de845604000199cd24/t/5da9f4479ecab221ce848fb2/1571419335217/CARE+Principles_One+Pagers+FINAL_Oct_17_2019.pdf) principles**. I think those are a really good concrete guideline for data scientists, technologists, and scientists for working with vulnerable populations. These principles are really popular with and come out of the [US Indigenous Data Sovereignty Network](https://usindigenousdata.org/).

Recently, I wrote one of my comprehensive exam papers on how scientists can apply the CARE principles to genomic research. **There's a long history of extractive research that has either killed people or perpetuated ideas of racism and sexism and heteropatriarchy**, and also gets caught up in this cycle of research being co-opted by capitalism and being for-profit instead of for the interests of the people.

And then **[Pollution is Colonialism](https://discardstudies.com/2017/09/01/pollution-is-colonialism/)** really reoriented me towards **the connection between environmental hazards and land**, and how that's all tied into and produced by a history of the state being built on native land, and through the appropriation of this land, in order to generate capital.

Throughout all these readings, **systems of power are taking various types of capital**, people's information, people's health and livelihood, in order to produce academic papers, money, whatever feeds their power. And I'm part of this too.

Rico, do you want to reflect on the other articles?

**RICO**: Yes, I can start with my own reason for being interested in this line of study. I think, as someone who has a political background, I've spent plenty of time talking to people who believe that racism exists, but localize it to being an interpersonal phenomenon. **They think that because systems aren't persons, systems don't encode those biases**. It's so hard to say, Hey, listen, Uncle Jim. Listen, man, the system is racist. He's like, Look, I don't doubt that there are politicians and there are DMV workers who are racist, but the system is not the problem.

Especially in a conversation where you're trying to change someone's mind, it's really hard to walk through how a whole system gets shaped and born and fortified with all these small decisions.

I'm particularly interested in **applications of algorithms for very simple-to-understand life purposes, that carry with them the biases of the data that are used to generate them, or of the creators of the algorithms themselves**.

I think this is a really easy to understand story: Black Americans are 12 to 15 percent of the American population. That means that if you're trying to source black faces and arms and bodies, to teach a car to stop when it sees that, if you're doing a good job, 12% of the images you're getting to the algorithm to train on are Black arms and legs et cetera. So that means it's going to be significantly less talented at spotting those things, and therefore it's going to stop just a little bit slower.

All of these things feed into a real danger that is "not the fault" of the researchers who went and just got as much data as they possibly could, or "not the fault" of the researchers who wanted to make sure that the data that they got was representative of the population that is going to be impacted by these cars. If they say, this is an algorithm for cars that are driving in America, well, 15% of Americans are Black. So we're going to have 15% of the images that we train our algorithm on to be Black. And that presents a real problem.

You can look at this as a summation of a lot of well-meaning decisions at different points in the chain that results in a really horrible outcome where our black neighbors are walking down the street and not sure if an autonomous vehicle is going to stop for them when they're crossing the street. And that is systemic.

It's not specifically tied to one person saying a bad joke, which we all so easily define as racism. **It's part of a system of norms that develop, that have shaped whiteness in America as default.** **Unless we're consciously working to reverse that, we're on the verge of amping up everything about our society considerably by the encoding of existing biases into large-scale algorithms.**

**KELSEY**: In [A Human Algorithm](https://www.goodreads.com/book/show/45029192-a-human-algorithm), the author Flynn Coleman makes the argument that this is the only moment in which we can influence whether algorithms have our same biases; pretty soon, machine learning will work faster than human ability to feed machine learning.


## How neural networks learn bias

**RICO**: As a society, we're beginning to laugh at people that say they don't see color. **I think the people who are closest to “not seeing color” are the ones who make sure that they see it.**

I worked at a fashion tech startup before working at Qri. We were training computer vision models on how to extract attribute data from fashion product images—for instance, this is a medium gray men's sweater—from a picture of a model wearing it.

When you get started on a project like that, you need 10,000 images that are classified on a taxonomy. You feed that data into a neural network; the computer “learns” from those images.

Imagine you have a young child who fell off another planet and didn't speak any language that you spoke, and all you did was show them a picture and said blue, and another picture and said green. Eventually, after thousands and thousands of images, they figure out what green means and what blue means. That's essentially what you're doing with computer vision. But **without giving more of the context of, green purse, a white woman, tall, whatever, it's going to be blind to all those other aspects**.

When I began working there, almost all of the models that were using were white. That was probably the most cost-effective way to make sure we got lots of pictures and lots of models, because most models are white. I was curious about how the algorithm would do trying to identify a blue bag with someone who's not white. In order for the algorithm to be colorblind, it needed to see: this is a blue bag and it's being carried by a black person. This is a blue bag and it's being carried by a brown person. This is a blue bag and it's being carried by a white person.

Like many tech startups, we weren't doing life or death work. But **the approach that we were taking encoded** **the wrong kind of colorblindness, where I can't tell you what color this bag is because a black model is holding it**. That's a big problem.


## Fast-paced work as an antagonist to anti-racism

**KELSEY**: I come from a startup background too. And **one of the things that you really, really feel when you're in a startup is how urgent it is to prove your product is a success, with as little time and money as possible**.

I wish Brendan [Qri’s founder] was here because we've talked about this a little bit. One of the things that Brendan and I have talked about is how different it is when he works at Qri versus when he works at EDGI, because within EDGI, one of the things that we do is work very slowly. We think about the problems and we take a lot of time and distance and thought, and it means that we don't get things done on a product-style speed.

For those of us who really enjoy making product, it's maddening. I like building things fast, testing them in the field when they’re still made with foam and duct tape. It feels really powerful to do as much as you can with the little you have. But **there's a huge value in doing things slowly**, and in trying things that you don't complete because you've decided that it wasn't the right thing.

One of the challenges I had to pause on in my startup time was, can we, as a handful of people trying to build a product, really afford the extra outreach time to hire for diversity? But can we afford not to? You are in such a rush that you want to cut corners. But every decision you make, **you are deciding what matters for the parts of society you have influence over**.

**KEVIN**: Even EDGI has that problem. Hiring is—it's not that you want it to be fast, but you don't want it to be too slow either, because it drains energy. That becomes an excuse to use shortcuts, like “we don't have time for it”, so we'll just hire the easiest thing. And **the easiest thing is to stay within our networks** and the people that we know already.

**LOURDES**: This whole fast pace thing– this is our life in this society. We are always going, ch-ch-ch-ch—and that's what neoliberalism is about, is this idea of being extra efficient, maximizing your profits. Getting, and always needing, more money.

Sometimes you have to take a step back. I think Coronavirus is helping us do that, helping us say, Wow, there are things that are deeply flawed in the systems that we've created for ourselves, but we also need them. How do we live outside of them now?

**KELSEY**:  And now that people are staying at home—I’m out in the woods; I can go outside. But in the city, maybe you're in an apartment complex, and there’s really no place to go. So people are living online more than ever. But **if everything we do is moderated through a screen and especially through the internet**—who controls the internet? And how?


## Accidental encoding of antipatterns

**RICO**: The thing I'm most afraid of is that it's either not a person, not a good person, or not enough people.

I'm going to boil that big idea of “controlling the internet” down into something small, my LinkedIn network. Let's say 25 of my friends get a new job. How do they choose the five to suggest that I congratulate? That's a decision made by an algorithm that encodes some arbitrary set of behaviors. I don’t know what those behaviors are; is it based on the last five people I've messaged, or the five people I haven't messaged for the longest time? If I were to pass on two women in a row, it would then stop recommending that I "Say hello" to women—is that one of the attributes it’s tracking?

**It needs to not just encode just your previous behaviors, because a lot of our previous behaviors are based on the networks that we grew up with**. A lot of us have been locked into these segregated worlds, and **those worlds are not going to change unless those algorithms are cracked into.**

Whenever I hear a Spotify song that I don't like, I'm worried about disliking it, because then I think I'm never going to hear that artist again. **I’m afraid the computer is going to overlearn from my input**.

**LOURDES**: I was thinking about the same thing with Spotify. I like too many bands that are all white dudes. But I like the music that I like. But when I like things, then Spotify learns, she really likes white boy punk bands from the 90s. And so they recommend some modern white boy punk bands. I've made a rule for myself that if it's all white cis white dudes from the past five years, I'm not listening to it.

**KELSEY**: I would expect that Spotify, LinkedIn, Facebook, all of them probably do specifically call out people and bands and stuff as white, male, female, Latina, whatever. In most forms of machine learning, we do actually choose what parameters are being looked at. We pick these ones because they're easy to identify. But they are in many ways the least interesting.

**LOURDES**: But then we're talking about the fact that they're not chosen. **There is no equity in how these algorithms are built.** There's no algorithm in Spotify that says, this person's listening to too much music by white people; we're gonna suggest some bands by people of color.

**RICO**: I bet most datasets at Spotify are not coded by the race of the author; it's just the genre, ‘90s punk bands were mostly white. Those things get correlated tightly, so when you keep listening to that, you keep getting whiter audiences. In that sense, because the algorithm was colorblind, it started pushing white punk ‘90s music.

If somebody on the engineering team decided to tag artists by their predominant race and then weight things so the algorithms put bands in front of you that are a little bit more local to your place—there are other categories that are not race specific, that can get other kinds of music in front of you.

**LOURDES**: Before people started writing about this, **the act of tagging a band with their race, like how white or how not-white they were, would be perceived as racist.** And then the question of, who are you, some white dude coder, to determine the race of a band? So then you would have forms when the band puts up their information on Spotify that says, What's your demographic? And then the band will wonder, why is this a question here?


## Directly challenging patterns of bias

**KELSEY**: When I was in the library recently, I picked up a couple fliers that were movies and books centering indigenous voices—#ownvoices, where you're specifically reading books that are written by the demographics of the people that they're about.

In our modern society, not everybody is interested in reading for diversity, but there's a huge population that is. **I think that there's a market available for recommendation engines that specifically give you stuff that's outside of the dominant narrative.**

**LOURDES**: I just searched on Spotify, "punks of color", and there is one playlist.

**I think it does start with putting together playlists, putting together book lists, curating things.**

**KELSEY**: One of the things that I was doing for a while was, my local library has a "recommended this book" option to suggest materials for purchase. So I was going through book lists like the #ownvoices lists and suggesting them to be stocked in the library. It felt really powerful because otherwise people might not even know they existed.

**We have influence over how people think and perceive what normal is, just by creating models of it.**


## Well-intended antipatterns

**RICO**: Switching gears a little bit, I shared the article “[TikTok Secretly Hid Videos by Fat, LGBTQ, Mentally Disabled Users](https://futurism.com/the-byte/tiktok-hid-videos-fat-lgbtq-mentally-disabled)”. TikTok moderators were being alerted when a TikTok-er with Down syndrome had at least 6000 people watching their video. They were cued to check in and make sure that people aren't making fun of that person.

I'm fascinated by the unintended consequences of policies and practices meant for good. You can make all the reasons why that moderation alert is a necessary process. At the same time, imagine being someone with Down syndrome and knowing that **if you get a certain level of popularity, you’re going to have moderators in your feed immediately**. I'd feel othered by that.

We're fumbling through a lot of this: best intentions, tech as it is, the world as it is. And the output is really messy.

**LOURDES**: That is patronizing in a way: that someone has to look out for you.

**RICO**: Right.

**LOURDES**: But, I love it when people intervene to tell people off.

There exists an organization of white folks who come in and intervene in threads of racist people being racist, to take the load off of the person of color in that thread. They'll step in and educate. I think that's cool. That's a good way for white people to engage in solidarity. But it's only when they're requested.

I think that goes back to Design Justice: **you ask people if they want to contribute. But you don't want to put the burden of contributing on people of color**; you want to give them the space and facilitate their contribution. And if they want to take a leadership role, it's open but not not pressed.

**KELSEY**: It could actually be a really cool feature if TikTok, when you signed up, said, Hey, are you a member of XYZ vulnerable population? Because if so we can prioritize moderation requests that you submit.

**RICO**: I'm already 35 and race has been a problem in my country for 500 years, and a problem in the world for far longer than that. I think I've accepted the fact that it will be a big part of the life of many of the people of the country that I live in for the rest of my time here. And so I'm keeping the goal of erasing all of that for another lifetime, just reducing the worst parts of it.

Bringing us back, the fact that autonomous cars can't as easily identify a black neighbor of mine is a majorly scary problem. And **that seems really both really scary and really fixable**. And so, **I personally want to focus efforts on where those two things intersect.** Let's get the big dangerous things reduced however we can.


## Transparency as a first step forward

**KELSEY**: I'm really curious about how folks think we can get around algorithmic bias given that machine learning is definitely happening.

**KEVIN**: Just give me a chronological timeline again. And no ads. Don't push anything. Just let me find it through serendipity.

**RICO**: **Transparency** sounds like the very first step. **If you knew exactly how it worked, you could adjust your behavior accordingly, or maybe ask for changes.**

**LOURDES**: Big advertising is a  problem. But the fact that you can put ads on Facebook for not a lot of money... it really helps. If EDGI wanted to put up an ad, it would only cost a couple bucks. That's really cool. But then people can also spread misinformation using that and can also target, say, African American populations with misinformation and do damage that way.

**KEVIN**: Yeah, it's really dangerous. That kind of weaponized targeting leads me toward wanting to use federated social networks. **Does it make sense for me to be connected to somebody I don't know across the world, or should I be having social networks with my neighbors?** On [Scuttlebutt](https://github.com/datatogether/reading_datatogether/blob/main/notes/semester_03_2020/scuttlebutt.nz) you can see folks that are on the same network or near you. Is there a place for smaller social networks, instead one ginormous Facebook where we're all on the same thing?

**RICO**: **That's a sword that cuts both ways, because race and affluence tend to have geographic boundaries.** People who have the same genuine interest in keeping their world a little smaller, if they grew up in white worlds, are then keeping their all-white worlds a little more tightly wound, unless you're proactively braking against that.

There's [a new algorithms officer for New York City](https://www.cityandstateny.com/articles/policy/technology/why-new-york-city-is-getting-an-algorithms-officer.html). I don't know exactly what their job and powers are. But I think one of the big missions of the people who cared about that position being created, and shaped it, is that **for any algorithm that goes into a city process, the algorithm and the underlying training data (if it's machine learning) is made public**, so that at least people can take a look at it.

Kevin, your point: **Do I get to tune the algorithm for myself?** The first step would be at least understanding how it works.

There was a [predictive policing](https://www.brennancenter.org/our-work/research-reports/predictive-policing-explained) effort in Chicago. They crunch all this data and they say, Look, you are likely to commit a crime or be the victim of a crime, based on these factors. We're knocking on your door just to check to make sure that you've got housing, a job, et cetera, because these are the four things that, if you get those, you're much less likely to be on our list in the future.

This is wildly controversial for all the reasons that are probably obvious to us. A lot of people in communities that had their doors knocked on, some of them are like, Why the fuck are cops knocking on my door like this? Other people are like, Oh my god, I'm so glad that they're checking in to make sure that my housing is safe, and they helped me make a complaint about my landlord.


## Environmental harms and systemic bias

**KEVIN**: Some stuff that I was reading made me think about the [ECHO](https://echo.epa.gov/) database [the EPA’s public database of permit compliance and enforcement]. Basically these permits are permissions to pollute [a certain amount], right? **How are the thresholds determined?** How long ago were these determinations made? Were they thought about in aggregate, like, it's okay for one power plant to pollute that much, but what if we had ten of them next to each other? Is there any thought to the cumulative effect of all of them being allowed to pollute in that area? Do you know that stuff, Lourdes? I know you've been studying this.

**LOURDES**: Yeah. **Those thresholds are generally based on white male bodies.** They also are based on the idea that the dose makes the poison—that there’s a dosage at which the pollutants don’t cause harm. That's totally not reflective of reality.

Adding to this is the fact that **companies prevent certain science from happening**, what STS [science, technology, and society] scholar Scott Frickel calls "[undone science](https://www.jstor.org/stable/27862473)". There's just loads of science about these chemicals that isn't done.

**KEVIN**: I really like the Design Justice article because it asks those questions: **why aren't the people being affected involved in the determination of these permits and how they work?**

**KELSEY**: Specifically, one of the things that I think is really important about understanding various forms of bias, including racism, is **the privilege or right to not worry about it,** because things are just made with you in mind.

**KEVIN**: For me, design is problem solving, whatever realm that happens to be. It could be applications, it could be engineering, design can happen in all forms.

I also like that you shared the CARE principles alongside the FAIR principles. The FAIR principles were really data-centric, but the CARE principles were talking about the communities or what would happen with data.

Thinking about design justice makes a lot of sense in this realm: **how do we make sure that these communities are brought forward at the very beginning of any problem solving exercise, problem solving process?**

---

*Data Together is a community of people imagining a better future for data. We engage in a monthly [Reading Group](https://github.com/datatogether/reading_datatogether) on themes relevant to information and ethics. Participants’ backgrounds range decentralized web protocols, data archiving, ethical frameworks, and citizen science.*

*This reading group is something your own collective can do too! We encourage you to draw on [our notes for this month's topic](https://github.com/datatogether/reading_datatogether/blob/main/notes/semester_03_2020/1-algorithmic-racism-edj-2020-03-17.md). Our notes list readings, call out themes, and suggest discussion questions.*

*This blog post is derived from our conversation, but is not a replica of it; we rearrange and paraphrase throughout. You can view the recorded call [here](https://youtu.be/0Vg-A9eK-14).*
