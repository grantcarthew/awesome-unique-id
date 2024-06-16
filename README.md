# Awesome Unique ID [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome Unique ID libraries and resources.

Unique identifiers are used everywhere. This list contains awesome projects you can use that generate IDs or hash then for security.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

* [Generation](#generation)
* [Hash](#hash)
* [Research](#research)

## Generation

### JavaScript
* [uuid](https://github.com/kelektiv/node-uuid) ([npm](https://www.npmjs.com/package/uuid)) - Simple, fast generation of RFC4122 UUIDS.
* [ulid](https://github.com/ulid) ([npm](https://www.npmjs.com/package/ulid)) - Universally Unique Lexicographically Sortable Identifier.
* [cuid2](https://github.com/paralleldrive/cuid2) ([npm](https://www.npmjs.com/package/@paralleldrive/cuid2)) - Secure, collision-resistant ids optimized for horizontal scaling and performance. Next generation uuids.
* [nanoid](https://github.com/ai/nanoid) ([npm](https://www.npmjs.com/package/nanoid)) - A tiny, secure URL-friendly unique string ID generator for JavaScript.
* [crypto-random-string](https://github.com/sindresorhus/crypto-random-string) ([npm](https://www.npmjs.com/package/crypto-random-string)) - Generate a cryptographically strong random string.
* [yeast](https://github.com/unshiftio/yeast) ([npm](https://www.npmjs.com/package/yeast)) - Yeast is a unique id generator.
* [shortid](https://github.com/dylang/shortid) ([npm](https://www.npmjs.com/package/shortid)) - Amazingly short non-sequential url-friendly unique id generator.
* [lodash.uniqueid](https://github.com/lodash/lodash) ([npm](https://www.npmjs.com/package/lodash.uniqueid)) - The lodash method uniqueId exported as a Node.js module.
* [uniqid](https://github.com/adamhalasz/uniqid) ([npm](https://www.npmjs.com/package/uniqid)) - A Unique Hexatridecimal ID generator.
* [puid](https://github.com/pid/puid) ([npm](https://www.npmjs.com/package/puid)) - Generate an unique ID depending on time, machine and process for use in a distributed environment.
* [flake-idgen](https://github.com/T-PWK/flake-idgen) ([npm](https://www.npmjs.com/package/flake-idgen)) - Flake ID generator yields k-ordered, conflict-free ids in a distributed environment.
* [get-uid](https://github.com/dfcreative/get-uid) ([npm](https://www.npmjs.com/package/get-uid)) - Simple random id generator.
* [uniqueid](https://github.com/jonschlinkert/uniqueid) ([npm](https://www.npmjs.com/package/uniqueid)) - Generate sequential IDs, with optional prefix or suffix.
* [hyperid](https://github.com/mcollina/hyperid) ([npm](https://www.npmjs.com/package/hyperid)) - Uber-fast unique id generation, for Node.js and the browser.
* [uid](https://github.com/lukeed/uid) ([npm](https://www.npmjs.com/package/uid)) - Generate unique ids of any length.
* [uid-safe](https://github.com/crypto-utils/uid-safe) ([npm](https://www.npmjs.com/package/uid-safe)) - URL and cookie safe UIDs.
* [nanoid](https://github.com/ai/nanoid) ([npm](https://www.npmjs.com/package/nanoid)) - A tiny, secure, URL-friendly, unique string ID generator for JavaScript.
* [uuid-readable](https://github.com/Debdut/uuid-readable) ([npm](https://www.npmjs.com/package/uuid-readable)) - Generate Easy to Remember, Readable UUIDs, that are Shakespearean and Gramatically Correct Sentences.
* [human-id](https://github.com/RienNeVaPlus/human-id) ([npm](https://www.npmjs.com/package/human-id)) - Generates human readable identifier strings by chaining common (short) words of the english language. 
* [unique-sequence](https://github.com/kayomarz/unique-sequence) ([npm](https://www.npmjs.com/package/unique-sequence)) - Generate short sequential strings.
* [breezeid](https://github.com/tzwel/BreezeID) ([npm](https://www.npmjs.com/package/breezeid)) - Easily generate unique, human-first IDs
* [Sqids](https://sqids.org) ([npm](https://www.npmjs.com/package/sqids)) - Sqids is small JavaScript library to generate YouTube-like ids from numbers.
* [ksuid](https://github.com/novemberborn/ksuid) ([npm](https://www.npmjs.com/package/ksuid)) - K-Sortable Globally Unique IDs


### Python
* [muid](https://github.com/microprediction/muid) Generates IDs whose hashes are, in part, memorable. See [video explanation](https://vimeo.com/397352413)

### Go
* [xid](https://github.com/rs/xid) - xid is a globally unique id generator thought for the web.
* [ksuid](https://github.com/segmentio/ksuid) - K-Sortable Globally Unique IDs.


## Hash
* [RoboHash](https://robohash.org/) ([github](https://github.com/e1ven/Robohash)) - Generate unique images from any text.

## Research
- [The definitive guide to modulo bias and how to avoid it](https://research.kudelskisecurity.com/2020/07/28/the-definitive-guide-to-modulo-bias-and-how-to-avoid-it) - Generate unbiased random numbers
- [Efficiently generating a number in range](https://www.pcg-random.org/posts/bounded-rands.html) - Discusses performance problems in PRNGs and many algorithms



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Grant Carthew](https://github.com/grantcarthew) has waived all copyright and related or neighboring rights to this work.
