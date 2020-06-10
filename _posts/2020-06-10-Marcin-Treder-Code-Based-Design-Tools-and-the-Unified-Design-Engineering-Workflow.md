---
speaker: Marcin Treder
topic: Code–Based Design Tools and the Unified Design–Engineering Workflow
video: https://www.ustream.tv/recorded/124494683
issue: 9
---

Digital product design have grown exponentially over the last decade. From 'a cherry on top' to a household name valued by nearly everyone. The teams and budgets are getting bigger and bigger, but with all this power comes responsibility – we’re expected to deliver more, at a higher level of quality and… faster. Scalability of the design process became a requirement.

To answer this challenge companies all over the world started to invest into design systems. Unfortunately the problems of scale did not magically disappear. Design systems, deeply rooted into the coded foundation of digital products, lacked any natural and automatic connection to a vast majority of design tools. Why? Majority of design tools operate on the level of vector graphics and hence cannot in any way understand production code and connect to it.

Note from our conversation
-------------------------

* Development tooling and workflow support is indeed amazing compared to what UI/UX has.
* There are two main drivers for making UX code:
  - Make use of the entire ecosystem of code handling tools which usually revolve around handling text. This is mainly a tooling question: if the design apps can create consistent, easy-to-read UI specifications in a text format and we can find a good way to view the diffs in them, it's done.
  - Save the work that's required when turning a UX design into production code. It's a risky thing, as it's similar to trying to reuse PoCs as production code -- designs and production code have different requirements. What can be really useful is the ability to automatically reuse any changes made in production code so that there's no need to maintain two parallel tracks for the design and production code.
* Most of these problems are solved through good widgeting systems and DSLs to represent a UI design. In the Microsoft world, XAML is popular and works well, but none of us knew enough about the landscape to know what else is available out there on other tech stacks
