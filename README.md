# Superset Public Roadmap
## Overview
We have introduced this public roadmap with [SIP-XX](http://blank.org/), plese see the details for the motivation there. This document describes the parctical aspects of using and contributin to the roadmap.

### Target audience
Anyone who is intersted in knowing how Superset's functionality is being enanced and how it will be changing over time. This includes developers, end users and project sponsors.

### Disclaimer
The purpose of this content is to outline the general product direction for SUperset. It is intended for information purposes only, and may not be incorporated into any contract. It is not a commitment to deliver any material, code, or functionality, and should not be relied upon in making purchasing decisions. The development, release, and timing of any features or functionality described for Superset is subject to change witout notice.

## Contributing to the roadmap
### Add a new project for consideration
Anyone from the community can add a new proposed project to the roadmap: (see [How to organize the content in the roadmap](#how-to-organize-the-content-in-the-roadmap) )
> 1. Create a new issue in the [/superset-roadmap](https://github.com/benceorlai/superset-roadmap) repo using the [Roadmap Epic](https://github.com/benceorlai/superset-roadmap/issues/new/choose) template
> 1. Add the issue to the [project board](https://github.com/benceorlai/superset-roadmap/projects/1)
> 1. Add it to the "For consideration" column in the board
> 1. Optionally you may create a SIP or link an existin SIP to the epic
 
### Prioritization
When a new project is created, it will be placed in the **Inbox** column. As the project received feedback, the scope is defined and clarified it will be in the **Discussion** column.

For a project to happen (get "prioritized" in the roadmap), two things need to be in place:

> 1. The scope is clear enough to understand the functional benefits and user impact on a high level
> 1. A community member is willing to dedicate the effort and resources to make the project happen

When these conditions are met, the card is moved to the **Committed** column. The subsequent **In Development** and **Done** columns indicate the development status.

Cards in each column of on the board will sorted by the number of comments, the cards with the highest number of comments being at the top.

The Product Managers at Preset are offering help with grooming the Roadmap board and keeping it up to date on a weekly basis but anyone can contribute if they have the desire to do so.

## How to organize the content in the roadmap
### Project Epic
This is a Github issue in the roadmap repo, with the content of the body organized into specific sections:
1. A **summary** of the project, includin motivation, business need or user paintpoints
1. A description of the expected **outcome**
1. A description of the **functionality**

### Epics vs SIPs - what's the difference
In sort, an Epic is higher level and broader than a SIP. An Epic deals with the WHY and the WHAT, but leaves te HOW completely unanswered. A Epic will be translated into one or more (or zero) SIPs at implementation time, based on the [existing guidelines for SIPs](https://github.com/apache/incubator-superset/issues/5602).

### Milestones
A Milestone is a fixed "goal post" in the roadmap. Per [Github's documentation](https://docs.github.com/en/github/managing-your-work-on-github/about-milestones): "You can use milestones to track progress on groups of issues or pull requests in a repository.". In the Superset roadmap milestones can be used to track major releases or maturity stages of the project. (_Getting the milestone granularity will probably require an iterative approach to strike a goo dbalance between granularity and usability_)

### Labels
There are labels to be used on the roadmap items, to better organize them and make them searchable based on functional areas of Superset:

- Data (related to Databases, Datasets, Saved Queries, Executed Queries)
- SQL Lab
- Explore
- Visualizations (related to charts and visual representation of data)
- Dashboards
- System (functionality of the app as a whole (settings, navigation etc)
- Non-functional (features with no direct end user impact, e.g. code organization, architecture etc)
