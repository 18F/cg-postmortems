# cloud.gov post mortems

**Note: If you're experiencing a problem with cloud.gov or you want to discuss an ongoing incident: check [the cloud.gov StatusPage](http://cloudgov.statuspage.io/) and visit #cloud-gov-support in Slack or email cloud-gov-support@gsa.gov. This repository and wiki are *only* for post-mortems after the incident has been closed.**

We hold a post mortem as soon as possible after a cloud.gov service disruption or other incident. We use a broad definition of incident; ITIL says "Failure of a configuration item that has not yet affected service is also an incident — for example, failure of one disk from a mirror set. The ITIL incident management process ensures that normal service operation is restored as quickly as possible and the business impact is minimized."

We keep our post mortems in [the wiki](https://github.com/18F/cloud-gov-postmortems/wiki) attached to this repo.

For more information on post mortems, check out:

* John Allspaw's [introduction](https://codeascraft.com/2012/05/22/blameless-postmortems/)
* This [great presentation](http://www.slideshare.net/danmil30/how-to-run-a-postmortem-with-humans-not-robots-velocity-2013) by Dan Milstein

### How we run post mortems - the short version

Before the post mortem we'll put together a timeline of the incident on the wiki, beginning at the time the incident was announced in Slack, and ending at the point we declared the incident over. Everybody is welcome to add their observations to the timeline, including which actions were taken when, the effects observed, and their understanding of the events.

1. The facilitator starts by reading [the retrospective prime directive](http://www.retrospectives.com/pages/retroPrimeDirective.html).
2. We review the timeline and add anything we have missed.
3. We analyze the factors that contributed to the incident.
4. We propose, discuss and prioritize ways to incrementally improve our systems, and to test these improvements.

We add the work that comes out of the post mortem to our backlog. We then schedule a meeting 2 months after the incident to review our progress.
