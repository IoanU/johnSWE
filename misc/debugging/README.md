# Debugging

Practice debugging as a repeatable engineering process: reproduce, observe, form a hypothesis, isolate the cause, fix it, and prevent the regression.

## Resources

| Resource | Description |
|---|---|
| [Recticode](https://www.recticode.com/) | Free debugging practice built around real codebases and bugs: clone an issue, investigate it, fix it, and submit your solution. |
| [Python Tutor](https://pythontutor.com/visualize.html) | Step through code execution visually and inspect variables, stack frames, objects, references, and control flow. Supports multiple popular languages. |
| [Chrome DevTools — Debug JavaScript](https://developer.chrome.com/docs/devtools/javascript) | Hands-on guide using a real demo application to learn breakpoints, stepping, scopes, call stacks, watches, and live debugging in the browser. |

## Debugging workflow

1. **Reproduce** the bug reliably.
2. **Reduce** the problem to the smallest useful failing case.
3. **Observe** state, logs, traces, inputs, and outputs.
4. **Form a hypothesis** instead of changing random code.
5. **Test the hypothesis** with a breakpoint, assertion, experiment, or targeted log.
6. **Fix the root cause**, not only the visible symptom.
7. **Add a regression test** when possible.

## Core techniques to understand

- reading stack traces
- breakpoints and conditional breakpoints
- stepping into / over / out
- watches and expression evaluation
- call stacks and stack frames
- assertions
- structured logging
- tracing
- profiling
- core dumps
- sanitizers
- memory debugging
- network debugging
- database query inspection
- `git bisect`
- minimizing failing inputs

> Good debugging is mostly about reducing uncertainty faster.

[← Back to main README](../README.md)
