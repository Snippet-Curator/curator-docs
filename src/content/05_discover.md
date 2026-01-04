---
title: Discover
description: Discover notes
---

Notes under Discover are presented based on their scores in a descending rank list. Scores are calculated based on several factors, and their weight can be adjusted under settings:

![](/images/settings-discover.png)

### Recency Score

This is how recently the note was last viewed. Older notes are scored higher. Last viewed is updated when a note is either seen via Discover or on its own and is not affected when the note is displayed as part of a notebook or tag list.

Change its weight (between 0 and 10) to affect how heavily you want to resurface old notes. Use higher numbers (e.g. 10) to rank older notes higher.

Notes that have never been seen before gets a randomized score with slight boost.

### Rating Score

![](/images/star.png)

Notes can be rated from 0 to 5. Higher rated notes are scored higher. Think of rating as more of a longterm score modifier (e.g. I like this note and will continue to like this note).

Adjust its weight (between 0 and 10) to affect how heavily a higher rated note will be scored.

### Vote Score

![](/images/navigation.png)

Under Discover, notes can also be given upvote or downvote. By default, every note starts with vote of 5. Use weight as more of a short term score modifier (e.g., I like this note but just want to see it less).

Adjust its weight (between 0 and 10) to affect how heavily a higher voted note will be scored.

### Penalty and Penalty Recovery

To avoid showing notes that are just seen, a penalty score is added that dramatically decreases a note's score temporarily and then gradually lets it return to normal over time.

By default, notes seen in the last hour are penalized fully, and the window to return to normal score is 12 hours.

### Refresh Score Cutoff

One problem with having notes presented by scores is that lower scored notes are seen less, and thus less likely to have their scores refreshed. If you have a large collection, the bottom of the list may never be seen or have their scores refreshed to include the new recency score.

At startup, Curator will recalculate scores for notes to mitigate this problem. By default (0 day), all notes have their scores recalculated on startup. When the collection size is large enough, this may cause performance problems. For example, I currently have about 6,000 notes, and it takes about 1.5 seconds to calculate all of their scores.

You can change this to a different cutoff. For example, changing it to 5 will calculate only notes with scores more than 5 days old.
