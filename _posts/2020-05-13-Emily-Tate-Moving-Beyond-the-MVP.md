---
speaker: Emily Tate
topic: Moving Beyond the MVP
video: https://vimeo.com/148347976
issue: 16
---

Launching new features is hard. This is especially true when you have an established user base that expects more than a half-baked MVP. How do you build things your customers will love without letting scope get out of hand?

This talk will examine the lifecycle of a feature, from ideation through release and review. Using real examples of feature successes and failures, it will offer insights on ways to manage your feature development to be able to deliver value to market incrementally without tarnishing your product’s reputation.

Notes of our discussion
-----------------------
* It is indeed more difficult to introduce a new feature to a mature product in a minimal way, customer have much bigger expectations
* A good approach is GitLab's Minimum Viable Change: https://about.gitlab.com/handbook/product/#the-minimal-viable-change-mvc
* The feature must solve a real problem well -- it is the problem that should be broken down to the minimal chunks, not the amount of "solving" the product provides
* Strong UX research and telemetry helps tremendously -- they tested an incredible amount of things as they iterated.
* An huge dilemma is always finding the right trade-off in the solutions chosen during the development.
  - An elegantly engineered solution will be expensive, which makes iteration on the product idea itself costly and slow.
  - Some engineering choices, however, might lock us in and make subsequent changes exponentially more expensive.
  - Three tactics can help here: (1) always discuss the long-term vision for a feature along with the current, minimal scope (2) write a list of engineering tradeoffs made (3) identify the decisions and assumptions that would cost us the most in the future if they had to be changed or that were proven to be false and try to avoid the lock-ins in those specific cases
