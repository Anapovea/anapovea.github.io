## What is this?
This is just a test. 


## How is it built?
I have been using [`harp`](http://harpjs.com) to great satisfaction.
No databases, no complex configurations: just `git clone`, `harp compile`, serve the generated `www` directory through NGINX (or similar) and you're all set.

The workflow for, e.g. a new blog post, is hopelessly simple:

1. Add an entry in [`_data.json`](public/blog/_data.json) with some info:
```
{
  "post-url": {
    "title": "Hello World!",
    "date": "August 25th, 2018",
    "author": "Pol"
  }
}
```
2. Write the Markdown-formatted body in `public/blog/post-url.md`, and [`_layout.jade`](public/blog/_layout.jade) takes care of the rest.

Not even three steps, which is great! I use [Bulma CSS](https://bulma.io/) for a decent 5-minute layout.

<h2 id="projects">Projects</h2>

### » [Blockchain by example](https://github.com/aszkid/blockchain)
Very much WIP. A barebones blockchain protocol implementation, very Bitcoin-y in many respects; written in Rust. Node-to-node (Msgpack-encoded TCP stream) and user-node (JSON-RPC) communication.

### » [CHIP-8 emulator](https://github.com/aszkid/chip8)
My first hands-on experience with Rust, served as a first course on writing emulators and understanding how a CPU works at a basic level.

### » [OpenGL renderer](https://github.com/aszkid/milsim)
An attempt at a data-oriented rendering pipeline, implemented using OpenGL. Written in portable C++, heavily inspired by the [bitsquid](http://bitsquid.blogspot.com/) engine (later known as *Stingray*).

-------

<h2 id="math">Math</h2>

### » [Algebraic number theory](https://github.com/aszkid/number_theory)
Paper for Peter May's REU at The University of Chicago, written during the summer of 2018. An introduction to algebraic number theory from a somewhat modern perspective (number fields, ideal class group, group of units).

### » [Polynomial functors](https://github.com/aszkid/polynomial-functor-notes)
Learned about fundamental categorical constructions, and dived into the novel and exciting world of polynomials... at the categorial level, of course!

-------

<h2 id="words">Words</h2>

### » Russian
If you are studying russian, [here](https://github.com/aszkid/russian-anki) is my somewhat decent Anki deck with two years worth of vocabulary and verbs.

### » Catalan
My mother tongue; I write occasionally on literature, language and etymologies. Currently working on migrating an old Blogger site to this platform.

