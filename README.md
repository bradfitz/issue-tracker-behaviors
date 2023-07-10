# Public Issue Tracker Behaviors

I've been involved in FOSS communities for over 25 years now. I've
used a handful of different bug trackers and worked on and created a
ton projects, often acting as the bug triage person.

I've also worked inside companies with private bug trackers.

Private bug trackers and public bug trackers are vastly
different. Public bug trackers are full of the best and the worst of
the internet. This page documents some of the most commonly seen bad
behavior on public issue trackers. (and why many people prefer private bug
trackers)

Pull requests or issues welcome to add more. I surely forgot a bunch.

# Behaviors

## Me too, plus one

User shows up adding no new information, just:

* "+1"
* "me too"
* "i also see this"

No version numbers, no logs, nothing.

User has not learned to use the emoji reactions yet. (Please learn.)

## Subscribing via comments

* "just leaving a comment to watch this bug"

And you just spammed everybody else watching this bug.

There's a "subscribe" button to get notified over on the right. Push
that instead.

## Back from the dead

User comments on ancient closed issue saying they're "also seeing
this", without saying what "this" is. They probably found one common
symptom ("it doesn't work") and decided that an Android crash from 3
years ago is the same as their Windows issues, because both resulted
in it "not working".

## Any update?

* "Any update?"
* "Any news on this?"

If there was an update we would've posted an update. We were just
waiting for the forty-seventh person to ask! But now that you're here,
here's an update!

(if it's been a year, sure. But we don't need somebody pinging the bug
for updates daily or weekly.)


## Any workaround?

User asks for a "workaround" on a bug that clearly has no
workaround. Maybe it's a feature request or a crash that's affecting
everybody, but the user wants a "workaround".

## The negger

* "I can't believe you don't have this yet. That's ridiculous. All
  your competitors can do X, so I guess I'll just have to go use
  something else."

## The duper

Files duplicate bug without doing any search ahead of time to see if
the bug was already filed. I don't expect people to be perfect and
find a possible dup bug every time, but I expect you to try for 10
seconds first.

## The template ignorer

The bug template asks a bunch of questions.

The person filing the bug answers none of them.

But, uh, "it doesn't work".

## XY Problem

See https://xyproblem.info/

Somebody files a bug asking for X, omitting what their real problem
is, but thinking that X would help with their problem. Usually they
don't understand the problem enough and are asking for the wrong
thing.

Start with your problem.

## Just add an option!

The project doesn't want a hundred configuration knobs. That's a
usability and testing disaster: users need to learn all the options
and how they interact, and project maintainers need to set up tests to
test every combination of them.

So the project instead tries to do the right thing automatically,
configuration free.

But users inevitably don't want to wait for the right fix and instead say:

* "Just add an option!"

Just.

## The lazy pull request

Somebody opens a pull request adding a feature or bug fix, but in
doing so ...

* implements an unwanted feature with no discussion
* provides no description in the pull request
* breaks existing functionality that doesn't apply to them
* breaks test cases and does not address them
* fails to provide coverage in new test cases
* does not update documentation
* expects maintainers to "take it from here"

## The locals find each other

The project is primarily in one language (inevitably English): its
website, its docs, its bug tracker are all in English.

A user files a bug in English.

Some comments go by.

Eventually two of users commenting in the bug discover that they both
speak some non-English language and switch all the dialogue in that
bug to that language. It's spread in forums by users speaking that
language and more people speaking that language start participating.

Now the original people who filed the bug (in English) have to do the
copy/paste translation because the issue tracker doesn't have built-in
translation. (It's 2023. They should. But maybe they don't want to pay
for it.)

This is regrettable (people should ideally be able to use their
preferred language and participate), but it's really annoying for
project maintainers when their issues are taken over and had the
language changed on them. Better tooling by issue trackers & browsers
would help here.

## Wants the opposite.

The project says "This is **foo**, specifically for **bar**. It
specifically does not do **baz** because the following reasons."

User shows up in the issue tracker: "Hey, I really like **foo**! How
about you add **baz**? It would be great!"

## The cookie licker

* "Can I work on this?"

... then proceeds to never work on it.

(courtesy @jakebailey)

## The At-er

`@`-mentions a bunch of project contributors, hoping to get more
attention to their issue.

(BTW, if you ever need attention on an issue, be sure to mention
@jakebailey who suggested this item)

## The Blaster

User files a bug,

... but also emails the user list, the core developer list, posts to
Twitter, posts to Reddit, asks on Stackoverflow, emails support,
emails sales, privately DMs some core developers ....

_STOP._
