Title: This Week in Rust 401
Number: 401
Date: 2021-07-28
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](http://rust-lang.org) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) or [send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

## Updates from Rust Community

### Official

* [Inside] [1.54.0 pre-release testing](https://blog.rust-lang.org/inside-rust/2021/07/26/1.54.0-prerelease.html)

### Project/Tooling Updates

* [rust-analyzer Changelog #87](https://rust-analyzer.github.io/thisweek/2021/07/26/changelog-87.html)
* [CGlue Today And The Road Ahead](https://blaz.is/blog/post/cglue-012-and-the-road-ahead/)
* [Black Hat Rust: July Update](https://kerkour.com/blog/black-hat-rust-july-update/)
* [Updates from the Tinyverse - July 2021](https://tinyverse.substack.com/p/updates-from-the-tinyverse-july-2021)

### Observations/Thoughts

* [Towards Inserting One Billion Rows in SQLite Under A Minute](https://avi.im/blag/2021/fast-sqlite-inserts/)
* [Async and asleep: designing our future embedded applications](https://tweedegolf.nl/blog/58/async-and-asleep-designing-our-future-embedded-applications)
* [My Rust development workflow (after 2+ years full-time)](https://kerkour.com/blog/rust-development-workflow/)
* [Dealing with Out-of-memory Conditions in Rust](https://www.crowdstrike.com/blog/dealing-with-out-of-memory-conditions-in-rust/)
* [Rust for Linux redux](https://lwn.net/Articles/862018/)
* [My experience crafting an interpreter with Rust](https://ceronman.com/2021/07/22/my-experience-crafting-an-interpreter-with-rust/)
* [Rust: First Thoughts](https://dev.to/mapoulos/rust-first-thoughts-7l0)
* [Mutable statics have scary superpowers! Do not use them](https://blog.kodewerx.org/2021/07/mutable-statics-have-scary-superpowers.html)
* [9 advantages of programming in Rust](https://tim.mcnamara.nz/post/657832047640985600/nine-advantages-of-programming-in-rust)
* [audio] [AreWePodcastYet - 07 Georg Semmler on Diesel!](https://soundcloud.com/arewepodcastyet/awpy-07-georg-semmler-on-diesel)

### Rust Walkthroughs

* [Awesome Unstable Rust Features](https://lazy.codes/posts/awesome-unstable-rust-features/)
* [How I Built a Cross-Platform Desktop Application with Svelte, Redis, and Rust](https://css-tricks.com/how-i-built-a-cross-platform-desktop-application-with-svelte-redis-and-rust/)
* [Understanding Rust futures by going way too deep](https://fasterthanli.me/articles/understanding-rust-futures-by-going-way-too-deep)
* [Understanding Rust's 'serde' using macro expansion](https://owengage.com/writing/#understanding-serde-macro-expansion)
* [Rust - Writing Parsers With nom Parser Combinator Framework](https://iximiuz.com/en/posts/rust-writing-parsers-with-nom/)
* [✨🥞 Rust Visualized: The Stack, the Heap, and Pointers](https://dev.to/ender_minyard/rust-visualized-the-stack-the-heap-and-pointers-a5c)
* [First steps with Rust declarative macros!](https://dev.to/rogertorres/first-steps-with-rust-declarative-macros-1f8m)
* [diceroller, a sample Rust project](https://blog.frankel.ch/start-rust/8/)
* [Ditching `try..catch` and `null` checks with Rust](https://blog.logrocket.com/ditching-try-catch-and-null-checks-in-rust/)
* [Implementing Merge Sort in Rust](https://dev.to/felixfaisal/implementing-merge-sort-in-rust-4ko8)
* [Emulating abstract base classes in Rust](https://dev.to/mdoerner/emulating-abstract-base-classes-in-rust-3ai6)
* [Rust #6: Exploring crates](https://dev.to/cthutu/rust-6-exploring-crates-3p6i)
* [Rust and WebAssembly Serverless Functions in Vercel](https://thenewstack.io/rust-and-webassembly-serverless-functions-in-vercel/)
* [28 Days of Rust -- Part 1: Ownership and the Borrow Checker](https://medium.com/comsystoreply/28-days-of-rust-part-1-ownership-and-the-borrow-checker-977a17e5b733)
* [The Rust dbg! macro](https://edgarluque.com/blog/rust-dbg-macro)
* [video] [Building a Web Application with Rust - Part X - VanillaJS FrontEnd](https://youtu.be/mgGPD6IVUbI)
* [video] [Rust Bevy Tutorial - Enemy Formation & Attack (part 3/3)](https://youtu.be/4nEUX2hf2ZI)
* [video] [How to create an AWS Lambda in rust](https://www.youtube.com/watch?v=PmtwtK6jyLc)

### Research

* [Performance vs Programming Effort between Rust and C on Multicore Architectures: Case Study in N-Body](https://arxiv.org/abs/2107.11912)
* [Revisiting Prechelt's paper and follow-ups comparing Java, Lisp, C/C++ and scripting languages](https://renato.athaydes.com/posts/revisiting-prechelt-paper-comparing-languages.html)
* [Programming Rules to Develop Secure Applications with Rust](https://www.ssi.gouv.fr/en/guide/programming-rules-to-develop-secure-applications-with-rust/)

### Miscellaneous

* [This finally happened: rust made more sense](https://www.reddit.com/r/rust/comments/or9r1h/this_finally_happened_rust_made_more_sense/)
* [Edward Snowden endorses Rust for more secure computing](https://www.reddit.com/r/rust/comments/os94ur/edward_snowden_endorses_rust_for_more_secure/)
* [I bet I can do that in rust!!. Generic types are more powerful than most of us thought](https://www.reddit.com/r/rust/comments/opkcuh/i_bet_i_can_do_that_in_rust_generic_types_are/)

## Crate of the Week

This week's crate is [dylint](https://github.com/trailofbits/dylint), a tool for running Rust lints from dynamic libraries.

Thanks to [George Hahn](https://users.rust-lang.org/t/crate-of-the-week/2704/938) for the suggestion.

[Submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Call for Participation

Always wanted to contribute to open-source projects but didn't know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

* [rust-embedded/cross - Call for help: more maintainers wanted](https://github.com/rust-embedded/cross/issues/574)

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines].

[guidelines]: https://users.rust-lang.org/t/twir-call-for-participation/4821

## Updates from Rust Core

280 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2021-07-12..2021-07-19

* [handle non-integer const generic parameters in debuginfo type names](https://github.com/rust-lang/rust/pull/87082)
* [warn about useless assignments of variables/fields to themselves](https://github.com/rust-lang/rust/pull/87129)
* [suggest a path separator if a stray colon is found in a match arm](https://github.com/rust-lang/rust/pull/87101)
* [add diagnostics for mistyped inclusive range](https://github.com/rust-lang/rust/pull/87071)
* [various diagnostics clean ups/tweaks](https://github.com/rust-lang/rust/pull/87225)
* [compute a better `lint_node_id` during expansion](https://github.com/rust-lang/rust/pull/87146)
* [TAIT: infer all inference variables in opaque type substitutions via `InferCx`](https://github.com/rust-lang/rust/pull/87200)
* [remove refs from `Pat` slices](https://github.com/rust-lang/rust/pull/87140)
* [shrink the `CrateStore` dynamic interface](https://github.com/rust-lang/rust/pull/87117)
* [loop over all opaque types instead of looking at just the first one with the same DefId](https://github.com/rust-lang/rust/pull/87107)
* [cache expansion hash globally](https://github.com/rust-lang/rust/pull/87044)
* [perf: noise and variance](https://github.com/rust-lang/rustc-perf/pull/902)
* [some perf optimizations and logging](https://github.com/rust-lang/rust/pull/87203)
* [update Rust Float-Parsing to use the Eisel-Lemire algorithm](https://github.com/rust-lang/rust/pull/86761)
* [stabilize `[T; N]::map(_)`](https://github.com/rust-lang/rust/pull/87174)
* [split `MaybeUninit::write' into new feature gate and stabilize it](https://github.com/rust-lang/rust/pull/86344)
* [mark Option::insert as `must_use`](https://github.com/rust-lang/rust/pull/87196)
* [added `Arc::try_pin`](https://github.com/rust-lang/rust/pull/85579)
* [hashbrown: replace some custom unsafe code with `array::map`](https://github.com/rust-lang/hashbrown/pull/281)
* [hashbrown: optimize `find`](https://github.com/rust-lang/hashbrown/pull/279)
* [cargo: deduplicate compiler diagnostics](https://github.com/rust-lang/cargo/pull/9675)
* [cargo: add `d` as an alias for doc](https://github.com/rust-lang/cargo/pull/9680)
* [clippy: fix false positives and document `branches_sharing_code` lint](https://github.com/rust-lang/rust-clippy/pull/7462)
* [clippy: new lint: `self_named_constructor`](https://github.com/rust-lang/rust-clippy/pull/7403)
* [clippy: add `Arc` to `redundant_allocation`](https://github.com/rust-lang/rust-clippy/pull/7308)
* [clippy: fix ICE in `is_integer_const`](https://github.com/rust-lang/rust-clippy/pull/7473)

### Rust Compiler Performance Triage

A very quiet week with only improvements. There was one possible regression, but it was removed from consideration due to only barely impacting a somewhat noisy stress-test benchmark. Untriaged pull requests continue to pile up, but there is still not a good process for dealing with them. 

Triage done by **@rylev**.
Revision range: [5c0ca08..998cfe5](https://perf.rust-lang.org/?start=5c0ca08c662399c1c864310d1a20867d3ab68027&end=998cfe5aad7c21eb19a4bca50f05a13354706970&absolute=false&stat=instructions%3Au)

0 Regressions, 3 Improvements, 0 Mixed; 0 of them in rollups

[Full report here](https://github.com/rust-lang/rustc-perf/blob/master/triage/2021-07-27.md).

### Approved RFCs

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* [#[derive(Default)] on enums with a #[default] attribute](https://github.com/rust-lang/rfcs/pull/3107)

### Final Comment Period

Every week [the team](https://www.rust-lang.org/team.html) announces the
'final comment period' for RFCs and key PRs which are reaching a
decision. Express your opinions now.

### [RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)

* [Stabilize Cargo's weak-dep-features and namespaced-features.](https://github.com/rust-lang/rfcs/pull/3143)

### [Tracking Issues & PRs](https://github.com/rust-lang/rust/labels/final-comment-period)

* [disposition: merge] [Allow reifying intrinsics to fn pointers.](https://github.com/rust-lang/rust/pull/86699)
* [disposition: merge] [Associated functions that contain extern indicator or have #[rustc_std_internal_symbol] are reachable](https://github.com/rust-lang/rust/pull/86492)
* [disposition: merge] [Commit to not supporting IPv4-in-IPv6 addresses](https://github.com/rust-lang/rust/pull/86335)
* [disposition: merge] [Implement Extend<(A, B)> for (Extend<A>, Extend<B>)](https://github.com/rust-lang/rust/pull/85835)

### New RFCs

*No new RFCs were proposed this week.*

## Upcoming Events

### Online

* [July 27, 2021, Dallas, TX, US - Last Tuesday - Dallas Rust](https://www.meetup.com/Dallas-Rust/events/jqxqwrycckbkc/)
* [August 3, 2021, Buffalo, NY, US - Buffalo Rust User Group, First Tuesdays - Buffalo Rust Meetup](https://www.meetup.com/Buffalo-Rust-Meetup/events/jxfdjsycclbfb/)
* [August 10, 2021, Seattle, WA, US - Monthly meetup - Seattle Rust Meetup](https://www.meetup.com/Seattle-Rust-Meetup/events/gskksrycclbnb/)

### North America

* [July 27, 2021, Chicago, IL, US - Rust in production at Tempus - Chicago Rust Meetup](https://www.meetup.com/Chicago-Rust-Meetup/events/279131036)
* [August 11, 2021, Atlanta, GA, US - Grab a beer with fellow Rustaceans - Rust Atlanta](https://www.meetup.com/Rust-ATL/events/lhpkmsycclbpb/)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

# Rust Jobs

**The Tor Project**

* [Software Developer, Rust (Remote)](https://www.torproject.org/about/jobs/rust-dev/)

**Stockly**

* [Back-end developer - TechOps team (Rust, GRPC, PostgreSQL) (Paris, FR)](https://www.welcometothejungle.com/fr/companies/stockly-1/jobs/back-end-developer-rust-grpc-postgresql_paris)

**Rhebo GmbH**

* [Rust Software Engineer - Focus Networks (DE)](https://germantechjobs.de/en/jobs/Rhebo-GmbH-Softwareentwickler-Rust---Schwerpunkt-Netzwerk-wmd)

**Kraken**

* [Senior Banking Engineer - Rust (Remote)](https://jobs.lever.co/kraken/2863623f-13c9-4f50-992d-7c25736a60f9)
* [Senior Backend Engineer - Rust - Core Backend (Remote)](https://jobs.lever.co/kraken/4c864c8f-bde6-443d-b521-dd90df0e9105)

**Lumeo**

* [Senior Backend Engineer (Rust) (Remote EU)](https://www.lumeo.com/careers/senior-backend-engineer-rust)
* [Senior Systems Engineer (Rust) (Remote EU)](https://www.lumeo.com/careers/senior-systems-engineer-rust)

**Tweede golf**

* [Lead Developer Embedded Rust (Nijmegen, NL)](https://tweedegolf.nl/vacatures/2/lead-developer-embedded-rust)
* [Embedded software engineer (Nijmegen, NL)](https://tweedegolf.nl/vacatures/11/medior-embedded-engineer)

**Kollider**

* [Junior Backend Engineer (Remote)](https://kollider.homerun.co/junior-backend-engineer/en)
* [Senior Backend Engineer (Remote)](https://kollider.homerun.co/senior-backend-engineer/en)
* [DevOps Engineer (Remote)](https://kollider.homerun.co/devops-engineer/en)


*Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) to get your job offers listed here!*

# Quote of the Week

> Tip: whenever you wonder if Pin could be the solution, it isn't

– [@SkiFire13 on the official Rust Discord](https://discord.com/channels/442252698964721669/448238009733742612/866312170890330122)

Thanks to [Kestrer](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1071) for the self-suggestion!

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), and [cdmistman](https://github.com/cdmistman).*

<small>[Discuss on r/rust](https://www.reddit.com/r/rust/comments/k5nsab/this_week_in_rust_367/)</small>