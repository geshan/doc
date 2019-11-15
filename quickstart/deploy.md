---
description: Deploy in production
---

# Deploy

## Deploy

Are you ready to deploy? **Simply push your git repository, that's it**!!!

## Deployment status

You'll be able to watch the activity with Qovery CLI or from the Web interface.

To know what's currently happening on your Qovery account:

```bash
$ qovery status

* Current deployed version        : 7b3aeb5 (Marty McFly) / 2014-05-13 02:56
* In progress deployment          : b0b03ab (Ada Lovelace) / 75% done
* Pending deployments in the pipe : 0
* Total deployments today         : 3
* Total rollback today:           : 0
```

## Code a new feature

As soon as you want to develop a new feature in your code, create a new branch!

{% hint style="info" %}
**A new branch will spawn a dedicated \(production replicated\) environment for you**
{% endhint %}

To know more about it, look at the [branch dedicated section](../extending-qovery/branches.md).
