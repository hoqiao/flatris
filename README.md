[![Flatris](flatris.png)](https://flatris.space/)

![](https://github.com/skidding/flatris/workflows/ci/badge.svg)

> **Work in progress:** Flatris has been recently redesigned from the ground up and turned into a multiplayer game with both UI and server components. This has been an interesting journey and I plan to document the architecture in depth. **[Stay tuned](https://twitter.com/skidding)**.

[![Flatris](flatris.gif)](https://flatris.space/)

> **Contribution disclaimer:** Flatris is a web game with an opinionated feature set and architectural design. It doesn't have a roadmap. While I'm generally open to ideas, I would advise against submitting unannounced PRs with new or modified functionality. That said, **bug reports and fixes are most appreciated.**

Thanks [@paulgergely](https://twitter.com/paulgergely) for the initial flat design!

Also see [elm-flatris](https://github.com/w0rm/elm-flatris).

::: mermaid
graph TD
   A(Coffee machine <br>not working) --> B{Machine has power?}
   B -->|No| H(Plug in and turn on)
   B -->|Yes| C{Out of beans or water?} -->|Yes| G(Refill beans and water)
   C -->|No| D{Filter warning?} -->|Yes| I(Replace or clean filter)
   D -->|No| F(Send for repair)
:::
