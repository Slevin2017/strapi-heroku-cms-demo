# Markdown Cheatsheet for Strapi with Gatsby

(Taken from [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet))

This cheatsheet shows you the markdown that is supported when using Strapi with Gatsby.

![Strapi Logo](https://res.cloudinary.com/dunjfeiit/image/upload/v1556888660/f9l8shax7l4ichpv8qze.png)

### Headers

```
# H1
## H2
### H3
#### H4
##### H5
###### H6

```

# H1

## H2

### H3

#### H4

##### H5

###### H6

### Emphasis

```
Emphasis, aka italics, with *asterisks*.

Strong emphasis, aka bold, with **asterisks**.

Combined emphasis with **asterisks and *single asteriks***.

Strikethrough uses two tildes. ~~Scratch this.~~

```

Emphasis, aka italics, with _asterisks_.

Strong emphasis, aka bold, with **asterisks**.

Combined emphasis with **asterisks and _single asteriks_**.

Strikethrough uses two tildes. ~~Scratch this.~~

### Lists

```
1. First ordered list item
2. Another item
    - Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
4. And another item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```

1. First ordered list item
2. Another item
    - Unordered sub-list.
3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
4. And another item.

-   Unordered list can use asterisks

*   Or minuses

-   Or pluses

### Links

This is how to create links:

```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")


[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../Article_1)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com> but not
example.com.

Some text to show that the reference links can follow later (see above).

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

```

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../Article_1)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com> but not
example.com.

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

### Images

Here's our logo (hover to see the title text):

Inline-style:

![Strapi Logo](https://res.cloudinary.com/dunjfeiit/image/upload/v1556888660/f9l8shax7l4ichpv8qze.png 'Strapi Logo')

Reference-style:

<img class="small" src="/uploads/16d3c59d30cc41cba45862dc782a6c9c.png" alt="Small Gatsby Logo" />

<img  src="/uploads/16d3c59d30cc41cba45862dc782a6c9c.png" alt="Default Gatsby Logo" />

![text](https://res.cloudinary.com/dunjfeiit/image/upload/v1556888704/s0mji46npwzj4rpfvkbc.png 'Gatsby Logo')

<img class="large" src="/uploads/16d3c59d30cc41cba45862dc782a6c9c.png" alt="LargeGatsby Logo" />

### Code

Code blocks are part of the Markdown spec.

```
Inline `code` has `back-ticks around` it.
```

Inline `code` has `back-ticks around` it.

Blocks of code are either fenced by lines with three back-ticks ```, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier.

````

    ```
    But let's throw in a <b>tag</b>.
    ```

````

```
But let's throw in a <b>tag</b>.
```
