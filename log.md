# 100 Days Of Code - Log

<!-- ### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com) -->

## Why am I doing this?

I've always wanted to write a blog... and code, and draw, and learn a bunch of fun things that don't seem to materialize. I want to do a lot of things, but I lack the **focus** to *actually* do them - or at least try.

So my overarching goal for doing #100DaysOfCode is to practice self-discipline by making time to do the things I want to do. Specifically, I aim to:

* learn the basics of web dev & design through freeCodeCamp's **Responsive Web Design Certication**
* come up with a working blog or personal site (Jekyll, maybe?)
* connect more with the coding community

---

### Day 0: October 27, 2019 🚀 Sunday

**Today's Progress**: Set up this GitHub repo.

**Thoughts**: Get more confident with using Git. I have an idea of the workflow, but I needed to double check before pressing Enter to see if I was using the right parameters. Make more mistakes - it will speed up the learning process.

**Resources**: 
* [Learn Git Branching](https://learngitbranching.js.org/)
* [What is the difference between origin and upstream on GitHub?](https://stackoverflow.com/questions/9257533/what-is-the-difference-between-origin-and-upstream-on-github)
* [What's the difference between git fetch and git pull?](https://www.git-tower.com/learn/git/faq/difference-between-git-fetch-git-pull)
* [Checking, adding remote repos (upstream and origin)](https://webkul.com/blog/syncing-local-repository-with-remote-repository-on-github/)

### Day 1: November 3, 2019 ~ Sunday

**Today's Progress**: Started developing my personal site using Jekyll.

**Thoughts**: I've been in a rut recently, anxiety and perfectionism preventing me from continuing my coding journey. After reading a [blog post](https://www.freecodecamp.org/news/how-to-get-a-developer-job-in-less-than-a-year-c27bbfe71645/) by Alexander Kallaway (creator of #100DaysOfCode challenge), I got inspired to push through, knowing that what I'd come up with this day might suck, but it's fine, because I'll work on it again the next day, and the day after that, and so on, continuously improving with every iteration.

That's when I realized: this challenge is not just about learning how to code, but also about realizing the value of small, consistent work over big, sporadic effort.

**Notes:**
* Practice Vim to use it more seamlessly
* I'm surprised how intuitive Vim is: automatic indenting, syntax highlighting, screen flashes when it detects a syntax error (I thought it was just broken lol)
* Interplay of Git and Jekyll (files to include in gitignore, pushing local repo to GitHub)
* `ls -R` - list all files, including subdirectories (recursively)
* `pwd` - print working directory
* `mkdir` - create a directory (folder)
* `touch` - create a file (use mkdir first to create a new folder, then use `touch <dir>/<file>`)

**Resources:**
* [Why do I have to "git push --set-upstream origin <branch>"?](https://stackoverflow.com/questions/37770467/why-do-i-have-to-git-push-set-upstream-origin-branch)
* [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.freecodecamp.org/news/git-the-laymans-guide-to-understanding-the-core-concepts/)
  * Git's core functionality is to create save points in files - like in video games
  * explained why "git add -A" is better than "git add ."
  * better explanation of git checkout
* [How to Create a Pull Request on GitHub - DigialOcean](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) -- process for contributing to open-source projects (via forked repos)

### Day 2: November 4, 2019 ~ Monday

**Today's progress:** Reviewed Jekyll mechanics, pushed my personal site to a remote GitHub repo.

**Thoughts:** A little slow today as I mostly just repeated what I did yesterday, but with more understanding of what each command does and how stuff works.

Since I'm also practicing Git, I copied an idea from a project that uses two branches: `master` and `develop` (turns out this is a [best practice in Git branching](https://nvie.com/posts/a-successful-git-branching-model/)).

**Resources:**
* [Using Jekyll with Bundler](https://jekyllrb.com/tutorials/using-jekyll-with-bundler/)
* [Bundle Recommended Workflow with Version Control](https://bundler.io/v2.0/bundler_workflow.html)
* [Git Handbook](https://guides.github.com/introduction/git-handbook/)
* [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
* [Git Pro book](https://git-scm.com/book)
* [Comparing Git Workflows](https://www.atlassian.com/git/tutorials/comparing-workflows)

### Day 3-4: November 5-6, 2019 ~ Tue-Wed

**Today's progress:** Read Git Pro (I'm on [chapter 2.3](https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History), learned [a little bit of regex](https://www.youtube.com/watch?v=bgBWp9EIlMM), and continued learning Jekyll.

**Thoughts:** I planned to finish Jekyll's Step by Step Tutorial (I'm already on [Collection](https://jekyllrb.com/docs/step-by-step/09-collections/)), but I actually fell asleep during a break. That's good because it means I'm not lacking in the motivation department, but I should watch my energy lest I should burn out.

**Resources:**
* [Tom Critchlow](https://tomcritchlow.com/) -- main blog inspo (*"Built using Jekyll, hosted on Github. All pixels designed and built by myself"*)
* [Let Jekyll --watch](https://jekyll-windows.juthilo.com/4-wdm-gem/) -- check out if you have time to learn about the `wdm` gem (message "please add the following to your gemfile" when I'm running `build exec jekyll serve`)
* Learn more about [Sass](https://sass-lang.com/)

### Day 5: November 9, 2019 ~ Saturday

**Today's progress:** Finished vimtutor! 🎉

**Thoughts:** I realized that vimtutor is just the tip of the iceberg, and there are better/faster ways of doing things (like `D` and `C` instead of `d$` and `c$`, respectively)

I also got confused with my setup because I was using Vim via Git Bash (which came with Git installation), but I was referencing the vimrc in the standalone Vim I installed separately. **Opportunity for learning**, but had to stop because I was getting obsessed with optimizing my vimrc instead of actually coding.

Some notes:
- Are vimrc files inherited? i.e. configs in system vimrc are inherited to user vimrc (my guess is no. I found a [workaround](https://unix.stackexchange.com/questions/423301/extend-default-configuration-of-vim) and [why `:runtime` is better than `:source`](https://vi.stackexchange.com/questions/9250/includes-in-vimrc) )
- Should I just use Vim that comes with Git Bash? Or is it better to use Windows-native Vim? (extending Vim with plugins like Powerline, etc.)

** Resources:**
- [The Vim book](http://www.truth.sk/vim/vimbook-OPL.pdf) by Steve Oualline -- further reading in vimtutor
- [Other Vim books](https://iccf-holland.org/vim_books.html) via [Bram Moolenaar's site](https://moolenaar.net/) (creator of Vim) -- also check out "Learning the Vi and Vim Editors" which is the other book mentioned in vimtutor
- [Top 50 Vim Configuration Options](https://www.shortcutfoo.com/blog/top-50-vim-configuration-options/)
- Derek Wyatt's [Vim Video Tutorials](http://derekwyatt.org/vim/tutorials/index.html)
- [Vim Training Class 1 - Basic motions and commands](https://www.youtube.com/watch?v=Nim4_f5QUxA) by Shawn Biddle
