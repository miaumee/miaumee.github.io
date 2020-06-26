---
layout: default
title: The World of Mathematics
---

# The World of Mathematics

Welcome! This site is an attempt to feature some of my favorite math resources on the Web, so without further ado, let's get started!

- [**Mathematics — Wikipedia**](#): This is the de-facto portal of mathematics on the Web, and features a story of mathematics that is incredibly fascinating. When mathemaics reads like a novel, you know that it got to be good. And this happens to be one of them.
- [**The Glossary of Higher Mathematical Jargon**](https://mathvault.ca/math-glossary/): When you want to learn some serious math but have no clue where to start, what do you do? Well, you start with its language of course — more specifically the jargon of mathematics. When it comes to these words, this guide is definitely not in the lacking. If anything, it will take you on a ride from "abstract nonsense" all the way to "without loss of generality".
- [**Introduction to Higher Mathematics**](https://www.youtube.com/playlist?list=PLZzHxk_TPOStgPtqRZ6KzmkUQBQ8TSWVX): When it comes to math beyond the K-12 level, videos are often not the type of modality. But alas, there are times where math videos can strike gold, and this is one of them. Organized as a 19-part series, this resource will venture into an abstract world which you might or might not have seen. From proof, logic, set theory, relation to number theory, modular arithmetic, topology and ring theory, it seems that there's enough of mathematical goodness for just about everyone.

All right folks. These resources should keep you busy for a while already. So until next time and may Math be your lord and shepherd many years down the road!
{: .text-danger}

## Text Ornament

**Bold text** makes *emphasize* or ~~deleted~~ text to shame. <u>Underline</u> using `<u>`, <mark>highlight</mark> with `<mark>` and <small>make texts smaller</small> with `<small>`. [link](#) works as usual.

## Text Alignment

This paragraph is centered using `.text-center` class.
{: .text-center}

This paragraph is aligned to the right using `.text-right` class.
{: .text-right}

## Heading 2

### Heading 3

<h3>
  Fancy display heading
  <small class="text-muted">With faded secondary text</small>
</h3>

#### Heading 4

##### Heading 5

###### Heading 6

<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>

## Columns

### 3 Columns

<div class="container">
  <div class="row">
    <div class="col-sm"> <strong>Column 1</strong> </div>
    <div class="col-sm"> Column 2</div>
    <div class="col-sm"> Column 3</div>
  </div>
</div>

### Any columns (`.container` > `.row` > `.col`)

<div class="container">
  <div class="row">
    <div class="col"> Column 1 </div>
    <div class="col"> Column 2 (Width is auto-adjusted) </div>
    <div class="col"> Column 3</div>
  </div>
</div>

### Specify 4 columns with `.row-cols-4`

<div class="container">
  <div class="row row-cols-4">
    <div class="col"> Column 1 </div>
    <div class="col"> Column 2 (Width is auto-adjusted) </div>
    <div class="col"> Column 3</div>
    <div class="col"> Column 4</div>
    <div class="col"> Column 1 </div>
    <div class="col"> Column 2 (Width is auto-adjusted) </div>
    <div class="col"> Column 3</div>
    <div class="col"> Column 4</div>
  </div>
</div>

## Lists

* A first item
* A second item
* Again a third item
  *  A sub-item
  * Another one
* Test to see if unindent alignment is legit
* And... it seems that it really is!
  
1. Having fun with ordered list
1. Another list item
1. Yet another one
   1. A nested item (three spaces to indent)
   1. Just checking to see if alignment is correct
1. Testing to see if unindent alignment is good
1. And everything seems good!

Cat
: A feline animal (with `: `, item separated by a blank line)

Dog
: A canine animal

## Preformatted Text

```
.example-element {
  margin-bottom: 1rem;
}
```

## Blockquotes

> A picture is worth a thousand words.
> But I ain't seen anything yet...

> This is going to be from a separate paragraph with `.blockquote` class.
{: .blockquote}

## Colorboxes

The class `.alert` is needed for all alerts.
{: .alert}

This is `.alert-primary`
{: .alert .alert-primary}

This is `.alert-secondary`
{: .alert .alert-secondary}

This is `.alert-success`
{: .alert .alert-success}

This is `.alert-warning`
{: .alert .alert-warning}

This is `.alert-danger`
{: .alert .alert-danger}

This is `.alert-info`
{: .alert .alert-info}

This is `.alert-light`
{: .alert .alert-light}

This is `.alert-dark`
{: .alert .alert-dark}

### `.lead` class

<p class="lead">
  Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus.
</p>

## Badges

All badges require `.badge` class.

{: .badge .badge-secondary}
New 

{: .badge .badge-success}
Success!

Badge as a pill using `.badge-pill` class

Warning!
{: .badge .badge-pill .badge-warning}

### Badge as links

[`.badge-primary`](){: .badge .badge-primary} [`.badge-secondary`](){: .badge .badge-secondary}
[`.badge-success`](#){: .badge .badge-success} [`.badge-warning`](#){: .badge .badge-warning} [`.badge-danger`](#){: .badge .badge-danger} [`.badge-info`](#){: .badge .badge-info} [`.badge-light`](#){: .badge .badge-light} [`.badge-dark`](#){: .badge .badge-dark}  

### Buttons

All buttons require `.btn` class. Otherwise similar to badges

[.btn-primary](#){: .btn .btn-primary} [.btn-secondary](#){: .btn .btn-secondary} [.btn-outline-success](#){: .btn .btn-outline-success} [.btn-lg](#){: .btn .btn-warning .btn-lg} [.btn-sm](#){: .btn .btn-danger .btn-sm} [.btn-block](#){: .btn .btn-block .btn-info} 

## Button Groups

Wrap buttons within a `div` with `.btn-group` class

<div class="btn-group" role="group" aria-label="Some Menu">
  <button class="btn btn-success"> Menu 1</button>
  <button class="btn btn-success"> Menu 2</button>
  <button class="btn btn-primary"> Menu 3</button>
</div>

<div class="btn-group" role="group" aria-label="Button group with nested dropdown">
  <button type="button" class="btn btn-primary">1</button>
  <button type="button" class="btn btn-secondary">2</button>

  <div class="btn-group" role="group">
    <button id="btnGroupDrop1" type="button" class="btn btn-warning dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
      Dropdown
    </button>
    <div class="dropdown-menu" aria-labelledby="btnGroupDrop1">
      <a class="dropdown-item" href="#">Dropdown link</a>
      <a class="dropdown-item" href="#">Dropdown link</a>
    </div>
  </div>
</div>

With `.btn-group-lg` and `.btn-group-sm`

<div class="btn-group btn-group-lg" role="group" aria-label="Some Menu">
  <button class="btn btn-success"> Menu 1</button>
  <button class="btn btn-success"> Menu 2</button>
  <button class="btn btn-primary"> Menu 3</button>
</div> 

<div class="btn-group btn-group-sm" role="group" aria-label="Some Menu">
  <button class="btn btn-success"> Menu 1</button>
  <button class="btn btn-success"> Menu 2</button>
  <button class="btn btn-primary"> Menu 3</button>
</div>

With `.btn-group-vertical`

<div class="btn-group btn-group-vertical" role="group" aria-label="Button group with nested dropdown">
  <button type="button" class="btn btn-primary">1</button>
  <button type="button" class="btn btn-secondary">2</button>

  <div class="btn-group" role="group">
    <button id="btnGroupDrop1" type="button" class="btn btn-warning dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
      Dropdown
    </button>
    <div class="dropdown-menu" aria-labelledby="btnGroupDrop1">
      <a class="dropdown-item" href="#">Dropdown link</a>
      <a class="dropdown-item" href="#">Dropdown link</a>
    </div>
  </div>
</div>

## Cards

- Outermost div requires `.card` class
- Image with class `.card-img-top`
- Card body div needs class `.card-body` for padding
- Title with `.card-title` class
- Subtitle with `.card-subtitle` class
- Text with `.card-text` class
- Use `.text-center` or `.text-right` for alternate alignments

<div class="card" style="width:33%;">
  <img src="images/BLM.jpg" class="card-img-top" />
  <div class="card-body">
  <h5 class="card-title">Newest iPhone revealed</h5>
  <h6 class="card-subtitle">A unique experience</h6>
  <p class="card-text">Discover what a titanium-grade, bullet-proof telecommunication device is made of.</p>
  <button class="btn btn-primary">Learn More</button>
  </div>
</div>

<div class="card text-center" style="width:33%;">
  <img src="images/BLM.jpg" class="card-img-top" />
  <div class="card-body">
  <h5 class="card-title">Newest iPhone revealed</h5>
  <h6 class="card-subtitle">A unique experience</h6>
  <p class="card-text">Discover what a titanium-grade, bullet-proof telecommunication device is made of.</p>
  <button class="btn btn-primary">Learn More</button>
  </div>
</div>
<div class="card text-right" style="width:33%;">
  <img src="images/BLM.jpg" class="card-img-top" />
  <div class="card-body">
  <h5 class="card-title">Newest iPhone revealed</h5>
  <h6 class="card-subtitle">A unique experience</h6>
  <p class="card-text">Discover what a titanium-grade, bullet-proof telecommunication device is made of.</p>
  <button class="btn btn-primary">Learn More</button>
  </div>
</div>

## Images

![BLM](/images/BLM.jpg)

With `.img-fluid` class:

![BLM](/images/BLM.jpg){: .img-fluid}

### Full-fledged figures

<figure class="figure">
  <img src="/images/BLM.jpg" class="figure-img img-fluid rounded">
  <figcaption class="figure-caption text-center">Mathematician's wordplay.</figcaption>
</figure>

## Toggle

- Button requires `data-toggle="collapse"` linking to an anchor
- An answer div block with class `collapse` and anchor id

<p>
  <a class="btn btn-success" data-toggle="collapse" href="#proof">Show the Proof</a>
</p>
<div class="collapse" id="proof">
  <div class="card card-body">
    Here is the answer! Bingo!
</div>

## Tables

Need `.table` for all tables. `.table-dark` to invert colors. 

Type-A | Type-B | Type-C | Type-D
------ | ------ | ------ | ------
John | Mary | Abraham | Becky
{: .table}

Type-A | Type-B | Type-C | Type-D
------ | ------ | ------ | ------
John | Mary | Abraham | Becky
{: .table .table-dark}

Using `.thead-light` and `.thead-dark`

Type-A | Type-B | Type-C | Type-D
------ | ------ | ------ | ------
John | Mary | Abraham | Becky
{: .table .thead-light}

Type-A | Type-B | Type-C | Type-D
------ | ------ | ------ | ------
John | Mary | Abraham | Becky
{: .table .thead-dark}

With `.table-striped`

Type-A | Type-B | Type-C | Type-D
------ | ------ | ------ | ------
John | Mary | Abraham | Becky
{: .table .table-striped}

With `.table-hover`

Type-A | Type-B | Type-C | Type-D
------ | ------ | ------ | ------
John | Mary | Abraham | Becky
{: .table .table-hover}

Small table with `.table-sm`

Type-A | Type-B | Type-C | Type-D
------ | ------ | ------ | ------
John | Mary | Abraham | Becky
{: .table .table-sm}

Using `.table-responsive`

Type-A | Type-B | Type-C | Type-D | Type-E | Type-F | Type-G | Type-H
------ | ------ | ------ | ------ | ------ | ------ | ------ | ------
John | Mary | Abraham | Becky | Carla | Duncan | Ernie | Fisher
{: .table .table-responsive}

<form>
  <fieldset>
    <legend>A Very Cool Form</legend>
    
    <p><label>Name</label>
    <input type="text" placeholder="John"></p>
    
    <p><label>Email Address</label>
    <input type="text" placeholder="abc@def.com"></p>
    
    <p><label>Date</label>
    <input type="date"></p>
    
    <p><label>Time</label>
    <input type="time"></p>
    
    <p><input type="checkbox" value="0">Subscribe me to the newsletter!</p>
    
    <p><label>Comment</label>
    <textarea></textarea></p>
    
    <p><input type="button" value="Submit"></p>
  </fieldset>
</form>
