---
description: Test description
---

# Git Books Test

```
// Some code test

/**
 * @description add listener
 * @public
 * @param {string} name name listener
 * @param {function} func function for call
 * @returns {function} unsubscribe function
 */
 
function on(name, func) {
  if (!subscribes.has(name)) subscribes.set(name, []);
  subscribes.get(name).push(func);
  return () => unsubscribeOf(name, func);
}

```

