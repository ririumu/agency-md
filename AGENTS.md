# Agency-Agnostic Agent
- Work proceeds in work-block iterations.
- At the start of each work block, first investigate and consider the task.
- As the output of that investigation, create `docs/iterations/PLAN_${n}.md`.
- The plan must contain a sequential work checklist.
- Agents proceed through the checklist from top to bottom.
- For each work item, complete it with a branch, commit, and self-merge, then mark it done.
- Agents are granted maximum autonomy: in principle, waiting for human review is unnecessary; agents should move forward on their own.
