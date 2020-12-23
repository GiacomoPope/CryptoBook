# CryptoBook

## About this project

I am starting this repository to motivate myself to create a space to document the mathematics I am learning while building CryptoHack and learning cryptography. 

More than anything, I am grateful for the community of people within CryptoHack who have made the discord such an interesting and educational place, and I hope that this repo can become an extension of that, helping each other learn in a more formal and permanent setting.

My first goal for this book is to include background chapters on some aspects of pure mathematics which appear in cryptography. Something I feel that is commonly missing from texts is *why* certain protocols use certain properties. Why do perform Diffie-Hellman key exchange in Abelian groups? Of all the curves, why do we pick elliptic curves? Would conic sections be ok? To have a proper appreciation for this, I think a offering a discussion on the fundementals of the inner workings of cryptographic protocols is necessary. My hope is to present this in a form which is palatable for people without formal educations in mathematics.

Another goal of this project is to include code snippets as examples of protocols, attacks and maths tricks as standard. I know several of us have used the `sage` docs when trying to solve CTFs and commonly it's hard to find precisely what functions to use, and when. I would like this book to have chapters devoted to protocols and their weaknesses. Implmentation of attacks with code given. For now, I think it would be best to have examples given in sage/python and as the book grows, we can look to Magma, or lower-level programming languages. 

I hope these two goals are interesting to the community and that together we can create a great resource together. 

The book is run using [mdbook](https://rust-lang.github.io/mdBook/index.html). The whole book is built from markdown files and should be simple to upkeep. We have access to MathJax for latex maths, and we have code highlighting for code snippets.

## Authors

Jack, ...

(Please add your names to this and the toml as you wish)

## To Do

I have made a [file](TODO.md) which has a list of topics as a checklist. If you have ideas of topics which should be covered, please add them. If you write a page which covers a topic in the list, update it my marking it complete.

## Installation 

To build the book, you must have [rust](https://www.rust-lang.org/learn/get-started) installed. With rust installed, you can download mdbook with 

```
cargo install mdbook 
cargo install mdbook-classy
```

🦀🦀🦀

**Note:** `mdbook-classy` is used to render div elements through preprocessing and currently causes some other markdown bugs... We either need to write one ourselves as a fork, or do a PR on the mdbook-classy github. Any rust people wanna give it a go? 

🦀🦀🦀

You can build the book with 

```
mdbook build
```

or use 

```
mdbook watch
```

to render changes as you save files.

To preview the book, run 

```
mdbook serve 
```

and go to `localhost:3000` to see the current progress

## mdBook

For more details of mdBook, the source code is on [GitHub](https://github.com/rust-lang/mdBook) and they have a [user guide](https://rust-lang.github.io/mdBook/) documenting the features available. Generally, each page in the book is created as a markdown file and then indexed by including it in the SUMMARY.md




