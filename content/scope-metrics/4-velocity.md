---
title: "Velocity"
metaTitle: "Velocity - Scope Docs"
metaDescription: "Velocity"
---

In Velocity, we show the data of the real times it takes to finish the PRs and Reviews. We display the data at the engineer and repository level. In this way, you will be able to see which repositories are being more agile than others, get answers, measure and improve. The same happens with people. You will be able to detect bottlenecks when people take too long to complete their PRs or Reviews. For velocity, we play with these metrics:

### Cycle Time

The Cycle Time is the average time PRs take to be completed, since they are opened until they are merged or closed (lifetime).

### Commits/PR

The average number of commits per pull requests. 

### Time to Open

Is the average time it takes between opening each pull request. Normally, engineers are working on several PRs at once. With this metric, we can measure how much time does it take to open a new PR since the last one.

We measure it averaging the total number of PRs open in a time interval that you select and multiplying it by the number of work days. Then, we divide by 8 hours (hours of work per day on average). The result, is the Time to Open.

### Time to Merge

Time to Merge is the average time between the first review and the merge. Normally, a long review time implies that there is something wrong with the PR and that will delay the delivery.

---

· ***We do not take weekend days into account for the moment.***