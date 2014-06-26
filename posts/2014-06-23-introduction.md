## FOIA and Technology: a development blog

Welcome! We're a team at [18F](https://18f.gsa.gov) that's implementing part of the U.S. Government's [commitment](http://www.whitehouse.gov/sites/default/files/docs/us_national_action_plan_6p.pdf) to modernize the Freedom of Information Act. This commitment was made in late 2013, and we're starting work now on the implementation. We'll be writing here about the work and challenges along the way.

Our team is tasked with bringing technology to bear on this problem. We're *not tasked* with developing new regulations or legislation. Of course, neither policy nor technology exists in a vacuum, and they will depend heavily on each other.

### Where we are

18F works in the open, and so you can follow our work and project discussions on GitHub, centered at [18F's `foia` repository](https://github.com/18f/foia). You can use GitHub's "Watch" feature to be notified of ongoing discussion in that repository. We'll do as much project deliberation and stakeholder interaction as possible in GitHub.

Over time, the work will likely expand to include multiple repositories tackling more specific elements of the work, but our project-level discussions will remain at [`18f/foia`](https://github.com/18f/foia). So if you want to keep in close touch with the project, that's where to do it.

In *this* space ([18f.github.io/foia](https://18f.github.io/foia/)), the development team will write about our goals, plans, and progress. Compared to GitHub, updates will be less frequent and more narrative, but this is a **development blog** and so it will frequently be "in the weeds" and technical. You can use [our RSS feed](http://18f.github.io/foia/feed/) to follow our updates.


### Our plan

Our team's plan is to **reduce friction** for requestors and agencies in the FOIA process, create **scalable infrastructure** for making requests of a federated government of agencies and components, and **clear the path** for agencies to release public records.

To this end, we're developing, or looking at developing:

* A **consolidated FOIA tool** for requestors. A central, user-facing front-end from which anyone can start a FOIA request to an agency in the federal government.
* A **working request and response API and spec** for agencies to get and resolve FOIA requests. In other words, a common way for the tool to work with an agency's new or existing FOIA processing systems &mdash; at least at the very beginning and end of the process.
* An interface for **discovering public records** released through FOIA. At the very least, this means a public read API.
* A lightweight **application for FOIA offices** to track and process requests. It would use the same interoperable request and response API as described above.
* Tools to help agencies **efficiently prepare records ** for release. In particular, tools to make responsive documents accessible could increase the quality and quantity of publicly released documents &mdash; and be broadly useful in the federal government beyond FOIA.

That's a lot of stuff. We most likely won't end up choosing (or being able) to work on or finish all of them. But we think these are the areas that have the highest return on investment in using technology to modernize how the Freedom of Information Act functions in the United States.

And **we welcome your help!** 18F is an [open source team](#) working in the public domain &mdash; watch this space, and join us along the way.
