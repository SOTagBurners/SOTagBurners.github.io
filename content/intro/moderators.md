### Stage 2: Featuring

1. Add a hidden warning for editors is added to the proposal post:

```md
<!-- MODERATOR NOTE TO EDITORS:
Do not change the question's title while it is being [featured]. No puns!

If you ignore this note, it will be considered abuse and handled accordingly.
-->
```

2. Add a visible warning:

<pre class="scrollable-code">
<code>
> #### *This tag is in phase 2 of the burnination process described [here](https://meta.stackoverflow.com/q/324070). The question and comments have been cleaned to allow for on-topic discussion about the burnination of this tag. Please keep it that way.*
> ###### *If you want to discuss the process of burnination itself, post a new question on Meta or visit the [SOCVR chat room](https://chat.stackoverflow.com/rooms/41570).*
</code>
</pre>

3. Add a Featured Burninate Request notice:

{{< notice >}}
The tag under discussion here is being [considered for immediate removal](http://meta.stackoverflow.com/questions/307068/make-it-easier-to-prevent-new-questions-being-added-in-a-tag/307124#307124). If you have reason to believe this tag should be kept, please post an answer defending it!
{{</ notice >}}

### Stage 4: Burnination

1. Post a community-wiki answer (if you are the one to do it) on the proposal post with the following *template:*

```md
# Observations/Retag Guidance:

<Observations about the tag's current usage and specific guidance for cleaning it up. This should either be summarized or carried over directly from the previous discussion. [This is formatted as an HTML tag, not a comment, so the post editor complains and reminds you it need to be dealt with.]>

<!--Move these out of an HTML comment when there's specific guidance:
- Guidance 1
- Guidance 2
- Guidance 3
-->

# Progress:

The [tag:tag] tag is in the process of being burninated. You can help out by reviewing the questions with this tag, and...

- **editing** questions to improve the question *and* remove the tag (retag-only edits are best left to users with full edit privileges; i.e. > 2k reputation),
- **flagging/voting to close** questions that are duplicates/off-topic/unclear/too broad/opinion-based (users with < 3k reputation can help quite a bit by flagging questions for closure, which helps keep the Close Vote Review Queue full),
- **filtering** for questions with this tag in the [Close Vote Queue](https://stackoverflow.com/review/close/?filter-tags=tag),
- **voting** on questions with this tag,
- voting to **delete** the questions with this tag (after they have been closed, and only if the entire Q&A contains nothing of value). However, keep in mind that at the end of the burnination process all closed questions containing this tag will be deleted semi-automatically. Thus, there's rarely a need to vote to delete these questions.

Here are some quick links to get you started:

- [Open](https://stackoverflow.com/search?q=%5Btag%5D+closed%3Ano)
- [Closed](https://stackoverflow.com/search?q=%5Btag%5D+closed%3Ayes)
- [Unanswered](https://stackoverflow.com/search?q=%5Btag%5D+answers%3A0+closed%3Ano)
- [No Accepted Answer](https://stackoverflow.com/search?q=%5Btag%5D+hasaccepted%3A0+closed%3Ano)

# [Track the progress of burnination](<URL for burnination chat room>)

![Gemmy's burnination progress chart (this is updated from time-to-time; see burnination chat room for the most recent)](<URL for gemmy burnination chart>)

# Remember that burnination is a *clean-up* effort!

### Salvage whatever possible by editing and re-tagging.

We don't want to destroy value, so salvaging a post should be your first priority. If a question can be saved, please edit it. Your edit should improve *all* problems with the question *and* remove the [tag:tag] tag, possibly replacing it with another tag, as described above in "Observations/Retag Guidance". (Edits, specially re-tags, are best left to users with [full edit privileges](https://stackoverflow.com/help/privileges/edit))

### Unsalvageable questions should just be flagged/voted for closure. They don't need to be retagged.

If the question is not appropriate for this site, then don't worry about removing the [tag:tag] tag&mdash;just flag/vote to close the question.

At the end of the burnination process, all questions which still have the [tag:tag] tag should have been closed. These will be mass-deleted, which will remove the tag from the system automatically, with minimal disruption.

### Ask for help if you need it.

If you have any questions about specific questions you come across, or the process in general, please feel free to leave a comment on this post. You can also drop into the [SOCVR chat room](https://chat.stackoverflow.com/rooms/41570) for real-time advice and discussion.
```

### Stage 5:

Edit the community wiki answer with a mention that the burnination is now complete:

```md
[tag:tag] has been *burninated*.

![trogdor](https://i.stack.imgur.com/Zm85C.png)

Thanks to everyone who participated.
```