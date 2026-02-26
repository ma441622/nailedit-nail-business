## What I Built
I built the a button featured in the header that gives the ability to change the  Nailed It Nail Website to dark mode and have the page remember the state.

## Micro - Iteration
I enjoyed micro-iteration, it feels easier to catch and repair any errors as you can closely follow the suggestions made by the assistant. It however, doesn't feel natural, but feels more introspective. It's a shame it uses so many tokens.

## What Did Self-Review Catch
In this more complex tool, self-review caught a lot of bug issues or changes that would affect the accessibility of the website. For example in Step 2, it found a universal convention where websites usually go from light to dark mode and not vice versa, so it implemented that change to fit standard conventions. The bug issues mainly came from Step 4, after adding Javascript it noticed there were lack of null checks and easier ways to implement the code without having to affect all the pages. I would've done this had my token usage not been so low.

## Tool Usage
I've been using Claude and thinking about making the switch to Github Copilot, but we will see. I like how it broke down the steps and was ready to implement the next after reviewing changes and necessary fixes. This might be what stops me from making the switch.

## Self-review patterns
After asking, the AI would usually notice bugs such as the white flashing screen when users would change to dark mode after implementing localStorage. In this project, I myself didn't notice any unusual changes.

## Browser vs CLI
To be truthful, I had realized we were supposed to use the browser experience too late into the assignment. However, I watched some YouTube videos and attempted to interact with it for my calculator component. I believe the browser has a more effective interface- allowing you to plan vs. allow auto-application to the code and also highlights key information in the code it's giving you. Plus, it already has GitHub integrated, so it's much easier to maintain a repo. However, CLI feels much more integrated and closer to your project if that makes sense. I feel I'm fully able to control and understand changes that are being made. I prefer CLI for that reason.

## When to use micro-iteration
I would use micro-iteration when I'm not used to using a certain programming language or when I have to implement a huge feature that could possibly break the entire site if done incorrectly. The self-review tool makes it so that the chances of causing bugs are slimmer than usual.