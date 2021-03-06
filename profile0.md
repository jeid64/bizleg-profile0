% Profile: GitHub
% [Matt Soucy](mailto:msoucy@csh.rit.edu)
  [Liam Middlebrook](mailto:liammiddlebrook@gmail.com)
  [Julien Eid](<mailto:jeid@csh.rit.edu>)
  [Aaron Herting](<mailto:adh2380@rit.edu>)


## Rationale

GitHub is used by an enormous variety of hackers, including us, so we wanted to learn more about its origins

# Organizational Details

---

- GitHub is a Corporation Registered in the State of Delaware
- GitHub was founded, April 10th, 2008
- GitHub's Founding Fathers:
    * Tom Preston-Werner
    * Chris Wanstrath
    * PJ Hyett

---

- All of the original founders are still active with the exception of Tom Preston-Werner.
    - He left GitHub in 2014 after confirmed [harassment allegations]
- GitHub is a private corporation and isn't publically traded
- GitHub has acquired the following companies:
    * Easel - In Browser Web Design Tool Built for Collaboration
    * Ordered List - Gauges, Speaker Deck, Harmony

---

- GitHub hasn't invested in any other companies
- Interestingly enough the first investment in GitHub was for [$100M]
- GitHub has 267 employees, some of which work at their HQ:
    88 Colin P Kelly Jr St (at Brannan St), San Francisco, CA 94107, United States

---

- GitHub doesn't have any other locations
- [http://github.com](http://github.com)
- [http://en.wikipedia.org/wiki/GitHub](http://en.wikipedia.org/wiki/GitHub)
- GitHub does not have any annual reports

[harassment allegations]: http://bits.blogs.nytimes.com/2014/04/21/github-founder-resigns-after-investigation/
[$100M]: http://go.bloomberg.com/tech-deals/2012-07-09-github-takes-100m-in-largest-investment-by-andreessen-horowitz/

# Communications

## Social media for GitHub

- [Twitter](https://twitter.com/github)
- [Twitter](https://twitter.com/githubstatus) (Downtime reporting)
- [LinkedIn](https://www.linkedin.com/company/github)

## Communications channels for GitHub

- GitHub’s press page lists all of their awards that they have received. (<https://github.com/about/press>)
- GitHub also has a blog that has lots of interesting posts. (<https://github.com/blog>)
- They also include a Glossary so writes can better report about what the company does. (<https://help.github.com/articles/github-glossary/>)

## GitHub Conference Participation

- GitHub hosts “GitHub Universe” which is their own conference about working on open source projects as well as gathering tons of people working in open source. (<http://githubuniverse.com/>)
- GitHub also hosts “CodeConf” a two day conference about open source, best practices, documentation, and collaboration. (<http://codeconf.com/>)
- GitHub also attends several other conferences including GDC. (<https://github.com/blog/1961-see-you-at-gdc>)

# Community Architecture

## Github and Government

- Website: <http://government.github.com>
- Repository: <http://github.com/github/government.github.com>
- The project is entirely documentation

---

- `Github and Government` is a website dedicated to sharing open government efforts that involve Github
- Started January 20, 2013, most recent commit March 5, 2015
- Two people ([benbalter][] and [jlord][]) accept all of the [pull requests][]
- [benbalter][] and [jlord][] seem to be the only two maintainers (BDFLs)
- The original developers have remained with the project the entire time.

[benbalter]: https://github.com/benbalter
[jlord]: https://github.com/jlord
[pull requests]: https://github.com/github/government.github.com/pulls?q=is%3Apr+is%3Aclosed


---

- Development has been active throughout its lifetime
- The project would continue fine if one of the two main devs were eaten by a velociraptor
	- Not if the [top 20% of the contributors][contributors] were in a freak bus accident, though - that includes both BDFLs
- No onboarding, since most of it is adding information instead of code

[contributors]: https://github.com/github/government.github.com/graphs/contributors

---

- Ruled by a pair of individuals who try to make sure data is complete and accurate
- Is this the kind of structure you would enjoy working in? Why, or why not?
- This structure is well-suited for this project, but maybe not for a code-based project

# Technology/Product

Section adapted from [EFF](EFF) [Worksheet](http://www.teachingcopyright.org/handout/technology-history-worksheet)

## The Technology Behind GitHub

GitHub is powered completely by [Git][Git Wiki], a distributed source control system.

- Git was originally started by Linus Torvalds, creator of the Linux kernel.
- Git was initially started to track the Linux kernel and was then used by other projects.
- Lots of people interested in working on the same set of files or tracking changes in files could potentially use Git.[][Git Wiki]

## GitHub Using Git

- Created to be a highly distributed SCM, GitHub based their entire product on using Git.
- GitHub now uses git as the tool it uses to track most of their repos and interface with GitHub.
- Contrary to popular belief, Git existed before GitHub. GitHub created a nice visual front end and a great central area for code repos.

## Copyright Law and Creation of Git

- The Linux kernel was originally tracked in BitKeeper, a properitary SCM.
- Devs of BitKeeper resciended license to use it and the kernel was left in the cold.
- Linus became fed up and created his own that would be FOSS so that incident could never happen again.

## Controversy over GitHub and Copyright

- GitHub is not open source, leading to an ironic situation that one of the most central sites for FOSS software isn’t FOSS itself.
- GitHub also has a default license that has been controversial over some of its terms.

[Git Wiki]: http://en.wikipedia.org/wiki/Git_%28software%29
