# 100 Days Of Code - Log

<!-- template
### Day 0: 2020-08-

**Today's Progress**:

**Thoughts**: 

**Link(s) to work**:
-->

### Day 1: 2020-08-09

**Today's Progress**: Experimented with Twitch API / read the docs / made a widget in Vue.

**Thoughts**: Vue <3 - struggled with fetch() headers for a while. Messed with oAuth a bit.

**Link(s) to ~~work~~ docs**: [dev.twitch.tv](https://dev.twitch.tv/)

---

### Day 2: 2020-08-10

**Today's Progress**: Worked on a little PHP backend. It consumes a csv of users and negotiates client-side access to a page.

**Thoughts**: `null`

**Link(s) to work**: `null`

---

### Day 3: 2020-08-11

**Today's Progress**: Continued on that one 👆 :) (NDA, sorry it's boring)

---

### Day 4: 2020-08-12

**Today's Progress**: Continuing with Twitch API stuff, at 4:10am, because I couldn't sleep. I added some environment checking. BG is transparent in prod and `#000` in dev (so I can see it)

**Thoughts**: `null`

**Link(s) to work**: I have decided I'll make it public, but I've gotta clean it up _a little_ first.

---

### Day 5: 2020-08-13

**Today's Progress**: Working on a nuxt.js project for work. Axios request for some data, then gently massage it using `map`, `reduce` and `filter`. 

**Thoughts**: Need to break components into smaller pieces. These components were starting to get messy and unwieldy over time. 

**Link(s) to work**: `null`

---

### Day 6: 2020-08-14

**Today's Progress**: Continuing on the nuxt.js project. Lots of debugging.

**Thoughts**: I moved some of the complicated logic into a jest/spec vanilla js file, and mocked the response, instead of waiting for Axios. This made it easier to work on getting the data "massage" correct.

**Link(s) to work**: `null`

---

### Day 7: 2020-08-17

**Today's Progress**: I took the weekend off. Today I got back up to speed on the backend, and messed around with cookies some more, before I ended up with a gnarly headache and had to take a break.

**Thoughts**: Some of the legacy code is a bit "spaghetti", so this job might benefit from working in a sandbox away from some of the dependent code as well.

**Link(s) to work**: `null`

---

### Day 8: 2020-08-22

**Today's Progress**: Changed my Zsh prompt to the unicorn emoji 🦄

**Thoughts**: The base theme is the default robbyrussel theme. Rather than make a new theme, I've just copied that code to the `~/.zshrc` file. I've just prepended the emoji, so its as simple as modifying the `PROMPT` variable with `PROMPT="🦄 "` followed by `PROMPT += ...normal theme stuff`

**Link(s) to work**: `null`

---

## 61 DAY GAP!

I have had thee worst couple of months. So I don't even care. Picking up in 5... 4... 3... 2... 1...

---

### Day 9: 2020-10-21

**Today's Progress**: Started working on a web scraper using puppeteer. The process of downloading lectures for school is very manual, so this thing is going to assist. Others have tried before me using Python, but I couldn't get those to work. Also I like JS.

**Thoughts**: It's slower and tricker than i expected to deal with things like Single Sign-On, moving around multiple pages, and just getting the selectors right, to make sure you're manipulating the correct piece of DOM. Also made tricky by how ridiculously bad the website i'm working with is put together. 

**Link(s) to work**: [echo-scraper](https://github.com/miclgael/echo-scraper) 🔒 (Private for now)

---

### Day 10: 2020-10-22

**Today's Progress**: I've been working on this workflow for the Alfred app (macOS). 

**Thoughts**: It's fun trying out a new ecosystem, Alfred has its own package manager(?) called [Packal](http://www.packal.org). Also, I learned that the `*.alfredworkflow` extension, is just a renamed `*.zip`, which would have been good to know, like, _yesterday_. 

![Adam Sandler in the wedding singer, with caption "Things that could have been brought to my attention YESTERDAY!"](https://media1.tenor.com/images/5be1d37605f45c2be6b61d35986bc11a/tenor.gif?itemid=6055305)

**Link(s) to work**: [Alfred MAMP Workflow](https://github.com/miclgael/alfred-mamp-workflow/)

---

### Day 11: 2020-10-23

**Today's Progress**: Spent two hours fixing bugs with the scraper project, and now have a functional prototype.

**Thoughts**: It's a bit of a pain working with Puppeteer, constantly authing and re-authing just to test minor bugs. Would be good to do some kind of actual tutorials on best-practices for this kind of use-case. Anyway, excited that the project might actually work. Just a few more things to refactor and I can make the repo public again.

**Link(s) to work**: [echo-scraper](https://github.com/miclgael/echo-scraper) 🔒 (Private for now)


---

### Day 12: 2020-10-24

**Today's Progress**: Stayed up late configuring [pi-hole](https://pi-hole.net). Now blocking ads network-wide in my home. With some bonus extras as well. Not super codey, more sys-adminy, but a little terminal action required so I'm counting it. 

**Thoughts**: Turns out my cheapie router has a secret page to configure DNS settings: `/dnscfg.html`, and another secret page for wifi settings. `/wlcfgadv.html` Thanks to this post on [whirlpool forums](https://whrl.pl/Reonpz) 

**Link(s) to work**: `null`

