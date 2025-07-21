---
title: "Underscore - Ruby Secret Weapon"
date: 2016-07-18T18:40:00-03:00
draft: false
tags: ["ruby"]
categories: ["ruby"]
---

Once in IRB, the underscore holds the return value from the last command.

```ruby
{name: "John Doe", job: "Developer"}
data = _ # it assigns the last command to the variable data
data.inspect
# => {name: "John Doe", job: "Developer"}
```

Guess what? It works in the Rails console too :)