---
title: Smart Contracts 101
date: "2022-02-24T00:00:03.284Z"
description: "Let's Learn Solidity"
---

This is my first post on my new blog! How exciting!<br>
I'm sure I'll write a lot more interesting things in the future.

Oh, btw you guys might be curious to learn [Ethereum](https://en.wikipedia.org/wiki/Salted_duck_egg) and [Solidity](https://docs.soliditylang.org/en/v0.8.12/) after the 2021 Crypto Bull Run.

Learning Smart Contract Development is absolute necessity if you want to be a Blockchain or a web3.0 developer. 

But, what the heck is a Smart Contract?

### Smart Contracts: A Transparent Way To Do Business
> "A smart contract is an agreement, in the form of a computer program
> that is executed automatically once certain pre-programmed conditions are satisfied.
> On blockchain, the goal of a smart contract is to simplify business and trade between both anonymous and identified parties,
> sometimes without the need for a middleman."<br>
> -- <cite>Infosys Digital Future Newsletter </cite>

This is how the "Hello World" of Solidity Smart Contract on Ethereum Blockchain looks like:

```js
// My First Smart Contract 
pragma solidity 0.8.7;
contract HelloWorld {
    function get()public pure returns (string memory){
        return 'Hello Contracts';
    }
}
```
<h4 style="color: #0773bddb;">But why do we need Smart Contracts at the first place?</h4>

Let's take a simple scenario. Suppose you're living in USA and you have to send $5000 to your friend living in India. The traditional way is to go to your bank and Transfer the money to your friend's bank account. The Bank (The centralised System) is the mediator on which you 'Trust'. The bank as a service provider will charge you money as a commision fees for this wire transfer. Also there are Remittance charges you need to pay while transferring the money (Out of scope. need to to discuss further). Your friend might end up receiving $4500.

**But, Can't we send money directly without the middlemen or a third party involved?**

Suppose We have trust issues. People can't be trusted. Middlemen and companies can't be trusted. So can we build a system which is automated and we just have to trust the Full-proof

| Number | Title                                    | Year |
| :----- | :--------------------------------------- | ---: |
| 1      | Harry Potter and the Philosopher’s Stone | 2001 |
| 2      | Harry Potter and the Chamber of Secrets  | 2002 |
| 3      | Harry Potter and the Prisoner of Azkaban | 2004 |

[View raw (TEST.md)](https://raw.github.com/adamschwartz/github-markdown-kitchen-sink/master/README.md)

This is a paragraph.

    This is a paragraph.

# Header 1

## Header 2

    Header 1
    ========

    Header 2
    --------

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

    # Header 1
    ## Header 2
    ### Header 3
    #### Header 4
    ##### Header 5
    ###### Header 6

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

    # Header 1 #
    ## Header 2 ##
    ### Header 3 ###
    #### Header 4 ####
    ##### Header 5 #####
    ###### Header 6 ######

> Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

    > Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.
>
> Here's some example code:
>
>     Markdown.generate();

    > ## This is a header.
    > 1. This is the first list item.
    > 2. This is the second list item.
    >
    > Here's some example code:
    >
    >     Markdown.generate();

- Red
- Green
- Blue

* Red
* Green
* Blue

- Red
- Green
- Blue

```markdown
- Red
- Green
- Blue

* Red
* Green
* Blue

- Red
- Green
- Blue
```

- `code goes` here in this line
- **bold** goes here

```markdown
- `code goes` here in this line
- **bold** goes here
```

1. Buy flour and salt
1. Mix together with water
1. Bake

```markdown
1. Buy flour and salt
1. Mix together with water
1. Bake
```

1. `code goes` here in this line
1. **bold** goes here

```markdown
1. `code goes` here in this line
1. **bold** goes here
```

Paragraph:

    Code

<!-- -->

    Paragraph:

        Code

---

---

---

---

---

    * * *

    ***

    *****

    - - -

    ---------------------------------------

This is [an example](http://example.com "Example") link.

[This link](http://example.com) has no title attr.

This is [an example][id] reference-style link.

[id]: http://example.com "Optional Title"

    This is [an example](http://example.com "Example") link.

    [This link](http://example.com) has no title attr.

    This is [an example] [id] reference-style link.

    [id]: http://example.com "Optional Title"

_single asterisks_

_single underscores_

**double asterisks**

**double underscores**

    *single asterisks*

    _single underscores_

    **double asterisks**

    __double underscores__

This paragraph has some `code` in it.

    This paragraph has some `code` in it.

![Alt Text](https://placehold.it/200x50 "Image Title")

    ![Alt Text](https://placehold.it/200x50 "Image Title")
