---
speaker: David Khourshid
topic: State of the Art Web User Interfaces with State Machines
video: https://www.youtube.com/watch?v=OVS9cKNK00U
issue: 192
---

As the number of possible states in your app grows, developing UIs can become exponentially more complex. With the help of finite automata, or finite state machines (FSMs), you will be able to manage your app's states in a simple, robust way, and even visualize them! In this session, we will discover how FSMs and statecharts can take your UIs to the next level, with innovative techniques for implementing, testing, and visualizing your app's finite states in a robust, automated way, with plenty of use cases, demos, and resources.

Finite state machines are an extremely important topic for any software developer who wants to create robust systems and user interfaces, and they're nothing new: FSMs have been used for over 50 years in applications from electronics to video games. Unfortunately, FSMs are seldom used explicitly when creating user interfaces, because it's much easier to implement UIs from a bottom-up approach, which is adding code inside event handlers that mutate and juggle state when needed.

However, this approach means that the entire app flow is inside the mind of the developer, which makes understanding an app's logic difficult to understand, test, and extend when more features are needed. FSMs and statecharts solve this problem elegantly by making the transition between states explicit. I will be presenting an innovative approach to representing these declaratively, which gives developers many advantages: - An easily configurable representation of business logic and user flows - A way to parse and visualize those state machines - Sharing state machines between different languages (!!) - Automatically generating comprehensive tests for every single state-to-state flow in your app (never forget a unit/integration test again) - Statically analyze and optimize state machines (improved performance and user experience) - TypeScript or Flow can enforce finite states/actions for better developer experience.

