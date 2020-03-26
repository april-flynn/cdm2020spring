---
layout: bottomnav
---

# Web Unit Workshop

**Work to have done**: a solid attempt at a complete website, ideally meeting baseline criteria. Rough edges are still welcome.

**Plan for the day**:

1. Workflow tweaks for websites and for #CovidCampus (5-10 min)
2. Evaluation reminder: our shared criteria (5 min)
3. Peer review workshop (3 times 10-12 min)
4. Evaluation revisited (10 min)
5. HW preview
6. EXT: Studio



## Workflow Tweaks

### We can't trade cards, so we'll trade clones

The most obvious change is that you can't very well load your website files on your own computer and switch seats with a neighbor. Instead, I'm putting the 19 of you into four groups: within your group, you'll clone three repositories, and leave feedback for the authors _on GitHub_.

How? Just (1) click through to the history of commits; (2) click on the _commit hash_, the set of random-seeming numbers and letters almost at the end of the top row (i.e., for the most recent commit); and (3) scroll to the bottom of the _diff view_ that appears. You'll see a comment box there:

<figure><img src="../assets/img/github--cmment-on-commit.gif" alt="screencast of the three steps just described"/></figure>

<div class="alert alert-info">
To make this process easier, you should probably indicate in your README.md file where to find the main files for your own project: what folder are they in, if not the docs folder?

Relatedly, if you're using Jekyll or something like it, please give instructions on how to load your most current rendered website: e.g. a link to the published GitHub Pages site. Your partners will probably want to View Source on the final rendered page.
</div>

### Still describe -> evaluate -> suggest... but describe twice

As you remember from the sound and image units, I encourage you to **always start by describing** the piece, before judging what's good about it, so the creator knows whether you're on the same page. (Which is itself important feedback: _is my message getting through?_)

<div class="alert alert-white">
   <div class="alert alert-info">
      For this unit, in which display is a separate – and often challenging – concern, I'm going to ask you to use a <em>two-step description</em>.
   </div>

   <ol>
      <li><strong>First look at the HTML files, and say back what you see there.</strong> What seem to be the major content areas? What's given top-level focus? (e.g. what kind of things are getting their own pages, or what's at &lt;h1&gt; status within a page?) What's next in the hierarchy?</li>
      <li>Once you've done that, <strong>turn to the browser and repeat the process for the display.</strong> What's given visual weight? What falls "above the fold"? Where are you invited to go next?</li>
   </ol>
</div>

From there, you can continue on to _evaluation_, using the shared criteria we developed before the break – and also the correspondence between the hierarchy you observed in the HTML and the hierarchy you observed in the rendered site.

NB: This is still a form of description: it's not about "good" or "bad" in the abstract but about where it meets or misses the shared or stated goals.

Finally, in your <em>suggestions</em>, some revision possibility that you think might help take the project to the next level: assume this is a work in progress. Given the goals, the focus, the criteria, what might be next? <!-- Pose this as a suggestion, not a command: and _interpret_ these as suggestions, not commands. -->

<!--
I have here to return to you the index cards from the visual unit – not from the comments you *received*, but the comments you *gave*. Read them over. **Were you doing describe/evaluate/suggest?** If so, be proud! See if you can do it again in a new sensory mode. If not, strive to level up today: train your attention to see before judging. -->

## 2. Evaluation reminder: our criteria (5 min)
We set up a few shared goals and constraints [bit.ly/cdm2020spring-criteria](http://bit.ly/cdm2020spring-criteria#heading=h.z8d1igk08a86) to meet the baseline requirements. Let's try to help everyone get at least to there!

<aside>
<strong>Baseline criteria</strong>
For a minimum grade of B, all projects for this unit must:

<ul>
  <li>Use arrangement, size, color, visual rhythm, and/or contrast to focus viewers' attention.</li>
  <li>Include at least three navigable html locations</li>
  <li>Have a clear mode of navigation among the locations</li>
  <li>Include at least one sitewide css stylesheet (i.e. an organized theme)</li>
  <li>Include at least one ethically useable image, with alt text</li>
  <li>Successfully display in a local web browser</li>
  <li>Argue in reflection why you did what you did</li>
</ul>

<strong>Aspirational inspirations</strong>
To target (but not guarantee) a grade above a B, the best projects for this unit may...

<ul>
  <li>Load site publicly over the internet (e.g. with GitHub Pages)</li>
  <li>Use Flexbox or Grid layout</li>
  <li>Use responsive design to dynamically resize elements based on screen width</li>
  <li>Use advanced navigation, like drop-down menus, tabs, or a sticky nav bar</li>
  <li>Use Jekyll to theme your site with minimal repetition of code (see Resources page)</li>
  <li>Optimize image filetypes (.jpg, .png, .svg, .gif), resolutions, and filesizes for the web</li>
  <li>Add interactivity via JavaScript (e.g. on-click events) or other ways to receive information from site visitors (e.g. mailto: links, forms)</li>
  <li>Animate HTML elements via JavaScript (e.g. image carousel) or CSS (e.g. rotation, :hover events)</li>
  <li>Include a loadable alternate stylesheet / theme (e.g. dark mode)</li>
  <li>Make or modify your own graphics using GIMP, photography, etc</li>
</ul>
</aside>

## 3. Peer Review Workshop (3 times 10-12 min)

Let's do this!

### Timing note

<div class="alert alert-white">
We're doing this asynchronously now, so I can't keep track of your time... but I can recommend <a href="https://chrome.google.com/webstore/detail/talking-timer-custom-spea/cbbmoeglgokhkbnnfpoeciheapicdphm?hl=en">a Chrome app that will simulate the effect</a>:

<figure>
<img src="../assets/img/custom-talking-timer.png" alt="Talking Timer settings with custom text such as 'it\'s been 25 minutes. Stretch break!' and '15 minutes left. Are you saving and committing?'" />
<figcaption>Custom Speaking Timer. After installing this in Chrome, you can run it standalone from the desktop.</figcaption>
</figure>

I'm sure something similar exists if you're not a Chrome user; I found this one pretty quickly on Google.

**We usually spend about 10-12 minutes on each rotation.** I recommend timing yourself to make the amount of feedback roughly equivalent.
</div>

### Detailed instructions for workshop-at-a-distance

1. Go to your first partner's website, and use the "clone or download" button, probably with the "open in desktop" option. <figure><img src="../assets/img/github-clone-or-download-2.png" alt="Clone or download pop-up; also includes the URL to use with the command line." /></figure>

2. In GitHub Desktop, choose the "Open in Atom" option if available, or else use View in Finder (Mac) / View in Explorer (PC) to find the files you just downloaded, and open them in your text editor.<figure><img src="../assets/img/github-desktop--open-in-atom.png" alt="GitHub Desktop with Open in Atom and Show in Finder buttons highlighted"/></figure>

3. Start by viewing the HTML in the docs folder (or, if the main files aren't there, look for something that signals it's the real project and not an exercise). Do the first part of **Describe**: What seem to be the major content areas? What's given top-level focus? (e.g. what kind of things are getting their own pages, or what's at &lt;h1&gt; status within a page?) What's next in the hierarchy?
    - If you're seeing a lot of curly brackets, or there's a subfolder called "templates", this may be a Jekyll site, which means the HTML will be distributed in a bunch of places. Hopefully there are instructions or a link to the fully-rendered site; once there, you can right-click to View Source, and see the composite HTML that way.

4. Next up, load the site in your browser (Firefox is best for inspecting the CSS of individual elements, should you want to; Chrome is also pretty good), and **describe again**: What's given visual weight? What falls "above the fold"? Where are you invited to go next?

5. Now continue as usual: **evaluate** the site relative to the shared set of criteria, and **suggest** changes that you think would take it to baseline and/or above.

6. Finally, make sure you **post** all these comments – in language you'd be comfortable sharing publicly – on the latest commit, as shown at the beginning of this lesson plan.

7. Repeat the steps above for your next two partners' repos. On subsequent loops, note that **after** viewing the project first, you may also want to read and/or refer to the previous comments.




## 4. Evaluation revisited (10 min)
Head back to your seats and take a minute to read **and photograph** the notes you've received. (Make sure your photos are legible; I'll be collecting the cards at the end of class.)

Based on your viewing, would anyone like to propose changes to the baseline criteria, or new aspirational goals to consider?


# Homework for Next Time
* Even as we zoom in toward the unit finale (again), I want to keep one eye open toward the bigger picture (again!). At this point, we have a number of [great ideas](https://github.com/benmiller314/cdm2019fall/issues/6) for [group projects](https://github.com/benmiller314/cdm2019fall/issues/10):
  - Collaborative soundscape narrative / podcast / radio show, perhaps traversing existing soundscape narratives
  - Art of Foley (adding sounds to video - maybe one of [these](https://www.google.com/search?q=short+videos+no+sound&tbm=vid&sxsrf=ACYBGNTjlnYAR93lkuo0q2cwvLs06VgiNw:1572973957460&source=lnt&tbs=dur:s&sa=X&ved=0ahUKEwiyn-bPyNPlAhUOyFkKHZIRDisQpwUIIQ&biw=1440&bih=798&dpr=1))
  - "Reverse-Foley" (visually animating, or filming, a soundscape)
  - Digital stop-motion / flip-book animation ([several tools](https://www.freelancer.com/articles/graphic-design/best-free-animation-software) available)
  - Animated or text-based game (perhaps using [Twine](http://twinery.org/))
  - Visual programming (probably in [Scratch](https://scratch.mit.edu/about))
  - UI/UX design in Adobe Suite (talk to [Margaret](mailto:mpalko@pitt.edu) about this one!)

* Skim through any links above that seem intriguing, and if something strikes you, **[post a proposal]({{site.github.issues_url}}/13) to try to recruit partners**. As before, there is no minimum length for these posts.

* Next class will be a web designers' studio: **optionally bring headphones for [sonic isolation](http://noisli.com)**, and whatever else you need to work towards finalizing your website portfolio.
  - The final draft is due at the end of the day on Sunday, and a reflection by class-time on Tuesday; see the [prompt](https://github.com/benmiller314/webste-portfolio-2019fall#project-3-website-portfolio) for further details.



## EXT:
If any time remains, go ahead and get started on those revisions!
