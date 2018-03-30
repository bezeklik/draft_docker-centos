# Supported tags and respective `Dockerfile` links

- `lastest`, `7.4`, `7` [(*Dockerfile*)](https://github.com/bezeklik/docker-centos/blob/master/Dockerfile)
- `7.4-php`, `7.4-php72`, `7-php`, `7-php72` [(*Dockerfile*)]()
- `7.4-php71`, `7-php71` [(*Dockerfile*)]()
- `7.4-php70`, `7-php70` [(*Dockerfile*)]()
- `7.4-php56`, `7-php56` [(*Dockerfile*)]()
- `7.4-php-base`, `7-php-base` [(*Dockerfile*)]()
- `6.9`, `6` [(*Dockerfile*)]()
- `6.9-php`, `6-php` [(*Dockerfile*)]()
- `5.11`, `5` [(*Dockerfile*)]()
- `5.11-php`, `5-php` [(*Dockerfile*)]()
- `5.11-php53`, `5-php53` [(*Dockerfile*)](https://github.com/bezeklik/docker-centos/blob/php53/Dockerfile)

# Quick reference

- **Where to get help:**

- **Where to file issues:**

https://github.com/bezeklik/docker-centos/issues

- **Maintained by:**

[Bezeklik](https://github.com/bezeklik/)

- **Supported architectures:**

- **Published image artifact details:**

- **Image updates:**

- **Source of this description:**

- **Supported Docker versions:**

# What is Centos5?

# How to use this image

## Usage

```
docker run --interactive --tty --name centos5 bezeklik/centos5 bash
```

# License

View [license information](https://github.com/bezeklik/test2/blob/master/LICENSE) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `centos/` directory](https://github.com/docker-library/repo-info/tree/master/repos/centos).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.

Alt-H1
======

Alt-H2
------

# h1
## h2
### h3
#### h4
##### h5
###### h6

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

Strikethrough uses two tildes. ~~Scratch this.~~

* Item 1
* Item 2
  * Item 2a
  * Item 2b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

http://github.com - automatic!
[GitHub](http://github.com)

As Kanye West said:

> We're living the future so
> the present is our past.

I think you should use an
`<addr>` element here instead.

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

|Left|Center|Right|
|---|:-:|--:|
|Line 1 Column 1|Line 1 Column 2|Line 1 Column 3|
|Line 2 Column 1||$100|
|Line 3 Column 1||$200|

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

Three or more...

---

Hyphens

***

Asterisks

___

Underscores
