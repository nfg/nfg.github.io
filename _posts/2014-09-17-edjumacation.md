---
layout: zigazigha
wide: 0
title: Edjumacation
date: September 17, 2014
---

Unsurprizingly, in my experience as a professional programmer I've used
very little of the stuff I learned as part of my computer science
degree. Which is good! I'm a strong believer that university is more
than career training, and even though I don't get to use much of it, I
was exposed to a lot of useful concepts in my education that I believe
make me a better programmer.

(Case in point: Timing. Discrete mathematics. Functional and logical
programming. Hell, even wiring a PDP-8 and writing bytecode gave me an
appreciation for how computers actually work.)

The one thing that my degree didn't cover is using other people's code.

For example, I took a course on data structures. It was pretty good. We
wrote stacks, queues, linked lists, and hashes from scratch. I have a
good understanding how those datastructures work.

As a developer, *you never actually write that code*.

Here's the Perl version:

~~~~~~

# List:
my @list;
push @list, 4;

# Queue:
my @queue;
push @queue, 27; # Adds to the end of the queue
my $head = shift @queue; # Pops off the head of the queue

# Hash
my %hash;
$hash{key} = $value;

~~~~~~

In C++, which is what we studied, there's the standard template library.
We did cover it briefly in one of my classes, but otherwise we ignored
it. The STL gives you highly optimized versions of all these data
structures. If you're writing C++ and avoiding the STL, you'd better
have a good reason.

It took me years of Perl development before I started taking a serious
look at CPAN. There's almost everything you could ever want there. At
one point I wrote an integration for a work system with Twilio, which
meant adding a dependency on [WWW::Twilio::API](https://metacpan.org/pod/WWW::Twilio::API)
and writing a package that maps our method calls to calls on an object.
Simple.

So ... yeah. I wish my education had a token class on, say, working with
Open Source libraries.
