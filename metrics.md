# Metrics

* I like to count things.  
  * Story points help us understand our capacity and our velocity.    
  * Bug counts tell is if we have a quality problem.
  * Production support tickets tell us where we need to improve the system.
  * Performance metrics ensure our products work the way we need them to.
  * Monitoring ensures we aren't the last to learn about a problem.
* I don't want to be ruled by metrics, but they let us stay on top of the chaos.
* If our metrics ever seem to be driving the wrong behavior, we need to stop and talk about it.  See [Feedback](##Feedback)

## Output Metrics

### Story Points

<img src="img/points-dont-matter.png" alt="well, yeah"/>

I don't quite agreee with that.  

Sure, the dishonest can game it, but why would we work with dishonest people?

Story points are useful for estimating and planning, and have some utility for measuring outcomes. As an output metric, they are of some use in knowing if the team is producing.

### PR Throughput

PR throughput measures how many changes we each get to prodution.

Sure, we can game this by making lots of small changes, but lots of small pull requests are actually what we want. We want to make small, safe changes and iterate.

### PR Cycle Time

Stale PRs are hard to get merged because too much changes.  PR cycle time tells us if our PRs are too complicated or if we aren't putting enough emphasis on reading code. 

## Input metrics

### Coding days per week
I am a strong beliver that every developer should write and commit code every day.  

Averaging > 4.0 coding days per week seems like the right number to me: 

`52 * 5 - 10 days of holidays and 20 days PTO = 4.42 days per week.`  
