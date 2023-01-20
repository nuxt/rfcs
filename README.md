# Nuxt 3 RFCs

👉 https://github.com/nuxt/nuxt/discussions/categories/rfcs

# Nuxt.js RFCs

Many changes, including bug fixes and documentation improvements can be
implemented and reviewed via the normal GitHub pull request workflow.

Some changes though are "substantial", and we ask that these be put
through a bit of a design process and produce a consensus among the Nuxt.js
core team.

The "RFC" (request for comments) process is intended to provide a
consistent and controlled path for new features to enter the project.

## When to follow this process

You should consider using this process if you intend to make "substantial"
changes to Nuxt.js or its documentation. Some examples that would benefit
from an RFC are:

   - A new feature that creates new API surface area, and would
     require a feature flag if introduced.
   - The removal of features that already shipped as part of the release
     channel.
   - The introduction of new idiomatic usage or conventions, even if they
     do not include code changes to Nuxt.js itself.
   - Introducing new core packages

The RFC process is a great opportunity to get more eyeballs on your proposal
before it becomes a part of a released version of Nuxt.js. Quite often, even
proposals that seem "obvious" can be significantly improved once a wider
group of interested people have a chance to weigh in.

The RFC process can also be helpful to encourage discussions about a proposed
feature as it is being designed, and incorporate important constraints into
the design while it's easier to change, before the design has been fully
implemented.

Some changes do not require an RFC:

  - Rephrasing, reorganizing or refactoring
  - Addition or removal of warnings
  - Additions that strictly improve objective, numerical quality
  criteria (speedup, better browser support)
  - Additions only likely to be _noticed by_ other implementors-of-Nuxt.js,
  invisible to users-of-Nuxt.js.

## What the process is

In short, to get a major feature added to Nuxt.js, one usually creates an issue that will be labled with 'active' when approved by core team. At that point the RFC
is 'active' and may be implemented with the goal of eventual inclusion into Nuxt.js.

## The RFC life-cycle

Once an RFC becomes active, then authors may implement it and submit the
feature as a pull request to the Nuxt.js repo. Becoming 'active' is not a rubber
stamp, and in particular still does not mean the feature will ultimately
be merged; it does mean that the core team has agreed to it in principle
and are amenable to merging it.

Furthermore, the fact that a given RFC has been accepted and is
'active' implies nothing about what priority is assigned to its
implementation, nor whether anybody is currently working on it.

## Implementing an RFC

The author of an RFC is not obligated to implement it. Of course, the
RFC author (like any other developer) is welcome to post an
implementation for review after the RFC has been accepted.

If you are interested in working on the implementation for an 'active'
RFC, but cannot determine if someone else is already working on it,
feel free to ask (e.g. by leaving a comment on the associated issue).

## Reviewing RFCs

Each week the team will attempt to review some set of open RFC
pull requests.

We try to make sure that any RFC that we accept is accepted at the
weekly team meeting. Every accepted feature should have a core team champion,
who will represent the feature and its progress.

**Nuxt.js's RFC process owes its inspiration to the [React RFC process], [Yarn RFC process], [Rust RFC process], and [Ember RFC process]**

[React RFC process]: https://github.com/reactjs/rfcs
[Yarn RFC process]: https://github.com/yarnpkg/rfcs
[Rust RFC process]: https://github.com/rust-lang/rfcs
[Ember RFC process]: https://github.com/emberjs/rfcs
