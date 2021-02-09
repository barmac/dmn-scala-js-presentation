---
title: Why we cannot run dmn-scala in the browser yet
author: Maciej Barelkowski
---

# dmn-scala-js

#### why we cannot run dmn-scala in the browser yet

---

### `dmn-scala`

Scala library used in the DMN Engine.

---

### `scala-js`

We can compile Scala code to JavaScript and run it in the browser.

---

### idea

Let's compile `dmn-scala to` JavaScript and run it in the browser:

* :tada: `dmn-testing-plugin` without Java dependency :tada:
* evaluate FEEL in the DMN Editor 100% as the DMN Engine

---

### outcome :boom:

* cryptic linking errors
* cryptic linking errors
* more cryptic linking errors

---

### *gotcha* :shrug:

Your dependencies have to be first compiled for `scala-js`.

---

So do your dependencies' dependencies etc.

---

`dmn-scala` has multiple dependencies.

---

### Maven !== npm

You cannot re-compile artifacts from the repository.

---

Thus, `dmn-scala-js` will remain a dream for now.
