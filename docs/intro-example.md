---
id: intro-example
title: Intro Example
---

Small overview of the ReasonReact API before we start. No worries if some of these are unfamiliar; the docs cover all of them.

```reason
let component = ReasonReact.statelessComponent "Greeting";

/* underscore before names indicate unused variables. We name them for clarity */
let make ::name _children => {
  ...component,
  render: fun self =>
    <button> (ReasonReact.stringToElement "Hello!") </button>
};
```
