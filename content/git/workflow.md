---
title: "Workflow"
date: 2022-02-04T20:30:31-06:00
draft: false
---


We commit in branches and open pull requests on the default branch (`main`|`master`).

{{< columns >}}


## New Code
Commit to your new branch


<--->


## Open a PR
Get some reviews


<--->


## Merge into default branch
Merge it, Merge it


{{< /columns >}}


{{< mermaid class="text-center">}}
flowchart LR;
    A[CODE]-->B[REMOTE BRANCH];
    B-->C[PULL REQUEST];
    C-->D[REVIEW];
    D-->E[MERGE];
    E-->F[DEPLOY];
{{< /mermaid >}}
