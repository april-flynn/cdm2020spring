
# Midterm Reflections and Intro to Markup

**Work to have done**:

* Your final-for-now Visual Rhetorical Collage and Reflection
* Download and install the [Atom text editor](http://atom.io)

**Plan for the day**:

1. Midterm reflection (5-10 min)
2. Share and discuss reflections (5-10 min)
3. Introduction to markup languages (15-20 min)
4. Web-design unit overview and assignment (10 min)
5. CSS in 4 minutes (10-15 min)
6. Homework preview

<!-- NOTE FOR NEXT TIME: don't cut CSS in 4 minutes, and maybe even start with it? I ended up with 30 minutes left!!

Okay, here's my current proposal for next time:
1. midterm reflection (10 min)
2. share / discuss reflections (10 min)
3. CSS Zen Garden. (5 min) different ways visual representations can highlight / draw attention.
4. Reveal: every one of these sites uses the exact same underlying text. How? By telling the computer what _parts_ a thing has, you can separate out how to _display_ those parts.
Consider making a PowerPoint for the next bit:
5. Separate, but cross-related, languages have developed to handle the part-marking and the display: html and css. (other web languages, like php, javascript, ruby, and python, can dynamically generate or change the html and css; but html and css are the core of what gets shown on the screen.)
6. pre-fab (not inspector-based) examples (maybe in a codepen?) of html + css + output. structure of an html tag (maybe start with <a>, because it has attributes? use atom to show syntax highlighting, which makes it easier to see the parts. also note the open-tag close-tag structure is essentially like parentheses, and show https://xkcd.com/859/.)
7. div as a kind of layer-group: collect these things, treat them the same. container model.


-->

## Midterm reflection (8-10 min)

Welcome to the second half of the semester!

Over the weekend, you wrote a reflection on your visual-rhetorical project; now, take a few minutes to write a broader reflection on the semester as a whole.

In the letter I wrote for the course syllabus, I asked you to think about "the affordances of digital media: that is, what’s made possible by working with bits instead of paper, even when we are still working with words[...] How do the answers change, or shift, as we move beyond words into aural and visual modes?"

<div class="alert alert-success">

<p>Please spend some time revisiting these questions, in writing, now that you've digitally crafted both sounds and images into coherent compositions. For example:
  <ul>
    <li>What's <em>afforded</em> (i.e. enabled, foregrounded, suggested) differently in these different media?</li>
    <li>What strategies carry across them?</li>
    <li>How do they extend or complicate your usual composition strategies in writing?</li>
  </ul>
</p>

<p>If you want, you could also consider how the particular software we used differs from other tools you might have employed toward similar ends: what's facilitated, and what's frustrated, by these tools, and how did that change your approach?
</p>
</div>

**Take 8-10 minutes.** I won't collect these directly today, but you will use them to develop your pitch for a collaborative project, and as a snapshot of your progress to look back on (and possibly quote) in a final reflection for the end of the course.

EXT: Reflect on your goals for the course: given your goals and expectations when you began this class, what have you begun to learn? Combined with what you now know about our projects and scheduling patterns, what would you give yourself as a goal for the rest of the term?

EXT 2: What do you expect the affordances of a website will be?

## 2. Share and discuss reflections (5-10 min)

Any volunteers to share?

Anyone have a different response?


## 3. Introduction to Markup Languages (10-15 min)

### Begin with a breath
Our next unit takes us into the world of hypertext, a more interactive medium. Before we dive in deep, <strong>come with me to the <a href="http://www.csszengarden.com">CSS Zen Garden</a></strong>.

Some things to notice:

* Responsive design: the same page can change appearance to suit the "viewscreen" (especially as the width changes).

<!-- demo Verde Moderna (the default), -->

* The visual hierarchy holds here, too – including uses of negative space as a way of establishing rhythm.

<!-- Screen Filler, -->

* So, too, are we retaining the importance of color schemes for both coherence and contrast.

<!-- Mid-Century Modern -->

* This is all _exactly_ the same html.

<!-- Even A Robot Named Jimmy. -->

### Markup: separating content from display
How?

| HTML | HyperText Markup Language | content, groupings |
| CSS | Cascading Style Sheets | display / presentation |

What does that mean??

Per [the tutorial I'm assigning you for homework](https://internetingishard.com/html-and-css/introduction#html-css-and-javascript),
> HTML is for adding meaning to raw content by marking it up.
CSS is for formatting that marked up content.

<!-- Make the connection to their own markup on the Issue Queue: bold, italic, etc. Make the connection to -->

In other words:

| acronym | stands for | used for |
| --- | --- | --- |
| HTML | HyperText Markup Language | content, groupings |
| CSS | Cascading Style Sheets | display / presentation |

There are other languages that interact with these two, especially JavaScript, but also PHP and Python and Ruby: they can dynamically generate or change the HTML and CSS. And there are preprocessor languages that make it easier to generate HTML and CSS on your own: Markdown, the syntax you use in GitHub READMEs and forum posts, is essentially a shortcut form of HTML. But HTML and CSS are the core of what gets shown on the screen.

Let's take Markdown as an example:

* If you want to make something bold, you...
  - put `**asterisks**` on either side of it.
* If you want italics, you...
  - put `_underscore_` on either side (single asterisks will work, too).

<div class="alert alert-info">
The basic idea is that you need to signal where the <em>marked-up text</em> begins and ends.
</div>

The same is true in HTML, but it looks a little different:

| what we're marking | Markdown syntax | HTML syntax |
| --- | --- | --- |
| strong text | `**surrounding asterisks**` | `<strong>opening and closing tags</strong>` |
| emphasized text | `_surrounding underscore_` | `<em>opening and closing tags</em>` |

<div class="alert alert-info">
<p>Unlike in Markdown, opening and closing tags in HTML aren't exactly the same. But they're <em>almost</em> the same: a closing tag in HTML just adds the slash after the first angle bracket.</p>

<!-- <p>In general, every tag you open should close. You can nest a complete pair of tags inside another pair, but you can't close the outer pair before closing the inner pair.</p> -->
</div>

### A Demo
Some of this is easier to understand with a live demo! Let's head over to a [CodePen](https://codepen.io/benmiller314/pen/poJROZM?editors=1100) where we can get some instant results from adding new HTML and CSS rules.

## 4. Web-design unit overview and assignment (10 min)

As I explained in the syllabus, your third project is to **build a responsive website using basic html and css files** — as opposed to a site manager like WordPress or Wix — **along with any media assets you wish to embed.** In assigning this, I have two main goals for you:

1. to learn how to manage a composite project made up of multiple interlinking files, and
2. to explore the affordances of the web design stack as a medium, and especially its ability to _flexibly render content for multiple audiences or reading priorities_.

<div class="alert alert-success">
To read the full assignment – and fork a copy for yourself – go to <strong><a href="https://github.com/benmiller314/website-portfolio-2020spring#project-3-website-portfolio">github.com/benmiller314/website-portfolio-2020spring</a></strong>.
</div>

Let's read through this together.

<!-- Go through overview, constraints, deadlines. -->

## 5. "Web Design in 4 Minutes"... in 15 minutes
I expect this will take a bit more than four minutes, because I fully plan to interject, and I hope you will, too. But that's really what this is called:
[http://jgthms.com/web-design-in-4-minutes](http://jgthms.com/web-design-in-4-minutes/)



## Homework for Next Time

* **Do** as much of the [Interneting is Hard (but it doesn't have to be)](http://web.archive.org/web/20190213013947/https://internetingishard.com/html-and-css/) tutorial as you can – at least parts 1-4 (from "Introduction" through "Hello, CSS")
* **Show your work** by pushing your tutorial code to a repository
   - I've already created folders for parts 1-3 in the GH repo you just forked; clone it to your local computer, and you should be able to work in those folders and push.
   - Note that _you'll need to add your own folder_ for part 4, and thereafter.
* **Bring** headphones for sonic isolation, if you want: we'll have some studio time next class.
