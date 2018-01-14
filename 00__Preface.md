---
title: Preface
---

Some programming languages excel at turning coders into clockwork
oranges. By enforcing rigid rules
about how software must be structured and implemented, it is possible to
prevent a developer from doing anything dangerous. However, this comes at a
high cost, stifling the essential creativity and passion that separates the
masterful coder from the mediocre. Thankfully, Ruby is about as far from
this bleak reality as you can possibly imagine.

As a language, Ruby is designed to allow developers to express
themselves freely. It is meant to operate at the programmer’s level,
shifting the focus away from the machine and toward the problem at hand.
However, Ruby is highly malleable, and is nothing more than putty in the
hands of the developer. With a rigid mindset that tends to overcomplicate
things, you will produce complex Ruby code. With a light and unencumbered
outlook, you will produce simple and beautiful programs. In this book,
you’ll be able to clearly see the difference between the two, and find a
clear path laid out for you if you choose to seek the latter.

A dynamic, expressive, and open language does not fit well into strict
patterns of proper and improper use. However, this is not to say that
experienced Rubyists don’t agree on general strategies for attacking
problems. In fact, there is a great degree of commonality in the way that
professional Ruby developers approach a wide range of challenges. My goal in
this book has been to curate a collection of these techniques and practices
while preserving their original context. Much of the code discussed in this
book is either directly pulled from or inspired by popular open source Ruby
projects, which is an ideal way to keep in touch with the practical world
while still studying what it means to write better code.

If you were looking for a book of recipes to follow, or code to copy
and paste, you’ve come to the wrong place. This book is much more about how
to go about solving problems in Ruby than it is about the exact solution you
should use. Whenever someone asks the question “What is the right way to do
this in Ruby?”, the answer is always “It depends.” If you read this book,
you’ll learn how to go with the flow and come up with good solutions even as
everything keeps changing around you. At this point, Ruby stops being scary
and starts being beautiful, which is where all the fun begins.


## Audience

This book isn’t really written with the Ruby beginner in mind, and
certainly won’t be very useful to someone brand new to programming.
Instead, I assume a decent technical grasp of the Ruby language and at
least some practical experience in developing software with it. However,
you needn’t be some guru in order to benefit from this book. The most
important thing is that you actually care about improving the way you
write Ruby code.

As long as you have at least an intermediate level of experience,
reading through the book should be enjoyable. You’ll want to have your
favorite reference book handy to look things up as needed. Either
_The Ruby Programming Language_ by David Flanagan and Yukihiro
Matsumoto (O’Reilly) or _Programming Ruby_, Third Edition, by Dave Thomas (Pragmatic Bookshelf) should do the trick.

It is also important to note that this is a Ruby 1.9 book. It makes
no attempt to provide notes on the differences between Ruby 1.8 and 1.9
except for in a brief appendix designed specifically for that purpose.
Although many of the code samples will likely work with little or no
modifications for earlier versions of Ruby, Ruby 1.9 is the way forward,
and I have chosen to focus on it exclusively in this book. Although the
book may still be useful to those maintaining legacy code, it is
admittedly geared more toward the forward-looking crowd.


## About This Book

This book is designed to be read by chapter, but the chapters are
not in any particular order. The book is split into two parts, with eight
chapters forming its core and three appendixes included as supplementary
material. Despite the fact that you can read these topics in any order
that you’d like, it is recommended that you read the entire book. Lots of
the topics play off of each other, and reading through them all will give
you a solid base in some powerful Ruby techniques and practices.

Each of the core chapters starts off with a case study that is meant
to serve as an introduction to the topic it covers. Every case study is
based on code from real Ruby projects, and is meant to provide a practical
experience in code reading and exploration. The best way to work through
these examples is to imagine that you are working through a foreign
codebase with a fellow developer, discussing the interesting bits as you
come across them. In this way, you’ll be able to highlight the exciting
parts without getting bogged down on every last detail. You are not
expected to understand every line of code in the case studies in this
book, but instead should just treat them as useful exercises that prepare you for studying the
underlying topics.

Once you’ve worked your way through the case study, the remainder of
each core chapter fills in details on specific subtopics related to the
overall theme. These tend to mix real code in with some abstract examples,
preferring the former but falling back to the latter when necessary to
keep things easy to understand. Some code samples will be easy to run as
they are listed; others might only be used for illustration purposes. This
should be easy enough to figure out as you go along based on the context.
I wholeheartedly recommend running examples when they’re relevant and
stopping frequently to conduct your own explorations as you read this
book. The sections are kept somewhat independent of one another to make it
easy for you to take as many breaks as you need, and each wraps up with
some basic reminders to refresh your memory of what you just read.

Although the core chapters are the essential part of this book, the
appendixes should not be overlooked. You’ll notice that they’re slightly
different in form and content from the main discussion, but maintain the
overall feel of the book. You’ll get the most out of them if you read them
after you’ve completed the main part of the book, as they tend to assume
that you’re already familiar with the rest of the content.

That’s pretty much all there is to it. The key things to remember
are that you aren’t going to get much out of this book by skimming for
content on a first read, and that you should keep your brain engaged while
you work your way through the content. If you read this entire book
without writing any code in the process, you’ll probably rob yourself of
the full experience. So pop open your favorite editor, start with the
topic from the chapter listing that interests you most, and get
hacking!


## Acknowledgments

Over the course of writing _Ruby Best Practices_, I was thoroughly supported by my friends, family,
and fellow hackers. I want to thank each and every one of the folks who’ve
helped out with this book, because it would not exist without them.

This book did not have a typical technical review process, but
instead was supported by an excellent advisory board whose members
participated in group discussion and the occasional review as each chapter
was released. These folks not only helped catch technical errors, but
helped me sketch out the overall vision for how the book should come
together as well. Participants included James Britt, Francis Hwang, Hart
Larew, Chris Lee, Jeremy McAnally, and Aaron Patterson.

Rounding out the group was the best pair of guiding mentors I could
hope for, Brad Ediger and James Edward Gray II. Both have published Ruby
books, and have worked with me extensively on a number of Ruby projects.
James and Brad were both instrumental in producing this book, and to my
career as a software developer in general. I have learned a ton from each
of them, and thanks to their help with _Ruby Best Practices_,
I can now pass their knowledge on to you.

Much of the source code in this book comes from the open source Ruby
community. Although I talk about my own projects (Prawn and Ruport) a lot,
most of the code I show is actually from other contributors or at least
originated from good ideas that came up in mailing list discussions,
feature requests, and so on. In addition to these two projects, I also
have benefited from studying a whole slew of other gems, including but not
limited to: activesupport, builder, camping, faker, flexmock, gibberish,
haml, highline, lazy, nokogiri, pdf-writer, and rspec. Great thanks go out
to all of the developers of these projects, whom I’ve tried to acknowledge
directly wherever I can throughout the text.

Of course, without Yukihiro Matsumoto (Matz), we wouldn’t have Ruby
in the first place. After writing this book, I am more impressed than ever
by the language he has designed. If I’m lucky, this book will help show
people just how beautiful Ruby can be.

Producing the technical content for this work was daunting, but only
part of the overall picture. My editor, Mike Loukides, and the entire
O’Reilly production team have made publishing this book a very comfortable
experience. After overcoming major fears about the hurdles of working with
a mainstream publisher, I’ve found the folks at O’Reilly to be helpful,
accommodating, and supportive. It is especially nice that this book will
become an open community resource less than a year after it prints. This
measure is one I hope to see other technical book publishers adopt, and
one I’m very thankful that O’Reilly was open to.

Finally, I need to thank the folks who’ve helped me keep my sanity
while working on this huge project. My future wife, Jia Wu, has been
amazingly supportive of me, and helped make sure that I occasionally ate
and slept while working on this book. On the weekends, we’d usually escape
for an bit and spend time with my close friends and family. Though they
didn’t have anything to do with the project itself, without Pete, Paul,
Mom, Dad, and Vinny, I doubt you’d be reading this book right now. Thanks
to all of you, even if you’ll never need to read this book.

So many people helped out in countless different ways, that I’m sure
I’ve missed someone important while compiling this list. To make sure
these folks get their well-deserved credit, please keep an eye on the
acknowledgments page at [`rubybestpractices.com`](http://rubybestpractices.com)
and let me know if there is someone who needs to be added to the list. But
for now, if I’ve failed to list you here, thank you and please know that
I’ve not forgotten what you’ve done to help me.
