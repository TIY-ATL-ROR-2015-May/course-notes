# A Postwork Confessional

> Brit Butler, TIY Atlanta
> July 30th, 2015

My dearest students, y'all, congratulations.

I've been a bit nervous about writing this because I feel like
I should have something authoritative and objective to say.
But better that I write something than nothing at all.

First of all, I'm proud of your hard work and how far you've come.
But you probably knew that. Keep being patient with yourselves,
curious about the magic of computing, and respectful of your peers.

## Now What?

Three big notes here:

1. Your focus should be the job hunt, marketing yourself,
   and more Ruby/Rails programming for a little bit.

2. As graduates of this course, my door is always open to you.
   I'll respond to emails and slack messages as best I'm able.
   If you're interested in exploring something new, I'm happy to give you pointers if at all possible.

3. Keep learning and be mindful of impostor syndrome.
   You'll never know it all, neither will anyone else, and that's good.

**tl;dr: Figure out what makes you excited about programming and chase it relentlessly.**

## Disclaimer

What comes out of my mouth is not gospel.

I'm going to suggest some things to look into to broaden your horizons over
the next year or two. These things are a bit open ended and they are colored
by my own biases and background. I'll try to point out where my preferences
are influencing suggestions and where suggestions depend on the path you
want to pursue.

Shortly below you'll find a list of suggestions and a list of resources.
There's a chance I'll add more resources to the list over the next week or so.
The material will vary between abstract/conceptual content and code/project-focused technical content.

As mentioned in the tldr above, you should do what *interests* you.
Don't view the below as an exhaustive task list to complete,
look at it as a jumping off point to interesting destinations.

## The Confession

I have not historically been very interested in web development.
I got into a career making web apps mostly by accident.

I have always been driven by a curiosity about how computers work,
why they do the things they do, and how to get them to behave differently.

And the great news (for me) has been that if you have a solid understanding
of how computers work in general, you can apply this to the particulars of
web apps in a pretty straightforward way.

Think back to every time you were impressed by my speed debugging a problem
you'd spent an hour staring at. I attribute my ability to do this not to
tons of experience with Ruby and Rails but to many hours spent working on
simple programs and thinking about the *fundamentals*.

In as much as I have something controversial to say, it's this:

    Don't forget to sharpen your fundamentals and work on things beyond the web.

If you think about it, the main time we had to focus on the "fundamentals"
were the first 2-4 weeks of the course. After that, we got wrapped up in
web apps and MVC. Now, don't get me wrong, MVC is great. But when you see
a new problem, I'd prefer you not to first think "How do I break this into
a model, controller, and view?"

The more you can broaden your horizons, the more ways you can think of to
break up and decompose problems, the better off you'll be. Seeing everything
through the lens of MVC and Rails limits your view. Keep learning more
about Rails but don't forget to learn things that might not seem
immediately applicable to your career.

Anyway, enough about that. I'll get off my soap box.

## Suggestions

### Reinforcement

* Write more tests. Seriously, go back and try to write a tested, terminal version of checkers or the todo list app.
  Write some tests for your final project if you haven't. Read about testing. It gives you more leverage over your code.

* Try to learn more about Frontend. I'm planning to follow my own advice here and redesign my personal site over the break.
  I'm not saying to become a JS wizard. Being able to do decent markup and layout (even with a CSS framework) is a big win.

### Unix / System Administration

* Get your own server and play with Linux. It's cheap!
  Get a $5/month [DigitalOcean droplet](https://www.digitalocean.com/pricing/)
  (I have a Linode but whatevs) and install Ubuntu on it.
  Or even just play with installing and configuring Debian on a spare computer.
  I played with Linux for 3 years before I really started programming.

  The advantage I think is that Linux makes it a lot easier to see that Operating Systems aren't
  much more magical than other programs. Over time you come to see the different pieces of software
  that make up a "Desktop" or "Server", where they live on the filesystem, and how they're stitched
  together with config files. From using Windows and Mac, you come to feel that an OS is a single big
  thing but it's actually many little pieces that can be swapped and tweaked in interesting ways.

  Try a little of the System Administration/Operations side of life.
  Start by just following along with the [tutorials][initial-setup], then set up a basic FTP server, or a simple
  website served by Apache or NGINX, or maybe even some cool Open Source software like [ownCloud](https://owncloud.org).

  Eventually, you might even want to try [hosting your own Rails apps][rails-tutorial]!

[initial-setup]: https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-14-04
[rails-tutorial]: https://www.digitalocean.com/community/tutorials/?q=rails

### Programming Paradigms

Different languages present different approaches to solving problems.
These are often broadly grouped into so-called "paradigms".

Ruby is an Object Oriented language and that is primarily what you've been exposed to.
It is useful not only to see more OO Design and other versions of OO (like Smalltalk),
but also to see alternatives like Functional Programming, Logic Programming, and so on.

#### Object Orientation

We could all use more practice with OO Design, including me.

The best single resource I can think of is Sandi Metz' [Practical OO Design in Ruby][poodr].
It's $30 and more than worth picking up and reading through at least twice.

If you're interested in a deeper dive after that, I really would recommend playing with
[Pharo Smalltalk][pharo] and perhaps reading Kent Beck's famous [Smalltalk Best Practice Patterns][sbpp]
which is purported to be one of the best exemplars of OO Design, regardless of what language you're using.

[pharo]: http://pharo-project.org
[poodr]: http://www.poodr.com
[sbpp]: http://devblog.avdi.org/2011/09/20/sbpp-1-introduction/

#### Functional Programming

There is no easy road to a completely new programming paradigm. Everything will seem alien at first
but that's good. It's the sound of your brain stretching.

I think an excellent place to start is [Functional Programming in Scala][fps] and my friend
[Paul Snively's review][psr] speaks to why a bit. It's a bonus that Scala is ultimately a
hybrid Object/Functional language and that its usage in industry is growing.

If you're still hooked and want more after that, maybe get a look at programming in a dedicated
Functional language and read Real World Ocaml or Real World Haskell.

[fps]: http://www.amazon.com/Functional-Programming-Scala-Paul-Chiusano/dp/1617290653
[psr]: http://www.amazon.com/review/R8P9W8Z7QXLWW/ref=cm_cr_dp_title?ie=UTF8&ASIN=1617290653&channel=detail-glance&nodeID=283155&store=books

### Fundamentals of Software Design

Read one of the [Structure and Interpretation of Computer Programs][sicp] or [Paradigms of AI Programming][paip]. Please.
Here's a [glowing endorsement of SICP][sicp-review] from Google's Director of Research.
Here's a [great review of PAIP][paip-review] from Eli Bendersky on why PAIP is really worth reading.

Okay, fine, here's the thing.

[paip]: http://norvig.com/paip.html 
[paip-review]: http://www.amazon.com/Paradigms-Artificial-Intelligence-Programming-Studies/product-reviews/1558601910/ref=cm_cr_dp_synop?ie=UTF8&showViewpoints=0&sortBy=bySubmissionDateDescending#R26TS0X19V6HJ4
[sicp]: https://mitpress.mit.edu/sicp/full-text/book/book.html
[sicp-review]: http://www.amazon.com/review/R403HR4VL71K8/ref=cm_cr_dp_title?ie=UTF8&ASIN=0262510871&channel=detail-glance&nodeID=283155&store=books

## Resources

### Articles

### Lectures

### Projects
