# Working with me

A way for you to understand why I am here and for us to measure success. This is heavily inspired by [Rands](http://randsinrepose.com/archives/how-to-rands/) and others.

## Contents

- [My role](#my-role)
- [My assumptions about you](#my-assumptions-about-you)
- [Our team](#our-team)
- [Communication](#communication)
- [One-on-ones](#one-on-ones)
- [Feedback](#feedback)
- [Metrics](#metrics)
- [Meetings](#meetings)

## My role

Whether I'm your manager or your team lead, the job is the same at its core: help the team deliver awesome software.

That means I:

- Find, retain, and encourage really smart developers (that's you).
- Provide context.
- Destroy obstacles.
- Build prototypes, design systems, and review code.
- Am the face of the team to stakeholders.
- Do enough individual-contributor work to stay effective at all of the above and connected to the solutions.

## My assumptions about you

- You are good at your job.
    - If you weren't, you wouldn't be here.
    - I will still question you. When I do, it is because:
        - I'm trying to learn more about what you know and I don't.
        - I'm trying to be a sounding board and make sure you do your best work.
- You have more detailed knowledge than I do of what you are doing.
    - I have more context than you do. (Context is part of what I do here.)
- You will tell me if you are having trouble doing your job.
    - One of my main responsibilities is setting you up for success, not failure.
    - You will know before I do if you are not set up for success, so say something.
- You feel safe debating with me.
    - The best ideas are those that have been viewed from multiple angles and been the subject of debate and discussion.
        - Sometimes I will play devil's advocate for this purpose alone.
        - Sometimes I'm just being dense.

## Our team

### Core needs

[Adapted from Google's ideas on what teams need](https://rework.withgoogle.com/blog/five-keys-to-a-successful-google-team/):

- **Psychological safety** — Can we take risks on this team without feeling insecure or embarrassed?
- **Dependability** — Can we count on each other to do high quality work on time?
- **Structure & clarity** — Are goals, roles, and execution plans on our team clear?
- **Meaning of work** — Are we working on something that is personally important for each of us?
- **Impact of work** — Do we fundamentally believe that the work we're doing matters?

### Vision

- We are all contributing at a high level.
    - We deliver features that bring joy to our customers or at least remove sources of pain and frustration.
    - To our stakeholders, we are big damn heroes.
- We take control of, and responsibility for, our own destiny.
    - We identify challenges and opportunities and come up with solutions.
    - If something is beyond our control, we look for ways to get it under our control or get help.
- We help each other.
- We hold each other accountable.
- We can expect excellence in ourselves and each other.
- We assume positive intent.
- We always ask "why?" and especially "Why can't we just make it be better?"
- We constantly learn and adapt.
    - If something isn't working, we change it.
- All of this is both fun and sustainable.

### Attendance

- We work a reasonable number of hours.
    - We occasionally work overtime during crunch periods.
    - But we understand that extended overtime...
        - Makes us unhappy.
        - Actually reduces productivity.
- We respect our team members by being available, being on time, and giving people time to adjust.
    - We try to give warning when we won't be in.
    - Life happens: people get sick, child care falls through, furnaces give out, so we are flexible.
        - But we need to give our team members warning.
        - If we will take a day, we give notice as soon as we know. We announce it and put it on the vacation calendar.
    - When one person is remote for a team meeting, everybody is remote for that meeting.
- When we do get sick...
    - We take care of ourselves by resting when we cannot or should not work.
    - We take care of our team by working from home when we are contagious.
- Nobody [goes dark](https://blog.codinghorror.com/dont-go-dark/) for an extended period.

### Practices

**Code**

- We work in the open.
    - Everybody tries to write and commit code every day. Delivery is a muscle. We exercise it.
    - Most people have a PR most days.
- Everybody reviews code.
    - Your input is valuable.
    - Do not hesitate to review code written by more experienced people.

**Testing**

- We own the quality of our code.
    - We test our own work *before* anyone else can find our mistakes.
    - We think about testability as a first-class concern.
    - We test 100% of the code we think needs testing.
    - We test 0% of the code we don't think needs testing.
    - We can depend on our tests.

**Standup**

- We talk about what we have been doing since our last stand.
- We talk about what we plan to do before our next stand.
- We talk about blocking issues.
- We talk about discovered tasks or complications.
- We review our collective situation.
    - Do we have open PRs that need review?
    - Are we likely to exceed or miss sprint commitments?
        - Do we need to communicate to our stakeholders?
        - Do we need to find additional work?
- We talk about any issues of common interest.
    - e.g. "Remember, I'm off all next week so if you need me, get me before 3."

## Communication

- Face to face is best.
- Emails — I will reply in < 24 hours.
- Slack — you should expect to get an answer right away. I will do my best.
- If it ever feels like we are not communicating, grab me and let's hash it out.
- I feel very strongly that teams need to over-communicate their progress.
    - Transparency builds trust.
    - We should be open and transparent about our successes and our failures.
    - Typically, this takes the form of a weekly status email going to all stakeholders.

## One-on-ones

- These are primarily your time to talk about whatever you want.
- Secondarily, they are for me to talk about what I want to talk about, but you come first.
- They shouldn't be status updates unless you really want to talk about status updates.
- These are flexible depending on our schedule, but we need to have them.

## Feedback

- Honest, compassionate feedback is one of the most important tools we have.
- This needs to go both ways.
    - I'm going to make mistakes.
        - I expect you to tell me when that happens.
        - Yeah, it might be hard, but I'm counting on you.

## Metrics

I like to count things.

- Story points help us understand our capacity and our velocity.
- Bug counts tell us if we have a quality problem.
- Production support tickets tell us where we need to improve the system.
- Performance metrics ensure our products work the way we need them to.
- Monitoring ensures we aren't the last to learn about a problem.

I don't want to be ruled by metrics, but they let us stay on top of the chaos. If our metrics ever seem to be driving the wrong behavior, we need to stop and talk about it. See [Feedback](#feedback).

### Output metrics

**Story points**

<img src="img/points-dont-matter.png" alt="well, yeah"/>

I don't quite agree with that. Sure, the dishonest can game it, but why would we work with dishonest people? Story points are useful for estimating and planning, and have some utility for measuring outcomes. As an output metric, they are of some use in knowing if the team is producing.

**PR throughput**

PR throughput measures how many changes we each get to production. Sure, we can game this by making lots of small changes, but lots of small pull requests are actually what we want. We want to make small, safe changes and iterate.

**PR cycle time**

Stale PRs are hard to get merged because too much changes. PR cycle time tells us if our PRs are too complicated or if we aren't putting enough emphasis on reading code.

### Input metrics

**Coding days per week**

I am a strong believer that every developer should write and commit code every day. Averaging > 4.0 coding days per week seems like the right number to me:

`52 * 5 - 10 days of holidays and 20 days PTO = 4.42 days per week.`

## Meetings

- We can always do an informal "help me talk through an idea" without a formal agenda. (Although, in reality the agenda is "Let's talk through connection pooling" or whatever.)
- Any meeting over 15 minutes needs to have an agenda.
    - If I call a meeting > 15 minutes with no agenda, call me out.
    - If possible, we should have a common set of notes for meetings so we know who agreed to what.
    - Meetings produce artifacts: notes or even screenshots of whiteboards.
- Story grooming is important to get everybody on the same page.
- Retrospectives are important to help us improve.
