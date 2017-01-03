![AdonisJs Discussion](https://cloud.githubusercontent.com/assets/2793951/20223951/43af9f1e-a83c-11e6-8275-acd669c425f5.png)

Over the past few months, the AdonisJs community has grown to a few hundred users and there have been lots of random requests by everyone in the community.

This repo is a place to share those thoughts and get them into action resulting in improving the eco-system.
For bugs, bugfixes, or other minor improvements to Adonis Framework or 1st party feel free to submit Issues and/or Pull-Requests to the correct repo.

# Your First Feature Proposal

For your first contribution or request we recommend [submitting an Issue](https://github.com/adonisjs/discussion/issues/new) describing your proposed feature.
From there, one of the contributors will help turn your Issue in to a full RFC for review and discussion!

---

# What is an RFC?

Some framework features, changes, or tools have a large impact on existing applications as well as the learning and documentation process needed to support these changes.
Often it can be hard to properly make these types of decisions without full knowledge of the existing implementation and other community efforts.
The RFC process allows for a greater consensus among the Adonis community before implementation and integration of new changes.

The "RFC" (request for comments) process is intended to provide a consistent and controlled path for new features to enter the framework.

[Active RFCs](https://github.com/adonisjs/discussion/pulls)

## When to Follow This Process

RFCs should be created for any "substantial" change to Adonis, Lucid, Ace, 1st Party Packages, or the documentation.
Examples of "substantial" changes might include:

* A new feature that adds, removes, or changes methods or classes: creating a new API surface
* The removal of a feature to a separate package
* The introduction of new conventions
* Changes in project structure
* New 1st Party Packages

Changes that do not require an RFC:

* Refactoring, renaming private variables
* Updates to comments
* Minor version updates to dependencies
* Additions that will only be noticed by core contributors and not addon authors or Adonis developers

If you submit a PR or Issue to an Adonis package repo, you may be requested to submit an RFC or issue to the discussion thread first to ensure consensus.

## Gathering Feedback

Discussion is the main driver for successful Open Source communities.
If you need help composing an RFC, create an Issue within this repo to begin a high-level discussion with the goal of creating a formal RFC.

Also feel free to reach out to community members on the [Adonis Gitter](https://gitter.im/adonisjs/adonis-framework) for help creating and submitting an RFC.

## The Process

To make a major feature change to Adonis, an RFC must be accepted and merged into the discussion repository.
At that point, the RFC may be implemented and included in the framework.

To submit an RFC

* Fork the Discussion Repo http://github.com/adonisjs/discussion
* Copy the `0000-template.md` to `text/0000-my-feature.md` (where `my-feature` is a descriptive short name for your proposal, *don't assign a number yet*)
* Fill in the RFC. Put care into each section (especially the "How We Teach This" section) as RFCs that do not present an attention to feature design will likely be closed or asked to rework.
* Submit a pull request. During this time, the RFC will receive feedback from contributors and community members. At this time, you may be asked to revise and push changes to your RFC.
* Build and iterate on feedback. RFCs that have more feedback and consensus are more likely to be accepted into the final framework.
* Eventually a core team member will flag the pull request as "final comment period". This period will be 7 days for final discussion.
* Significant changes during the "final comment period" may trigger a new 7 day period of commenting.
* Any RFC may be rejected by the core team based on public discussion or conflicts with other features or RFCs. A comment will be made on the pull request detailing the reasons the RFC was rejected, and the associated pull request will then be closed.
* At the end of the "final commend period", an RFC may be accepted by the core contributors and merged into the discussion repository. At this point the RFC will be considered "active" and implementations can be merged into the respective package or core repository.

## RFC Lifecycle

Once an RFC becomes active, the PR will be merged and an implementation issue will be opened, authors may implement it and submit the feature as a pull-request to the respective repo.
RFCs that are in the "active" stage may not be implemented, and implementations of "active" RFCs may not be merged in to the framework.

Modifications to existing "active" RFCs can be made via pull requests to further align RFCs that are still "active" but have not been implemented.

## Implementing RFCs

RFC authors are not required to provide implementation.
Of course: third party packages, example implementations, or proof-of-concepts are welcome and can be linked to in the RFC.
These can be used directly or used to influence the final implementation of a proposed feature.

If you are interested in working on an RFC implementation or know of design decisions that may help in the implementation of the proposed feature, feel free to comment on the associated issue.

## Review Process for RFCs

Each week, the core contributors will attempt to review some of the open RFC pull requests.
Also, community members will attempt to help transfer issues into RFC format.

Each accepted RFC will have a champion who will represent the feature and the progress.

The Adonis RFC process owes its inspiration to the [Ember](https://github.com/emberjs/rfcs) and [Rust](https://github.com/rust-lang/rfcs) RFC process.
