---
title: "Html Test"
date: 2021-03-14T19:44:54-05:00
draft: false
tags: ['code','lorem','test','html']
menu:
    main:
        parent: "code"
---

## Html Test Page

**This is incomplete, more will be added as needed. Delete the custom markdown section or it may
break your code with static site generators.**

This is a test page that shows all the elements for troubleshooting layouts. I try to keep
paragraphs short and sentences short. The objective is to make things break so that they can be
fixed.

## List Elements

**Horizontal line here**

---

**BULLETS**

* Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
* Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Integer eu dolor urna. Maecenas nec faucibus dui. Sed nibh mi, dapibus sit amet
eros nec, interdum rhoncus leo. Pellentesque nec vulputate elit. Curabitur.

**Github Task**

---

- [ ] **Task Unchecked long bold** - Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.
- [x] **Checked** - Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.
- [x] **Checked** - Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.
{.task}

**BOLD**

---

* **Bold long item** - Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.
* **Bold** - **This one has a space above**. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.

Cras est ligula, viverra a malesuada quis, egestas id magna. Praesent
ullamcorper ligula ut felis egestas laoreet. Integer nec mauris a justo aliquam
faucibus. Curabitur molestie quam sed tellus euismod, vitae faucibus ipsum.


**NESTED LIST**

---

* Disc 1
    * circle 2
    * circle 2
        * square 3
        * square 3
            * decimal 4
            * decimal 4
                * upper-roman 4
                    * lower-roman 5
                        * decimal-leading-zero 6
                            * circle 7


* Groceries
    * Produce
        * Apples
        * Bannanas
    * Meats
        * Tbone Steaks
        * Salmon

**Definitions H3**

---

Definition 1
: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud.

Defination 2
: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.

Definition 3
: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.

## Custom Markdown

**THIS IS CUSTOM MARKDOWN, IT MAY BREAK YOUR CODE IF YOU'RE USING A STATIC SITE GENERATOR**

These are attribute blocks in [hugo/goldmark](https://gohugo.io/getting-started/configuration-markup#config) if
you are using markdown-it you can use [markdown-it-attrs](https://github.com/arve0/markdown-it-attrs).

```text
{.fold}
```



This block quote has a caption.
>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
>vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
>Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
>scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.
{.fold data-caption="My Caption"}

Some javascript here with a fold.

```javascript
console.log('hello')
```
{.fold}

Vuepress warnings.

::: warning
This is warning. Usually pandoc and markdown-it support this. You need shortcodes in hugo
or will need the equivalent in another ssg. This won't break any code.
:::


This may break some static site generators. What about ```{{$this := "here"}}```.

```html
{{ $var := "foo"}}
```

Some static site generators can't handle yaml in a code block like this.

```yaml
---
title: My Title
draft: false
date: 2021-03-14T19:44:54-05:00
---
```

**Tables**

---

**Simple Long Table** - Mostly just eyeballed it and set ```td{ width:255px; }```
I also added the ```{.center}```.

|PROS|CONS|
|---|---|
|Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.|Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.|
{.center}


**Code**

---

**Vimscript here:**

```vim
function DoSomething() abort
echo "hello"
endfunction
```

**Html template long code example.**

```html
<!-- terms.html -->
{{define "head"}}
{{partial "head.html" .}}
<link rel='stylesheet' href='{{"css/flex.css" | absURL | safeURL}}' type='text/css' media='all' />
{{end}}
{{define "main"}}
<!-- HTML STUFF HERE -->
{{end}}
```

**Headers**


---

**Test different fonts.**

## Header2
### Header3
#### Header4
##### Header5
###### Header6

---

**All in paragraphs.**

## Headers H2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur

### Header H3

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur

#### Header H4

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur

##### Header H5

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur

###### Header H6

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur

---

**Test the sidebar.**

## Parent One H2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

### Child H3

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

### Child H3

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

## Parent Two H2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

### Child H3

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

### Child H3

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

#### Nested H4

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

#### Nested H4

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

##### Deep H5

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

###### Max Nest H6

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

## Parent Three H2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

## The End H2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tortor urna, semper
vel justo quis, aliquet varius nunc. Nulla a dictum magna, sed convallis augue.
Phasellus vehicula ipsum non volutpat rhoncus. Fusce vel tempus augue. Curabitur
scelerisque accumsan aliquet. Etiam in faucibus lectus, sit amet bibendum nibh.

