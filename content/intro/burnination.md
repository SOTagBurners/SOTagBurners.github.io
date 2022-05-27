---
description: Burnination FAQ
keywords: ["Stack Overflow", "Tags", "SOTagBurners", "Burnination"]
layout: single
title: Burnination
---

# A crash-course in burnination

{{<section "How does the burnination process work?" "about">}}

### Initiating

A tag can be burned on the spot by yourself if **all** holds true:

1. You have at least a **bronze** badge in the tag or one of the related tags.
2. You conferred with **at least one** other [trusted user](https://stackoverflow.com/help/privileges/trusted-user).
3. There are **less than 50** questions with the tag.

Otherwise, you **must** follow the burnination process.

### Stage 1: Proposal

First, make sure the tag **fails** all of the criteria for burnination:

1. Does it **describe the contents** of the questions to which it is applied? and is it **unambiguous**?
2. Is the concept described even **on-topic** for the site?
3. Does the tag add any **meaningful information** to the post?
4. Does it mean **the same thing** in all common contexts?

If it passes at least **one**, do not proceed and consider other options, if it is:

ambiguous, create a {{< tag "meta.stackoverflow.com" "tag-disambiguation" >}} request.

poorly named, make a {{< tag "meta.stackoverflow.com" "retag-request" >}} request.

too similar to another tag, write up a {{< tag "meta.stackoverflow.com" "synonym-request" >}} request.

----

If **all fail**, create a {{< external "https://meta.stackoverflow.com/questions/ask" "meta" "Meta Stack Overflow" >}} post tagged {{< tag "meta.stackoverflow.com" "burninate-request" >}} with arguments for **each** of the burnination criteria.

Here is a helpful template to get you started:

```md
I believe the tag [tag:tagname] should be burninated.

It fails all the preliminary checks before burnination:

> Does it describe the contents of the questions to which it is applied? and is it unambiguous?

**No**, <!-- reasons why it is ambiguous or is a "meta" tag -->

> Is the concept described even on-topic for the site?

**No**, <!-- TODO: reasons why it is used on off-topic posts -->

> Does the tag add any meaningful information to the post?

**No**, <!-- TODO: reasons why it adds no meaningful information -->

> Does it mean the same thing in all common contexts?

**No**, <!-- TODO: reasons why it means different things -->

It is also problematic because:

<!-- TODO: custom requester reasons -->
```

The guidelines state that proposals reaching a score of **20** are {{< tag "meta.stackoverflow.com" "featured" true >}} by a moderator, and that failure to reach the threshold in **6 months** may result in {{< tag "meta.stackoverflow.com" "status-declined" true >}}. However, this is typically not how it works in practice.

In most cases, failure to reach the threshold is not an issue. Burninations usually get declined if the proposal is met with resistance, either in the form of an overweight of downvotes, or comments and/or answers showing opposition to the idea. In either case, it'll take some time before stage two starts, provided it isn't declinable in phase one.

### Stage 2: Featuring

Stage two starts when a moderator features the question. It exists to gather feedback from wider community,
including those not frequenting {{< external "https://meta.stackoverflow.com/questions/ask" "Meta Stack Overflow" "Meta Stack Overflow" >}}.
The following happens in this stage:

A {{< tag "meta.stackoverflow.com" "featured" true >}} tag is added to the proposal post for at least **36–48 hours**.

Punny titles common for the stage 1 are **replaced** with "Should we burninate the [tag name] tag?".

### Stage 3: Decision

After giving the proposal time to be {{< tag "meta.stackoverflow.com" "featured" true >}}, a moderator will review the post, votes, answers, and comments.

If there is a strong indication the community does not support the request, it will be {{< tag "meta.stackoverflow.com" "status-declined" true >}}.

If the tag can be cleanly removed immediately, the proposal is moved directly to stage 5 after the moderator deals with the tag.

Otherwise, the proposal is advanced to stage 4.

### Stage 4: Burnination

A {{< tag "meta.stackoverflow.com" "status-planned" true >}} tag is added to the proposal post.

The title of the post is replaced with "The [tagname] tag is in the process of being burninated".

The tag's tag wiki is replaced with "DO NOT USE! This tag is being burninated. See: <link to Meta question>".

A "community wiki" answer is posted providing specific guidance on burnination.

After that, the tag is fair game for anyone to participate, including:

- editing
- flagging to close (users without the {{< external "https://stackoverflow.com/help/privileges/close-questions" "CV/RV privilege" "Cast close and reopen votes privilege" >}})
- retagging (users with the {{< external "https://stackoverflow.com/help/privileges/edit" "edit privilege" "Edit questions and answers privilege" >}})
- voting to close (users with the {{< external "https://stackoverflow.com/help/privileges/close-questions" "CV/RV privilege" "Cast close and reopen votes privilege" >}})
- voting to delete (users with the {{< external "https://stackoverflow.com/help/privileges/moderator-tools" "10K tools privilege" "Access to moderator tools" >}})

### Stage 5: Cleanup

After the tag is burninated, questions that are **closed** and have a score **less than 0** will be **deleted**, and the tag will be removed. Once that is done:

A {{< tag "meta.stackoverflow.com" "status-completed" true >}} tag is added to the proposal post.

The title of the post is replaced with "The [name of tag] tag has been burninated" *or* reverted to the punny one.

{{</ section >}}

{{<section "How do I participate in the removal phase?" "participate">}}

{{</ section >}}
