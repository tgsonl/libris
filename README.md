## *libris*


Libris is primarily a broad and ongoing project with inexorable scope creep that serves as a training ground for honing my skills in Javascript (possibly Typescript?), React (and React-Native) and other web technologies.

Secondarily, it is the kernel of a product I'd like for myself;
- a kind of modern take on [Calibre](https://calibre-ebook.com/)?
- or a sort of [Plex](https://www.plex.tv/) for books, with a sprinkle of self-hosted [Goodreads](https://www.goodreads.com/)?
- A multi-platform toolbox for the researcher, student, conspiracy theorist or leisure reader.

Stay tuned for a feature roadmap!

### Build

Libris is currently being bootstrapped with [Expo](https://expo.dev/). Until the project is ejected from expo, use `npm expo run` to fire up the dev server and desired simulators.

Expo will produce a static bundle for the web with `npx expo export:web`, serve it to `http://locahost:5000` with `npx serve web-build`.

[This](https://stackoverflow.com/a/46170797/15373641) is a possible but unverified way of building a signed apk.

