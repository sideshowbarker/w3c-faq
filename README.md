# Outsider’s Guide to the W3C

This is an FAQ for people who may not yet even be [involved in the W3C](https://www.w3.org/get-involved/) at all — but also for W3C [Working Group](#working-groups) participants (and even Working Group Chairs) who may not be familiar with all intricacies of the W3C process.

## What can W3C do for me?

## What can I get from W3C?

## How can I use the W3C?

If there’s a problem you want to solve for people using the web — then, here’s what the W3C can do for you:

* [You can use W3C services to document a web problem that needs solving (and use cases/requirements)](#how-can-i-document-a-web-problem-lacking-solutions)
* [You can use W3C services to propose a new web feature that solves a problem (use cases/requirements)](#how-can-i-propose-a-new-web-feature)
* [You can use W3C services to publish a spec for a new web feature](#how-can-i-publish-a-spec-for-a-new-web-feature)
* [You can get a w3.org URL for your spec, and autopublish updates to it at that URL](#how-can-i-get-a-w3org-url-for-my-spec)
* [You can get the strongest-possible Royalty-Free Licensing Commitments for your spec](#how-can-i-get-royalty-free-licensing-commitments)
* [You can make a “living standard” from your spec](#how-can-i-make-a-living-standard-from-my-spec)
* [You can have your spec formally endorsed by the W3C](#how-can-i-get-formal-w3c-endorsement-for-my-spec)

### How can I document a web problem lacking solutions?

### How can I document use cases and requirements?

If there’s a problem you want to solve for people using the web, here’s how you can document it:

1. Open the [Problem template](https://github.com/w3c/strategy/issues/new?assignees=&labels=problem&projects=&template=00-Problem.yml) form in the issue tracker of the [W3C Strategy team’s GitHub repo](https://github.com/w3c/strategy).
2. Fill out that form, succinctly describing the problem you want to solve, along with some use cases ([example](https://lists.w3.org/Archives/Public/public-webapps/2012JulSep/0835.html)).
3. Submit that form.
   That will create a new issue in the [W3C Strategy issue tracker](https://github.com/w3c/strategy/issues).
4. Share the link to your issue (on social media and in other places), and encourage others to comment.

The presence of that issue in the [W3C Strategy issue tracker](https://github.com/w3c/strategy/issues) will cause it to shortly thereafter get included in the [W3C Strategy Funnel](https://github.com/w3c/strategy/projects/2), and may even eventually lead to a W3C Working Group being formed to tackle the problem.

TODO: Mention that CGS can also be used to document problems, and especially, to publish Use Cases and Requirements reports.

### How can I propose a new web feature?

If there’s a problem you want to solve for people using the web *and* you have a proposal for a new web feature which will solve that problem — here’s how you can propose it:

1. Open the [Exploration template](https://github.com/w3c/strategy/issues/new?assignees=&labels=problem&projects=&template=00-Problem.yml) form in the issue tracker of the [W3C Strategy team’s GitHub repo](https://github.com/w3c/strategy).
2. Fill out that form, succinctly describing the new web feature you’d like to propose.
3. Submit that form.
   That will create a new issue in the [W3C Strategy issue tracker](https://github.com/w3c/strategy/issues).
4. Share the link to your issue (on social media and in other places), and encourage others to comment.

The presence of that issue in the [W3C Strategy issue tracker](https://github.com/w3c/strategy/issues) will cause it to shortly thereafter get included in the [W3C Strategy Funnel](https://github.com/w3c/strategy/projects/2), and may even eventually lead to a W3C Working Group being formed to work on it.

TODO: Mention that a CG could be started in parallel — or even before — raising a Strategy Funnel issue.

### How can I publish a spec for a new web feature?

If you have a solution in mind for a problem you want to solve for people using the web, you can create a spec that defines a new standard web feature to solve that problem for people — and then, the steps you can take for publishing your spec using W3C services depend on what you want to get:

1. If you want to get W3C spec hosting in the quickest/most-lightweight way, first [create a Community Group](#can-i-create-a-new-cg).
2. If you want to get a `https://w3c-cg.github.io/` URL, [request a GitHub repo](https://www.w3.org/2016/04/cg-support/#what) and [publish a Draft CG Report](#draft-cg-reports).
3. If you want to get a `https://www.w3.org/community/reports/` URL, [publish a Final CG Report](#final-cg-reports).
4. If you want to get a `https://www.w3.org/TR/` URL, [create a Working Group](#how-to-create-a-new-wg) and [publish a FPWD](#what-are-fpwds).
5. If you want to get [Royalty-Free Licensing Commitments](#rf-licensing-commitments), [publish Snapshots](#what-are-snapshots).
6. If you want to get a formal endorsement from the W3C and its Members, [publish a Recommendation](#how-can-i-get-formal-w3c-endorsement-for-my-spec).

### How can I get a w3.org URL for my spec?

You can publish specs in two different areas of the w3.org site: `https://www.w3.org/community/reports/` and `https://www.w3.org/TR/`.

#### [https://www.w3.org/community/reports/](https://www.w3.org/community/reports/)

`https://www.w3.org/community/reports/` URLs are for Community Group [Final Reports](#final-cg-reports). So to get a `https://www.w3.org/community/reports/` URL for your spec, you need to follow these steps:

1. First [get a Community Group created](#how-to-create-a-new-cg) for your spec.
2. Publish a [Final Community Group Report](#final-cg-reports).

#### [https://www.w3.org/TR/](https://www.w3.org/TR/)

`https://www.w3.org/TR/` URLs are for Working Group specs. So to get a `https://www.w3.org/TR/` URL for a spec, you need to follow these steps:

1. First [get a Working Group created](#how-to-create-a-new-wg) for your spec.
2. Publish a [First Publish Working Draft (FPWD)](#what-are-fpwds).

### How can I auto-update my spec at its w3.org URL?

You can use [autopublishing](#autopublishing) to update Working Group specs at `https://www.w3.org/TR/` URLs. And while there’s currently no similar mechanism for updating CG Reports at `https://www.w3.org/community/reports/` URLs, *Draft* CG Reports at `https://w3c-cg.github.io/` URLs are auto-updatable using [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site).

### How can I get Royalty-Free Licensing Commitments?

You can secure [Royalty-Free Licensing Commitments](#rf-licensing-commitments) for a Working Group spec by following these steps:

1. If you don’t already have a [Working Group](#working-groups), then first [get a Working Group created](#how-to-create-a-new-wg) created for your spec.
2. Publish a [FPWD](#what-are-fpwds) into [the w3.org/TR spec-publication space](#tr-space) — to trigger the first [Exclusion Opportunity](#exclusion-opportunities).
3. Continue to [autopublish](#autopublishing) updated [Working Drafts](#what-are-working-drafts) into [the w3.org/TR spec-publication space](#tr-space) and to communicate closely with implementors and others to get the details right.
4. When your group believes a spec is ready to be fully implemented — and ready to be thoroughly tested (by having a [suite of tests](https://github.com/web-platform-tests/wpt/) to test against) — then, follow the process to get the Working Draft warning label dropped from a spec, and to get the [CR](#candidate-recommendation) label added, and publish the first [Snapshot](#what-are-snapshots) for it.

   60 days after you publish that first [Snapshot](#what-are-snapshots), you’ll have [secured Royalty-Free Licensing Commitments](#how-can-i-get-royalty-free-licensing-commitments) for *all* [normative](#normative-requirements) features defined in that [Snapshot](#what-are-snapshots).

For information on getting commitments for a Community Group Report, see the [CG Patent Policy](#cg-patent-policy) section.

### How can I make a “living standard” from my spec?

You can make your Working Group spec a [“living standard”](#living-standards) by first [securing RF Licensing Commitments](#how-can-i-get-royalty-free-licensing-commitments), and then:

1. Continue working with implementors and other contributors, and on tests — and, as you iteratively refine the spec contents — [autopublish](#autopublishing) the updated contents as [“CR Drafts”](#when-to-do-cr-drafts) into [the w3.org/TR publication space](#tr-space).
2. At some regular cadence (say, once every 6 months) *and* if any [substantive spec changes](#substantive-changes) were made during that time period, [republish a new Snapshot](#how-can-i-get-royalty-free-licensing-commitments) so that a new [Exclusion Opportunity](#exclusion-opportunities) will be triggered.
3. As you receive bug/issue reports and pull requests for your spec over time, continue to perpetually [maintain](#spec-maintenance) it by repeating steps 1 and 2 above over time.

For information on Community Group “living standards”, see the [CG “living standards”](#cg-living-standards) section.

### How can I get formal W3C endorsement for my spec?

You can get your spec formally endorsed by the W3C — that is, get it labeled as a [W3C Recommendation](#recommendation) — by first [securing RF Licensing Commitments for your spec](#how-can-i-get-royalty-free-licensing-commitments), and then:

1. Assess whether the spec has multiple implementations (or is otherwise deemed sufficiently implemented).
2. When your group can show that the spec has multiple implementations (or is otherwise deemed sufficiently implemented), do an Advisory Committee review to get formal endorsement from the W3C and its Members.

## What can I do if I’m not a Working Group participant?

Even if you’re not a Working Group participant (and even if your employer’s not a W3C Member), you can do a lot:

* [You can get a W3C account](#can-i-get-a-w3c-account)
* [You can get a “W3C member” logo in your GitHub profile](#can-i-get-a-w3c-member-logo-in-my-github-profile)
* [You can make Royalty-Free Licensing Commitments](#can-i-do-rf-agreements)
* [You can document web problems that need solving (and use cases/requirements](#can-i-document-problems))
* [You can propose new features that solve web problems](#can-i-propose-features)
* [You can publish specs for new web features](#can-i-publish-specs)
* [You can get a w3.org URL for your spec](#can-i-get-a-w3org-url)
* [You can review specs](#can-i-review-specs)
* [You can raise issues against existing specs](#can-i-review-specs)
* [You can contribute PRs against existing specs](#can-i-contribute-spec-prs)
* [You can access W3C mailing lists](#can-i-access-mailing-lists)
* [You can freely join W3C Community Groups](#can-i-freely-join-any-cg)
* [You can create W3C Community Groups](#can-i-create-a-new-cg)

### Can I get a W3C account?

### Can I get a “W3C member” logo in my GitHub profile?

Yes. Here’s how:

1. Go to [https://www.w3.org/account/request/](https://www.w3.org/account/request/) to create your W3C account.
2. Go to [https://www.w3.org/users/myprofile/connectedaccounts/](https://www.w3.org/users/myprofile/connectedaccounts/) to connect your GitHub and W3C accounts.

The W3C logo will then show in the **Organizations** part of your GitHub profile — indicating you’re a member of the [W3C GitHub org](https://github.com/w3c/) (even if you’re not part of any Working Group, and even if your company’s not a W3C Member).

### Can I do RF agreements?

Yes. For Working Group specs, the W3C’s [automated contribution-management mechanism](https://w3c.github.io/repo-management.html) allows you (in some but not all cases) to make [RF Licensing Commitments](#rf-licensing-commitments) for any [substantive change](#substantive-changes) you contribute by way of a [pull request](#can-i-contribute-spec-prs) — even if you’re not a participant in the Working Group, and even if your company isn’t a W3C Member.

For information on commitments for non-Working-Group specs, see the [CG Patent Policy](#cg-patent-policy) section.

### Can I document problems?

Yes. If there’s a web-user problem you want to solve, [you can document it](#how-can-i-document-a-web-problem-lacking-solutions) (along with use cases/requirements).

### Can I propose features?

Yes. If there’s a problem you want to solve for web users, [you can propose a new web feature](#how-can-i-propose-a-new-web-feature) to solve it.

### Can I publish specs?

Yes. You can [publish a spec](#how-can-i-publish-a-spec-for-a-new-web-feature) even if you’re not part of any Working Group, and even if you’re not a W3C Member.

#### Can I get a w3.org URL?

Yes. Even if you’re not part of any Working Group, and even if you’re not a W3C Member, you can get a [`w3.org/community/reports`](#httpswwww3orgcommunityreports) URL for your spec — though you’ll first need to have a [W3C Community Group](#community-groups).

To instead get a [`w3.org/TR`](#httpswwww3orgtr) URL for your spec, you’ll first need [get a Working Group created](#how-to-create-a-new-wg) for your spec.

### Can I review specs?

Yes. The W3C strongly encourages and facilitates [wide review](#wide-review) — and seeks to provide the widest-possible opportunities for review from the widest-possible set of reviewers. Here’s how you can take part:

1. Find a W3C Working Group spec that you can review and comment on — by taking any of the following steps:
   * Go to the [W3C News](https://www.w3.org/news/) page or to [public-review-announce archive](https://lists.w3.org/Archives/Public/public-review-announce/) and browse through the latest “Call for Wide Review” and “First Public Working Draft” announcements.
   * [Subscribe](mailto:public-review-announce-request@w3.org?subject=subscribe) to the mailing list to which all “Call for Wide Review” and “First Public Working Draft” announcements are posted — so you’ll get e-mail notifications whenever new announcements are made.
2. Review the actual spec, and raise issues or pull requests or post comments.

   Every “Call for Wide Review” and “First Public Working Draft” announcement has a link to an actual Working Group spec — and every Working Group spec has a link to the group’s [W3C GitHub repo](https://github.com/orgs/w3c/repositories?type=source) and issue tracker and/or a [mailing list for comments](#can-i-access-mailing-lists). So, you can do any of the following:
   * [Raise issues](#can-i-raise-issues) in the group issue tracker — for questions/comments, or for spec problems that need fixing.
   * [Create a pull request](#can-i-contribute-spec-prs) with an actual spec patch — to propose changes you want merged into a spec.
   * [E-mail the group’s mailing list](#can-i-access-mailing-lists) — if you have questions/comments or find spec problems that need fixing.

### Can I raise issues?

Yes. Working Groups have [W3C GitHub repos](https://github.com/orgs/w3c/repositories?type=source) with issue trackers where you can raise issues with questions or comments on a spec — or when you find a spec problem that need fixing.

### Can I contribute spec PRs?

Yes. Working Groups have [W3C GitHub repos](https://github.com/orgs/w3c/repositories?type=source) to which you can submit patches you want merged into specs.

For [substantive patches](#substantive-changes), an [automated mechanism](https://w3c.github.io/repo-management.html) enables you (in some but not all cases) to make [RF Licensing Commitments](#rf-licensing-commitments) — even if you’re not part of any Working Group, and even if your company isn’t a W3C Member.

### Can I access mailing lists?

Yes. See the [W3C mailing-list archives](https://lists.w3.org/Archives/Public/). All Working Groups do their work in public; they have mailing lists with public archives that you can read, and you are welcome both to subscribe to Working Group mailing lists, and also to post messages to the lists (with questions or comments, or to report spec problems that need fixing, etc.)

### Can I freely join any CG?

Yes. You can [join](https://www.w3.org/community/about/faq/#how-do-i-join-a-group) any of the current [140+ Community Groups](https://www.w3.org/community/groups/) organized around specific technologies/topics:

1. Browse the [sortable list of all 140+ W3C Community Groups (CGs)](https://www.w3.org/community/groups/) that currently exist.
2. Find a CG you’d like to join, and then on the homepage of that CG, press the **Join this group** button.

### Can I create a new CG?

Yes. You [can create a new CG](#how-to-create-a-new-cg) relatively easily.

## Community Groups?

[W3C Community Groups (CGs)](https://www.w3.org/community/about/faq/) are open, self-organized groups that by design are unregulated by the W3C — for people to get together in and use without restrictions for any purposes they choose, including to develop specs.

### How open are CGs?

Unlike [Working Groups](#working-groups) — which to join generally require your employer to be a W3C Member organization — CGs are open to all. You can [freely join any CG you want to](#can-i-freely-join-any-cg) — and you can even [create a new CG](#how-to-create-a-new-cg) if you want to.

### WICG?

The [WICG](https://wicg.io/) is a particularly special W3C Community Group specifically for [incubating](https://wicg.github.io/admin/charter.html#goals) new web-platform features.

You can browse the [list of 120+ active incubations](https://wicg.io/#incubations), and you can even [create a proposal](https://wicg.io/#proposals) for a new incubation.

### How to create a new CG?

See [How do I propose a group?](https://www.w3.org/community/about/faq/#how-do-i-propose-a-group) in the W3C Community Groups FAQ for a how-to on getting a new CG created.

### CG Patent Policy

TODO

### Draft CG Reports?

TODO

### Final CG Reports?

TODO

## Working Groups?

TODO: Explain here what WGs are.

### Why a Working Group?

### Why not just a CG?

It’s entirely possible to [maintain](#spec-maintenance) a spec in just a [Community Group](#community-groups) or the [WICG](#wicg) — or even with just a GitHub repo alone — without ever needing to have a [Working Group](#working-groups) for it. But here are the things you *can’t* do in a Community Group or in the WICG or with just a GitHub repo alone, and that you instead do need to have a Working Group for:

* [You can get a w3.org/TR URL for your spec, and autopublish updates to it at that URL](#how-can-i-get-a-w3org-url-for-my-spec)
* [You can get the strongest-possible Royalty-Free Licensing Commitments for your spec](#how-can-i-get-royalty-free-licensing-commitments)
* [You can have your spec formally endorsed by the W3C](#how-can-i-get-formal-w3c-endorsement-for-my-spec)

### How to create a new WG?

To have a new W3C Working Group created, follow these steps:

1. [Develop a spec for a new standard web feature](#how-can-i-publish-a-spec-for-a-new-web-feature).
2. Write a [draft Working Group charter](https://w3c.github.io/charter-drafts/charter-template.html) for a new W3C Working Group to work on your spec:
   1. Fork and clone the [https://github.com/w3c/charter-drafts](https://github.com/w3c/charter-drafts) repo, and then within your local clone:
   2. Create a new `foo-wg-charter.html` (or whatever name) file by copying the [W3C charter template](https://github.com/w3c/charter-drafts/blob/gh-pages/charter-template.html).
   3. Fill out the parts of that template in your `foo-wg-charter.html` file.
   4. Save your `foo-wg-charter.html` file and use `git add` to add it to your clone.
   5. Push the `foo-wg-charter.html` file change to your fork.
   6. Open a [PR](https://github.com/w3c/charter-drafts/compare) to merge your `foo-wg-charter.html` file into the [https://github.com/w3c/charter-drafts](https://github.com/w3c/charter-drafts) repo.
3. File a formal request that the W3C consider launching a new W3C Working Group based on your draft charter:
   1. Open the [Charter development and review form](https://github.com/w3c/strategy/issues/new?assignees=&labels=charter&projects=&template=04-Chartering.md&title=%5Bwg%2F%3Cshortname%3E%5D+%5Bname%5D+Group+Charter) in the issue tracker of the [W3C Strategy team repo](https://github.com/w3c/strategy).
   2. Fill out that form, with a link to your draft-charter pull request from step #2 above.
   3. Submit that form.

  That will create a new issue in the [W3C Strategy issue tracker](https://github.com/w3c/strategy/issues), where you can have a discussion about your draft charter with people from the W3C Strategy team and others.

From there on — if your request for a new W3C Working Group ends up being accepted — the logistics for the actual creation of the new Working Group will be handled by the W3C staff.

## Editor’s Draft?

Anywhere you see *Editor’s Draft*, substitute ***Canonical Version***, ***Up-to-Date Version***, or ***Non-Obsolete Version***.

> [!IMPORTANT]
> For implementors: substitute ***“The* only *spec version that implementors should* ever *read”***.

### Editor’s Draft = *canonical* version to always read/use

A so-called “editor’s draft” of a spec is actually the ***canonical source*** **version** of the spec: The version including the latest changes made to the source for the spec in its source-control (GitHub) repo. That makes it the one you should use if you want to be sure you’re reading the most-up-to-date spec text — not already-obsolete spec text.

> [!IMPORTANT]
> If you’re an implementor, it’s *essential* to only work from so-called “editor’s drafts”; otherwise, if you use a version published elsewhere, you may implement old text that has subsequently changed in the canonical spec since whenever that other version happened to be published.

The way to know whether what you’re reading is actually the canonical version is: It’ll *usually* be explicitly subtitled with the literal label ***Editor’s Draft***. But also: It’s the version you find *outside the [the w3.org/TR publication space](#tr-space)*.

> [!NOTE]
> Canonical (“editor’s draft”) versions of Working Group specs *usually* have `w3c.github.io` URLs.

## Working Draft?

“Working Draft” is a label for indicating the status of a spec. There are two flavors: the “normal” Working Draft label, and the “FPWD” or “First Public Working Draft” label.

### What are Working Drafts?

“Working Draft” is what a spec gets labeled with while a group is still “working” on getting it to the point that they believe it’s ready to be fully implemented — and ready to be thoroughly tested (by having a [suite of tests](https://github.com/web-platform-tests/wpt/) to test against) — and before it’s ready to secure [Royalty-Free Licensing Commitments](#rf-licensing-commitments).

So, you can think of any Working Draft as being stamped with a giant ***“Use only with caution”*** warning, signaling that the spec very likely still has some significant deficiencies — but that it *certainly* does have one very important deficiency, which is: ***[RF Licensing Commitments](#rf-licensing-commitments) for the features in the spec have not yet been secured***.

> [!IMPORTANT]
> RF commitments can ***only*** be secured by publishing [Snapshots](#what-are-snapshots). 👉 [Why not just publish WDs?](#why-not-just-wds)

### What are FPWDs?

The first time a spec is published [at a w3.org/TR URL](#tr-space), **First Public Working Draft (FPWD)** is the label it gets.

The W3C widely [announces every single FPWD](https://lists.w3.org/Archives/Public/public-review-announce/) — including, often, by posting a news item both directly on the [https://www.w3.org/](https://www.w3.org/) homepage and on the [W3C News](https://www.w3.org/news/) page. Along with the general *“Here’s something new!”* value of each such an FWPD announcement, it also has another very important purpose, which is: To give a heads-up to everyone that the FPWD publication triggers a 150-day [Exclusion Opportunity](#exclusion-opportunities) for the spec.

## Patent Review Draft?

Anywhere you see or hear the term *Patent Review Draft*, you can in practice substitute *[Snapshot](#what-are-snapshots)*. Patent Review Drafts — [Snapshots](#candidate-recommendation) — are the stage at which [Royalty-Free Licensing Commitments](#rf-licensing-commitments) are actually are secured.

### Exclusion Opportunities?

[Exclusion Opportunities](https://www.w3.org/policies/patent-policy/#sec-exclusion-with) are **limited-time chances** to exclude specific [Essential Claims](https://www.w3.org/policies/patent-policy/#essential-claims) from any [RF Commitments](#rf-licensing-commitments).

There are two spec labels (publishing “stages”) which trigger an Exclusion Opportunity: [FPWD](#what-are-fpwds) and [CR](#candidate-recommendation).

> [!IMPORTANT]
> The W3C Patent Policy mandates *[disclosure requirements](#disclosure-requirements)* — and:
>
> * The [disclosure requirements](#disclosure-requirements) for a particular Working Group begin at the moment when the creation of the group is first announced — that is, when the first Call for Participation for the group is announced.
> * All [disclosure requirements](#disclosure-requirements) are *ongoing*; specifically, they are in effect both before any [Patent Review Draft](#patent-review-draft) happens to be published, and also at all times after.

### Disclosure Requirements?

The term *“disclosure requirement”* refers to the obligation the [W3C Patent Policy](https://www.w3.org/policies/patent-policy/) places on W3C Members to disclose any knowledge of a patent believed to contain any [Essential Claim](https://www.w3.org/policies/patent-policy/#essential-claims) with respect to a particular spec.

> [!IMPORTANT]
> Disclosure of any Essential Claims is an **ongoing obligation** — even though [Exclusion Opportunities](#exclusion-opportunities) are time-limited.

The disclosure obligation is explicitly triggered any time a new version of a spec is published in [the w3.org/TR spec-publication space](#tr-space) — but also, to quote verbatim from [the relevant part of the W3C Patent Policy document](https://www.w3.org/policies/patent-policy/#sec-disclosure-timing):

> *The [disclosure](https://www.w3.org/policies/patent-policy/#disclosure) obligation is an ongoing obligation that begins with the Call for Participation… In any case, disclosure as soon as practically possible is required.*

## Candidate Recommendation?

Everywhere you see *Candidate Recommendation*, substitute ***Working Group Specification*** — in this sense:

1. The spec is just a *WG*-owned/endorsed spec — *not* a *W3C*-owned/endorsed one (that’s what a [REC](#recommendation) is).
2. The spec meets criteria for dropping the Working Draft warning label — criteria such as:
   1. [Consensus](#consensus) has been achieved within the group for dropping the Working Draft warning label.
   2. [Wide review](#wide-review) has been conducted thoroughly.
   3. [Implementation interest](https://whatwg.org/stages#terminology) has been clearly expressed by at least two implementors.
   4. [WPT tests](https://github.com/web-platform-tests/wpt) (or equivalent) are already written for all features in the spec.
   5. [Implementation bugs](https://github.com/whatwg/meta/blob/main/MAINTAINERS.md#handling-pull-requests) have been filed in the project bug/issue trackers of all target implementations.
   6. [An MDN issue](https://github.com/whatwg/meta/blob/main/MAINTAINERS.md#handling-pull-requests) has been filed, describing the docs that would need to be written for the spec.
3. The spec has either secured [RF Licensing Commitments](#how-can-i-get-royalty-free-licensing-commitments) or is at most 60 days away from securing them.

That’s because initiating the process for dropping the Working Draft warning label is what you can/should do with a spec when your group believes it’s ready to be fully implemented — and ready to be thoroughly tested, with tests ready — and you want to secure [Royalty-Free Licensing Commitments](#how-can-i-get-royalty-free-licensing-commitments) for the spec.

> [!NOTE]
> In the label *Candidate Recommendation*, you can think of the word *Candidate* as meaning *eligible*; that is, it indicates your spec is *eligible* for evaluation against the requirements for the Recommendation label — even if your Working Group has no *intention* to go through the process of getting it labeled as such.

And if you *already* have multiple implementations (and a test suite) for a spec still labeled Working Draft, you probably should have already started the [steps for securing Royalty-Free Licensing Commitments](#how-can-i-get-royalty-free-licensing-commitments).

### What are Snapshots?

CR Snapshots are static date-stamped versions of the state of a spec — of all *features* [normatively defined](#normative-requirements) in a spec — *at a particular point in time*, intended solely for patent review toward a goal of securing [RF Commitments](#how-can-i-get-royalty-free-licensing-commitments).

So, everywhere you see *Candidate Recommendation Snapshot*, substitute ***Patent Review Snapshot***.

You typically publish new patent-review Snapshots at some regular cadence — for example, once every 6 months — *if* any [substantive spec changes](#substantive-changes) were made to the spec during the intervening time period.

60 days after publishing a particular Snapshot, you secure [RF Commitments](#how-can-i-get-royalty-free-licensing-commitments) for *all* [normative](#normative-requirements) features it defines.

> [!IMPORTANT]
> Due to their nature, **Snapshots are essentially disposable** and should never be used for any purpose at all after their related [RF Licensing Commitments](#rf-licensing-commitments) have been secured. That is, 60 days after it is published, a particular Snapshot effectively becomes completely obsolete for any purpose at all.
>
> In particular: **Implementors should *never* use Snapshot text as the basis from which they implement.**
>
> The reason for that is: In the intervening 60 days after that Snapshot was published, changes may have been made to spec text defining [normative requirements](#normative-requirements) for implementations of particular features — which means the state of the spec text in that Snapshot is possibly (or likely) already obsolete.
>
> Snapshots should also never be used for purposes such as feature versioning or feature profiling.

### When to do Snapshots?

When your group believes a spec is fully ready to be implemented — and ready for thorough testing — then, follow the [steps for securing Royalty-Free Licensing Commitments](#how-can-i-get-royalty-free-licensing-commitments), and [publish the first Snapshot](#how-can-i-get-royalty-free-licensing-commitments) for it.

Then, at some regular cadence (say, once every 6 months) *and* if any [substantive changes](#substantive-changes) were made during that period, [republish a new Snapshot](#how-can-i-get-royalty-free-licensing-commitments) — solely in order to secure [RF Licensing Commitments](#rf-licensing-commitments) on those changes.

### When to do CR *“Drafts”*?

As you work with implementors and contributors and on tests — and, as you iteratively refine the spec contents — (re)publish the updated contents as [“Candidate Recommendation” (“CR”) “Drafts”](#when-to-do-cr-drafts) into [the w3.org/TR space](#tr-space).

## Spec maintenance?

If you create a spec for a new feature for the web, plan on continuing to maintain that spec for the rest of your life (no joke) and/or plan to hand it over to others who will agree to continuing to maintain it after you move on.

### Why spec maintenance?

Ensuring interoperability among multiple implementations of a spec is, in practice, an ongoing process the never really ends — and that requires iteratively making refinements to the spec over time. Sometimes outright bugs are found in existing spec text, sometimes ambiguities in need of clarification, and sometimes just simple typos.

But *all* of those cases require you to do continuing maintenance of the spec. And the way you do *that* is by having a place where others can report spec issues they find, and can submit spec patches. That typically means using a GitHub repo or something similar — with an issue tracker and a mechanism for users to submit patches.

It’s like maintaining an open-source software application or library: Even after you release a “stable” version — and even in the case where you may *never* end up adding any features to it, or never making any API changes — you still continue to make updates to it, as users find bugs, contribute patches with code refinements, and so on.

## Autopublishing?

You should set up “autopublishing” for your specs (using [W3C “Echidna”](https://github.com/w3c/echidna/wiki)), so that up each time you merge commits to the source for your spec, your spec updates will be automatically published into [the w3.org/TR space](#tr-space).

You can set it up using the [spec-prod](https://w3c.github.io/spec-prod/) GitHub Action, or [Bikeshed’s built-in support](https://speced.github.io/bikeshed/#cli-echidna), or [any other available tools](https://github.com/w3c/echidna/wiki#sub-projects-and-related-tools).

## RF Licensing Commitments

In plain terms, RF Licensing Commitments provide for your spec to be freely implemented by anyone — so no one will ever need to pay royalties to anyone else in order to ship/sell products that have the features from your spec.

In legal terms: A Royalty-Free Licensing Commitment is a binding legal commitment to license under the [W3C Royalty-Free License](https://www.w3.org/policies/patent-policy/#def-RF) any [Essential Claims](https://www.w3.org/policies/patent-policy/#essential-claims) that haven’t been excluded during an [Exclusion Opportunity](#exclusion-opportunities) for a spec.

Among standards-development organizations (SDOs), the W3C has essentially the strongest-possible RF policy — and publishing a Working Group spec at the W3C ensures it’ll secure the strongest-possible RF Commitments.

## Living standards?

This section has information about [maintaining](#spec-maintenance) so-called “living standards” or “evergreen standards” at the W3C.

### W3C “living standards”?

Yes. For any Working Group spec that’s [receiving RF Licensing Commitments](#how-can-i-get-royalty-free-licensing-commitments), your group can continue to perpetually [autopublish](#autopublishing) and ***[maintain](#spec-maintenance)*** that spec as a so-called “living standard” or “evergreen standard” — without any requirement to necessarily ever get [formal endorsement of the spec from the W3C and its Members](#how-can-i-get-formal-w3c-endorsement-for-my-spec).

#### Perpetually-maintained working-group specs

In other words, these are *“unendorsed by the W3C and its Members but perpetually [maintained](#spec-maintenance) by the working group”* specs which *intentionally* never “transition”/“advance” further in the W3C spec-labeling (maturity) process.

So the literal term *“perpetually maintained working-group spec”* would be a more accurate label for such specs.

### Why publish CRs?

### Why not just WDs?

The reason you’d want your spec labeled [“CR”](#candidate-recommendation) — rather than keeping it labeled [“Working Draft”](#working-draft) forever — is this:

#### 👉 ***The only way to secure [RF Commitments](#how-can-i-get-royalty-free-licensing-commitments) for a Working Group spec is by publishing with the [“CR”](#candidate-recommendation) label.***

To state that same fact in few more words:

* Specs labeled with [“CR”](#candidate-recommendation) are [Patent Review Drafts](#patent-review-draft), while specs labeled as Working Draft are *not*.
* Publishing with the [“CR”](#candidate-recommendation) label secures [RF Commitments](#how-can-i-get-royalty-free-licensing-commitments); publishing with the Working Draft label does *not*.
* While publishing with the FPWD label *does* trigger an [Exclusion Opportunity](#exclusion-opportunities), that *does not* trigger [RF Commitments](#how-can-i-get-royalty-free-licensing-commitments). RF Commitments can in practice *only* be secured after publishing with the [“CR”](#candidate-recommendation) label.

### CG “living standards”?

Yes, it’s also possible to maintain a “living standard” in a Community Group (CG) — but only as a *Draft* CG Report, rather than as a *Final* CG Report. So, using a CG to maintain a “living standard” would mean losing two big things:

* Your CG-maintained “living standard” wouldn’t have a [w3.org URL](#how-can-i-get-a-w3org-url-for-my-spec) — because while [*Final* CG Reports](#final-cg-reports) have w3.org URLs, [*Draft* CG Reports](#draft-cg-reports) do *not* have w3.org URLs.
* Your CG-maintained “living standard” would lack adequate [RF Commitments](#how-can-i-get-royalty-free-licensing-commitments) — because securing even the most barely adequate ones requires a [*Final* CG Report](#final-cg-reports) (and *real* ones require Working Group [Snapshots](#what-are-snapshots)).

## Recommendation?

Everywhere you see the term *Recommendation* or *W3C Recommendation* on its own (rather than in *Candidate Recommendation*) substitute ***W3C Standard*** — in the sense of being a spec that:

1. Has multiple existing interoperable implementations.
2. Has received the endorsement of the W3C and its Members.

That’s because getting a spec labeled as a Recommendation is what you can do with it if your group can show it has multiple implementations (or may otherwise be deemed sufficiently implemented), and you want the spec to go through full W3C Advisory Committee review to receive formal endorsement from the W3C and its Members.

However, even if your group *can* demonstrate a particular spec has been sufficiently implemented, you are not *required* to go through the process for getting it labeled as a W3C Recommendation.

If your group decides you *don’t* want to have the spec formally endorsed by the W3C and its Members, you can instead choose to continue to ***[maintain](#spec-maintenance)*** it: by keeping it labeled with [“CR”](#candidate-recommendation) and [perpetually keeping it up to date](#living-standards).

## Recommendation Track?

Anywhere you see or hear the term *Recommendation Track*, substitute the term ***Standards Track***. So, for example, you can read the beginning of the *The W3C Recommendation Track* section in the Process doc as:

> #### *The Standards Track*
>
> *Working Groups create specifications and guidelines to complete the scope of work envisioned by a Working Group's charter. These W3C Publications undergo cycles of revision and review…*

And you can read the beginning of the *Types of Technical Reports* section as:

> #### *Types of Publications*
>
> *This chapter describes the formal requirements for publishing and maintaining a W3C Standard…*
>
> #### *Standards*
>
> *Working Groups develop W3C Publications on the W3C Standards Track in order to produce normative specifications or guidelines as standards for the Web. The Standards Track process incorporates…*

## Wide review?

At the W3C, the term “wide review” is used in a number of senses — one of them being that principle of seeking out the widest-possible opportunities for review from the widest-possible set of reviewers. But it also specifically means getting review in four core areas:

* Accessibility
* Security
* Privacy
* Internationalization

And along with those four core areas, there’s a fifth area which could be described as “technical soundness” — which is something the W3C TAG (Technical Architecture Group) has responsibility for helping to ensure across all Working Group specs.

## Consensus?

(TODO: Mention W3C making strong efforts to not disenfranchise particular groups of people, nor individuals.

## “Technical Reports”?

## “TR”?

Anywhere you see or hear the term *Technical Report* or *TR*, substitute the term ***W3C Publication***. So, for example, you can read the beginning of the *W3C Technical Reports* section in the Process doc as:

> #### *W3C Publications*
>
> *The W3C Publication development process is the set of steps and requirements followed by W3C Working Groups to standardize Web technology. The W3C Publication development process…*

And you can read the heading of the *Types of Technical Reports* section as:

> #### *Types of Publications*

## “TR space”?

*“TR space”* means [https://www.w3.org/TR](https://www.w3.org/TR) — it’s the area of the w3.org site under which the W3C publishes specs. So any time you see or hear *TR space*, substitute *W3C specs space* or *W3C publications space*.

In other words, imagine that the [https://www.w3.org/TR](https://www.w3.org/TR) URL is instead actually the following URL:

#### [https://w3.org/specs](https://w3.org/specs)

In fact, if you want, you can actually already *use* that URL instead. Try it. Currently it (sorta) redirects to [https://www.w3.org/TR](https://www.w3.org/TR) — but maybe someday, things will be the other way around instead!

## “Normative” requirements?

*Normative requirements* are any requirements that match the following definition [from the W3C Patent Policy](https://www.w3.org/policies/patent-policy/#dfn-norm):

> *The normative portions of the Specification shall be deemed to include only architectural and interoperability requirements. Optional features in the RFC 2119 sense are considered normative unless they are specifically identified as informative. Implementation examples or any other material that merely illustrate the requirements of the Specification are informative, rather than normative.*

That is, normative requirements are essentially any spec statements made using the [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119) keywords *“must”, “must not”, “required”, “shall”, “shall not”, “should”, “should not”, “recommended”, “may”,* and *“optional”*.

## “Substantive” changes?

A *substantive change* to a spec is any deletion or addition or modification to [normative requirements](#normative-requirements) in the spec that might invalidate anyone’s previous review or implementation of those [normative requirements](#normative-requirements).

Substantive changes include any of the following classes of changes:

* changes that “make conforming data, processors, or other conforming agents become non-conforming”
* changes that “make non-conforming data, processors, or other agents become conforming”
* changes that “clear up an ambiguity or under-specified part of the spec in such a way that data, a processor, or an agent whose conformance was once unclear becomes clearly either conforming or non-conforming”
* changes that “add new functionality, such as new elements, new APIs, new rules, etc.”

Substantive changes may expose a spec to new [Essential Claims](https://www.w3.org/policies/patent-policy/#essential-claims) — so, after any substantive changes are made to a spec, it should be [(re)published as a Snapshot](#how-can-i-get-royalty-free-licensing-commitments) so that a new [Exclusion Opportunity](#exclusion-opportunities) will be triggered.
