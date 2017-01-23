## WELCOME TO <br > THE IRON YARD

---

### Are you ready...

![inline](../images/shake.gif)

---

### Front End Engineering

![left,filtered](../images/internet.png)

---

### Instructor

* Brit Butler

![left 95%](../images/guide.jpg)

---

### Instructor

* Brit Butler

<br>

* I [blog][blog], I [tweet][tweet], I [code][code], I [smash][smash].
* And I get really excited about computers.

![left](../images/excited.jpg)

[blog]: http://blog.redlinernotes.com
[tweet]: https://twitter.com/king_cons
[code]: https://github.com/kingcons
[smash]: https://gfycat.com/DarkShamefulHoneybadger

---

### Instructor

Also my dogs are cute.

![left 35%](../images/puppers.jpg)

But enough about all that.

---

## What it takes to succeed

![left,filtered](../images/corgi.jpg)

---

## What it takes to succeed

- Determination
- Communication
- Experimentation

![left,filtered](../images/corgi.jpg)

---

![inline](../images/coffee.gif)

---

## 4 Rules to Live By

1. There is no perfect solution.
  * (There are *always* trade offs.)
2. Struggle often, [fail confidently][julia].
3. Don't compare yourself to others.
4. Understand why an idea __doesn't__ work.

[julia]: https://twitter.com/b0rk/status/726201450079113216

---

### What do I expect of you?

Attend lecture on time. Please. Ask. Questions.

Let me know when things don't make sense. (And maybe help me slow down.)

Turn in work when it's due, no exceptions.

Remember that you're here because computers are exciting and magical.

---

![inline](../images/magic.gif)

---

![inline](../images/magic.gif)

(You will feel like yelling soon. Remember this gif.)

---

### What can you expect of me?

I care about your experience, not just your education.

<br>

I will lecture to the best of my ability,
give as much feedback as I'm able,
and happily answer questions until I'm hoarse.

**Use Me!**

---

### How to ask technical questions

> `"It doesn't work" is very unhelpful.`

1. State what the code was supposed to do vs what it did.
2. Explain the code that was changed last.
3. Say something you tried to fix it.

---

## The Bounds of Helpfulness

*You are encouraged to help each other in person and in our slack channel!*

Helping understand why something won't work is awesome.

Telling someone how to make it work isn't.

---

### Lab Time

Work on homework and projects wherever you like.

I'll be grading and prepping in the teacher's lounge.

Come ask me questions!!! 😍

1. Do your own work. These are not group projects.
2. If you're not being challenged, come talk to me.

---

### Quizzes

We will have two quizzes a week, first thing in the morning.

They are not for a grade.

*Take them seriously!*

---

### Any Questions?

---

#### Goals for Week 1

* Semantic markup (HTML)
* Clean layout (CSS)
* Comfortable working on projects under version control (Git)
* Basic Command Line proficiency (shell)

---

#### Rough Overview

Today: HTML/CSS w/ [Codepen](https://codepen.io)
Tomorrow: Version Control with Git and Github
Wednesday: CSS Layout
Thursday: CSS Layout & Review

---

### HTML Basics

* HTML is about *structure* whereas CSS is about *appearance*.
* HTML is made up of many *elements* each with an open tag, content, and a close tag. (Except "void" elements.)
* These elements are *nested* to create web pages. The nesting is described similarly to inheritance.
* You should always choose which element to use based on what it *means*, not how it *looks*.

---

### HTML elements

* Every web page should have at least `<html>`, `<head>`, and `<body>` tags.
* `<head>` is information about the document while `<body>` is the content.

* `div`, `p`, `h1`, `ol`, `ul`, `li`
  * Some more recent elements: `nav`, `main`, `header`, `footer`
* `a`, `img`, `span`

---

### HTML Elements, Pt. 2

* Elements can have *attributes*. Attributes look like `foo="bar"`.
* What attributes do depends on the element but `class` and `id` are universal.

* The browser generally ignores whitespace.
* But take indentation seriously! Other people have to read your code.

---

### CSS Basics

* CSS is made up of rules, each with a *selector* and one or more *properties*.
* The *Selector* says which parts of the page are effected.
* The *Property* says what to change about its appearance.
* Elements have different properties to tweak. You don't have to know them all!

---

### CSS Selectors

3 types, ranked by priority:

`#id` - At most one and only used once!
`.class` - More than one and used as much as you like.
`tag` - Handy for defaults.

---

### CSS Selectors - Nested

You *cannot* nest entire rules.

You can nest selectors but don't get carried away.

`div p a` or `div > p > a`

If your selector is very long, there is a better way to organize your CSS.

---

### CSS properties

* `border`, `margin`, `padding`
* `color`, `background-color`
* `width`. `height`
* `font-style`, `font-size`, `font-weight`, `font-family`

---

### Boxes and Block vs Inline

* Everything on a web page is a box! (More Wed.)
  * Block elements expand to fill their parent unless restricted.
  * Inline elements flow "in line" with the text. Only take needed space.
  * For now, `<a>`, `<img>`, and `<span>` are the inline elements we care about. The rest are block-level!

---

### Developer Tools

The Chrome inspector is your best friend as you get comfortable with CSS.

You can hover over elements, see their Inherited traits, and toggle CSS rules
on and off or edit the rules live on the page.

---

### Homework

[Iron News][iron-news]: Recreate the page as closely as possible and submit the link to your codepen on TIYO.

[iron-news]: https://tiy-learn-content.s3.amazonaws.com/194319a7-Iron%20News.png
