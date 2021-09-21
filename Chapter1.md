---
marp: true
theme: gaia
class:
  - lead
  - invert
---
<!-- paginate: true -->


# Some thoughts on a better way to communicate

Adrian

---

# What are our constraints?
* We need to create written content
* Technical in nature
* Consumed by many different nationalities, with many different levels of experience
* Need to be able to present or show the content to someone live  as well as publish is for later consumption
![bg right:33%](./graphics/noun_Chain_1444025.svg)

<!-- HTML comment recognizes as a presenter note per pages. -->
<!-- You may place multiple comments in a single page. -->
---


# Where are we today?
* Single desktop publishing systems (Word, Powerpoint, ETC) or NGPS
* Saved in both a shared drive and GitHub 
* Graphics created in both the publishing platform and in 3rd party app (Inkscape)
* Shared review though 3rd party app / PDF 

![bg:fit](./graphics/noun_emotion_1982929.svg)

---

# Benefits of NGPS
* Identical formatting
* Pretty good workflow
* Works well in GIT
* Easy final build

---


# The challenges with NGPS
* Difficult to onboard
* Small number of people left to support
* Difficult to collaborate with (steep learning curve)
* No live preview
* Requires local install
* Slow build time
* Stuck to 4:3 aspect ration
* Difficult conversion to video
* No editor support (spell check, grammar check, highlighting)

---

# Benefits of PowerPoint + Word
* Universal - Easy collab
* Easy onboard
* Encourages collab from outside-team
* We can reuse company content
* Future proof (ish)
* Integrations

---


# Benefits of PowerPoint + Word
* Formatting hell 
* Not built for Git -  No Git workflow 
* Tools cost
* No CMS
* Low maturity
* More time spent on tooling than development
* No automation
* Focused on PDF

---

# What are our goals?
- Platform to create communications quickly and simply
- Modern
- Easy to collaborate
- Easy to build
- Easy to update + report bugs
- Fits into a workflow
- Reliable + Reproducible
- Automate the boring stuff
- Easy to learn - Content not tooling


![bg 90% left:20%](./graphics/noun_goal_1715960.svg)

---

# Who should we be looking at?
* Tech comms has been through all of this before
  * Many large companies opt for an all in Content Management System (CMS) with languages like DITA and DocBook
  * The main selling point of these is content reuse
  * These are very expensive


---

# What can this do?

## Block quotes 
> Block quote
> More block quote

*   A list item with a code block:

        <code goes here>

Use the `printf()` function.

---


# What can this do?
*Italicized text*

This text is ***really important bold + italic***

_single underscores_

**double asterisks**

__double underscores__

---


# Headers

# H1
## H2
### H3
#### H4



---



# Syntax highlight

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

---

# Tables

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


---

# Strikethrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

# Emojii
:+1: This PR looks great - it's ready to merge 	:smile: 	:ireland:! 

---

# Background Images
![bg left:33%](https://picsum.photos/720?image=27)

---

![bg right](https://picsum.photos/720?image=3)
![bg](https://picsum.photos/720?image=20)

# Split + Multiple BGs

The space of a slide content will shrink to the left side.





=======
# Slide 4
* this is a bullet
![bg right](https://user-images.githubusercontent.com/14011726/94132137-7d4fc100-fe7c-11ea-8512-69f90cb65e48.gif)

---


