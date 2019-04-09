![From Node.js to Deno](title.png)

---

# Rafał Pocztarski

You may know me from Stack Overflow

![rsp](https://stackexchange.com/users/flair/303952.png)

# pocztarski.com

Enough about me

---

# From Node.js<br>to Deno

JavaScript/TypeScript runtime<br>
built with V8 and ~~Go~~ Rust

---

# Architecture

Node = Server-side JS using V8 + libuv in C++

Deno = Server-side TS using V8 + Tokio in Rust

---

# Frameworks

- Fen (a simple Typescript web framework for deno)

---

求不要更新了，老子学不动了 (Issue #25)<br>
https://github.com/denoland/deno/issues/25

没钱用 肯定要学啊 不学就没有钱用 (Issue #27)<br>
https://github.com/denoland/deno/issues/27

your code very six !!! (Issue #31)<br>
https://github.com/denoland/deno/issues/31


---

Going from Go to Rust was proposed very early

<small>
Deno vs Node.js (Issue #11)<br>
https://github.com/denoland/deno/issues/11

拥抱GO 得永生 (Issue #34)<br>
(translation: Embrace GO for eternal life)<br>
https://github.com/denoland/deno/issues/34

Suggestion: Look into porting to Rust and using Tokio (Issue #205)<br>
(interesting discussion)
https://github.com/denoland/deno/issues/205
</small>


---

求你们不要在学了 我跟不上了 我也不想学了<br>
[translation: I don’t want to learn, I can’t keep up, I don’t want to learn.]



Here is NOT the chatroom, behavior yourself!<br>
请不要再灌水了，中国开发者的脸都被你们丢光了。<br>
[translation: Please don't pour any more water. The faces of Chinese developers have been lost by you.]

https://github.com/denoland/deno/issues/27<br>

---

Deno Core

https://github.com/denoland/deno <img alt="GitHub stars" src="https://img.shields.io/github/stars/denoland/deno.svg?style=social" class="stars" height="40" border="0">

Deno Standard Modules

https://github.com/denoland/deno_std <img alt="GitHub stars" src="https://img.shields.io/github/stars/denoland/deno_std.svg?style=social" class="stars" height="40" border="0">

---

Frameworks

- [http](https://github.com/denoland/deno_std/tree/master/http) (std) <img alt="GitHub stars" src="https://img.shields.io/github/stars/denoland/deno_std.svg?style=social" class="stars" height="40" border="0">
- [dinatra](https://github.com/syumai/dinatra) by Syumai (Japan) <img alt="GitHub stars" src="https://img.shields.io/github/stars/syumai/dinatra.svg?style=social" class="stars" height="40" border="0">
- [abc](https://github.com/zhmushan/abc) by Zhmushan (China) <img alt="GitHub stars" src="https://img.shields.io/github/stars/zhmushan/abc.svg?style=social" class="stars" height="40" border="0">
- [expressive](https://github.com/jinjor/deno-playground/tree/master/expressive) by Yosuke Torii (Japan) <img alt="GitHub stars" src="https://img.shields.io/github/stars/jinjor/deno-playground.svg?style=social" class="stars" height="40" border="0">
- [oak](https://github.com/oakserver/oak) by Kitson Kelly (Australia) <img alt="GitHub stars" src="https://img.shields.io/github/stars/oakserver/oak.svg?style=social" class="stars" height="40" border="0">
- [pogo](https://github.com/sholladay/pogo) by Seth Holladay (USA) <img alt="GitHub stars" src="https://img.shields.io/github/stars/sholladay/pogo.svg?style=social" class="stars" height="40" border="0">
- [fen](https://github.com/fen-land/deno-fen) by Dominic Ming (China) <img alt="GitHub stars" src="https://img.shields.io/github/stars/fen-land/deno-fen.svg?style=social" class="stars" height="40" border="0">

---

Databases

[deno-redis](https://github.com/keroxp/deno-redis) by Yusuke Sakurai (Japan) <img alt="GitHub stars" src="https://img.shields.io/github/stars/keroxp/deno-redis.svg?style=social" class="stars" height="40" border="0">

[deno-postgres](https://github.com/bartlomieju/deno-postgres) by Bartek Iwańczuk (Poland) <img alt="GitHub stars" src="https://img.shields.io/github/stars/bartlomieju/deno-postgres.svg?style=social" class="stars" height="40" border="0">

[deno_mysql](https://github.com/manyuanrong/deno_mysql) by EnokMan (China) <img alt="GitHub stars" src="https://img.shields.io/github/stars/manyuanrong/deno_mysql.svg?style=social" class="stars" height="40" border="0">

[Deno Simple Orm](https://github.com/manyuanrong/dso) by EnokMan (China) <img alt="GitHub stars" src="https://img.shields.io/github/stars/manyuanrong/dso.svg?style=social" class="stars" height="40" border="0">

---

Creative feedback 

"Will i like it ? no, i don't like it as i don't like you."

<small>
Please close this project for now. (Issue #53)<br>
https://github.com/denoland/deno/issues/53
</small>

---

???

https://cnodejs.org/topic/5b0fb21b57137f22415c47c8

---

![](deno-issue-53.png)

<small>
https://github.com/denoland/deno/issues/53
</small>

---



---

Alex Hultman, author of µWebSockets - https://github.com/uNetworking - gets banned

---

# Installation<br>For the adventurous

`curl -fsSL https://deno.land/x/install/install.sh | sh`

`iwr https://deno.land/x/install/install.ps1 | iex`

<small>
The scripts above currently just scrape the GitHub releases page:<br>
https://github.com/denoland/deno/releases
</small>

---

Suggestion: Look into porting to Rust and using Tokio (Issue #205)<br>
https://github.com/denoland/deno/issues/205

---

# Current state

Not ready for production yet

<small>
(which is the best time to get involved)
</small>

---

Why it *WILL* get traction

1. Ryan Dahl (his previous project was and still is an amazing success)
2. V8 (Google will promote it)
3. TypeScript (Microsoft will promote it)
4. Rust (Mozilla will promote it)

---

My prediction

The industry will ignore it until it is "ready" and then:

- startups who provide infrastructure and tooling will get business
- people who used it "before it was cool" will get more job offers that they can read

(like it is now with Node.js)

---

# Articles

- [Fen (a simple Typescript web framework for deno)](https://medium.com/@mxz961002/fen-a-simple-typescript-web-framework-for-deno-13cfe84d270c) by 明多牧

---

Modules Registry

https://deno.land/x/

This is a redirection service

<small>
E.g. this install script URL:<br>
https://deno.land/x/install/install.sh<br>
redirects to:<br>
https://raw.githubusercontent.com/denoland/deno_install/master/install.sh
</small>

---

Recommended talks

<small>
- [Ryan Dahl: Original Node.js presentation (2009)](https://www.youtube.com/watch?v=ztspvPYybIY)
- [History of Node.js by Ryan Dahl (2011)](https://www.youtube.com/watch?v=SAc0vQCC6UQ)
- [10 Things I Regret About Node.js by Ryan Dahl (2018)](https://www.youtube.com/watch?v=M3BM9TB-8yA)
- [Deno, A New Server-Side Runtime by Ryan Dahl (2018)](https://www.youtube.com/watch?v=FlTG0UXRAkE)
</small>

---

Resources

<small>
- https://denoland.org/
- https://deno.land/
- https://deno.land/manual.html
- https://deno.land/typedoc/
- https://deno.land/x/
- https://twitter.com/deno_land
- https://github.com/denoland/deno
- https://github.com/denoland/deno/releases
- https://github.com/denoland/deno/issues
- https://github.com/denoland/deno/pulls

</small>

---

# Questions?

Slides: https://pocztarski.com/ntd

## Rafał Pocztarski

## [pocztarski.com](https://pocztarski.com)

"In the original object-oriented systems that were so successful,
messages aren't commands at all. What they are are desires." - Alan Kay
