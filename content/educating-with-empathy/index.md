---
title: Educating With Empathy
weight: 500
---

# Educating With Empathy
The term “empathy” has unfortunately been diluted by years of marketing overuse,
but it is a fundamentally crucial concept that cannot be ignored. The term
captures the number one skill you need to employ as you build your Honest
Security education materials. Education without empathy is education that is not
personalized and becomes ill-suited for people who are from under-represented
groups. Security incidents are often a “weakest link in the chain scenario” --
they are unintentionally caused by the actions of uninformed employees. It's
imperative then, that security education is designed to reach everyone, no
matter their role or technical background.

## Recommendations Not Alerts

Since the primary actor achieving the organization’s security goals is the
end-user, Honest Security does not generate alerts, alarms, or failures, it only
generates recommendations.

Recommendations embody the values of Honest Security because they do the
following:

*   Do not come pre-loaded with negative value judgement (unlike the other
    terms)
*   Serve not only to instruct, but also inform and educate
*   Are an open invitation for further discussion and understanding

Expanding on the last point, Honest Security provides opportunities for
productive conversations about recommendations. These opportunities should
include contesting inaccurate or unhelpful recommendations, or even deferring
recommendation to a more helpful time in the future. Nothing makes a
recommendation feel more like a command than when there are no channels to
appeal or discuss its applicability.


## The Anatomy of a Well Written Recommendation

The following example is one of the more technical recommendations we use in
Kolide and have it enabled for all of our own employees, not just the software
engineers.

![An example Kolide SSH key notification](/images/ssh-key-notification-example.png)

I want to point out a few key elements in this recommendation. First, notice how
we explain the “why” using clear and concise terminology. We haven’t dumbed down
the language, but we also avoid using overly-technical terms that don’t add any
value.

Second, we include some language that short-circuits the most common arguments
that a defensive user might position against the recommendation. “Oh _this_ SSH
key isn’t really that important, I just made it as a test so it’s fine if it’s
unencrypted.” Yes that might be true, but we’ve made it so easy to encrypt. Why
not just do the right thing and make it a habit?

Third, we include step by step instructions that are customized to their
operating system and assume no prior experience. See the sentence, “You may not
see text being entered as you type your password in?” This is an example of
empathy in action. We are anticipating that this might be the first time the
user has ever interacted with the terminal and guiding them through a situation
where they might think something is going wrong.

Finally, we give them the precise command to enter into the terminal and a
feedback loop to verify that they did it right. They get confidence that the
problem is resolved and they even feel good that they were able to do it without
any help.

But suppose they need help or they object to the nature of the recommendation,
they are one button press away from contacting a human being and getting things
sorted. These aren’t commands to be followed, they are conversations.


## Using Empathetic Intelligence to Divine Novel Insights

Empathetic intelligence is what practitioners of Honest Security use to divine
security relevant insights about an organization, their digital assets, and the
people who use them.

Existing cyber security intelligence is typically generated by building
detection models derived by analyzing the patterns of attackers, their tools,
and their modus operandi. This intelligence is essential, but it’s not the whole
picture. Empathetic intelligence is generated by carefully considering the
common use-cases across different roles, identifying sources of risk, and
working forwards to generate the detection model.

In order to do this well, Honest Security must leverage the empathy of a diverse
set of human beings to generate these insights. By its very nature empathetic
intelligence cannot be automatically divined by artificial intelligence or
machine learning.

Using this very process at Kolide we’ve often created insights that unearth new
problems other security tools are completely blind to. At one organization, they
used Kolide to determine that their back-end engineers had a habit of
reproducing production bugs locally by downloading a copy of the database. Most
of them dutifully remembered to delete the file, but none of them remembered to
empty their trash. Unless you actually sit down with a developer and watch them
do this, you might miss that last detail.


## Recommendations Delivered At the Point of Performance

As previously discussed in the Goals section, the primary issue with classic
forms of education is that they deliver their recommendations out of context.

Most organizations have an IT acceptable usage document that they give to new
employees. In my experience, many of these documents are crafted with care and
contain valuable information that not only protects the company, but represents
good advice for people to be following even in their own personal lives. While
this type of all-at-once education style serves to check the box for various
compliance standards, it’s a terrible way to actually teach someone with any
hope of retaining the information.

The best time to teach someone a corrective action is when they are actively
making the mistake. Most folks would nap through a video presentation about how
to tie a figure-8 knot for rock climbing when they know there is a snowball’s
chance in hell they would even be in that situation. I guarantee you though that
same person will be all ears when those instructions are delivered moments
before they tie the knot that might save their life right before their first
climb. That moment is the point of performance; the time that training has the
maximum impact on the outcome.

Bringing this back to security, imagine you want your users to use a password
manager. In fact, you don’t want them to use any password manager, you want them
to use 1Password because you’ve done your research and you think they have the
best tool on the market and it matches your opinions on how to generate good
passwords.

Adding this recommendation under the “Password Hygiene” section of the training
powerpoint presentation three days _after_ employees have already set their
passwords is the right information delivered at the wrong time. Not only will it
not impact the outcome, they won’t even retain it.

However imagine a tool that reaches out to that very same user the moment they
download and attempt to install a different password manager. This helpful
recommendation explains that the password manager they chose was probably fine
but they might be interested in the fact that their company pays for 1Password,
a better product, and provides a helpful download link to get it right away.

This is relevant information delivered over a trusted communication channel
that’s already been established. It’s coming from an automated system so it
doesn’t feel like you are actively being watched. In fact, it feels like a
helpful service more than a tool that benefits the security team. Now the
chances are much higher this user retains this knowledge even in future
situations where the recommendation isn’t triggered.

Timing is everything, and Honest Security is about getting this timing right. It
uses the ground truth at its disposal to not only generate recommendations but
to also deliver them right when they are needed.
