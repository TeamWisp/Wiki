---
layout: post
title:  "Quality Assurance"
date:   2018-09-27 11:43:16 +0200
permalink: /quality/
weight: 80
---

## Unit Tests

Tests are used to confirm code compiles and functions as it should. Tests are created using *Google Test* and places in the `tests` directory.

To learn how to use Google Test I recommend to look through the primer they supply [on their github](https://github.com/google/googletest/blob/master/googletest/docs/primer.md).

## Report A Bug

We report bugs into Jira. This is done by creating a new issue in the backlog and marking it as a bug. Make sure it has a fitting title and a description. For the description use the bug report format mentioned below.

![](https://i.imgur.com/0VTY1sa.png)

Bugs should be reported in the following format (Formatted in Jira's markup language):

```
h3. Summary:
The price mentioned on the pricing page is not correct.

h3. Steps to Reproduce
Go to the pricing page.

h3. Expected Results
The price for the basic plan should be $29.

h3. Actual Results
The price for the basic plan is currently $25.

h3.  Additional Info
*Version:* 0.1
*Win SDK:* 10.0.17763.0
```

This is what it would look like in the preview window:

![](../../images/jira_bug.png)
