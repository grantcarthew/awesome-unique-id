# Awesome Unique ID [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![All Contributors](https://img.shields.io/github/all-contributors/grantcarthew/awesome-unique-id?color=ee8449)](https://github.com/grantcarthew/awesome-unique-id/graphs/contributors)

A curated list of awesome Unique ID libraries and resources.

Unique identifiers are used everywhere. This list contains awesome projects you can use that generate IDs or hash them for security.

## Contents

- [Generation](#generation)
- [Hash](#hash)
- [CLI Tools](#cli-tools)
- [Research](#research)
- [Contributors](#contributors)

## Generation

### Polyglot

- [uuidv7](https://github.com/nalgeon/uuidv7) ([RFC9562 uuidv7 reference](https://www.rfc-editor.org/rfc/rfc9562#name-uuid-version-7)) - UUID 128-bit unique identifier that is time-sortable with 1 ms precision.

### JavaScript

- [uuid](https://github.com/kelektiv/node-uuid) ([npm](https://www.npmjs.com/package/uuid)) - Simple, fast generation of RFC4122 UUIDS.
- [ulid](https://github.com/ulid) ([npm](https://www.npmjs.com/package/ulid)) - Universally Unique Lexicographically Sortable Identifier.
- [cuid2](https://github.com/paralleldrive/cuid2) ([npm](https://www.npmjs.com/package/@paralleldrive/cuid2)) - Secure, collision-resistant ids optimized for horizontal scaling and performance. Next generation uuids.
- [nanoid](https://github.com/ai/nanoid) ([npm](https://www.npmjs.com/package/nanoid)) - A tiny, secure URL-friendly unique string ID generator for JavaScript.
- [crypto-random-string](https://github.com/sindresorhus/crypto-random-string) ([npm](https://www.npmjs.com/package/crypto-random-string)) - Generate a cryptographically strong random string.
- [yeast](https://github.com/unshiftio/yeast) ([npm](https://www.npmjs.com/package/yeast)) - Yeast is a unique id generator.
- [shortid](https://github.com/dylang/shortid) ([npm](https://www.npmjs.com/package/shortid)) - Amazingly short non-sequential url-friendly unique id generator.
- [uniqid](https://github.com/adamhalasz/uniqid) ([npm](https://www.npmjs.com/package/uniqid)) - A Unique Hexatridecimal ID generator.
- [puid](https://github.com/pid/puid) ([npm](https://www.npmjs.com/package/puid)) - Generate a unique ID depending on time, machine and process for use in a distributed environment.
- [flake-idgen](https://github.com/T-PWK/flake-idgen) ([npm](https://www.npmjs.com/package/flake-idgen)) - Flake ID generator yields k-ordered, conflict-free ids in a distributed environment.
- [get-uid](https://github.com/dfcreative/get-uid) ([npm](https://www.npmjs.com/package/get-uid)) - Simple random id generator.
- [uniqueid](https://github.com/jonschlinkert/uniqueid) ([npm](https://www.npmjs.com/package/uniqueid)) - Generate sequential IDs, with optional prefix or suffix.
- [hyperid](https://github.com/mcollina/hyperid) ([npm](https://www.npmjs.com/package/hyperid)) - Uber-fast unique id generation, for Node.js and the browser.
- [uid](https://github.com/lukeed/uid) ([npm](https://www.npmjs.com/package/uid)) - Generate unique ids of any length.
- [uid-safe](https://github.com/crypto-utils/uid-safe) ([npm](https://www.npmjs.com/package/uid-safe)) - URL and cookie safe UIDs.
- [uuid-readable](https://github.com/Debdut/uuid-readable) ([npm](https://www.npmjs.com/package/uuid-readable)) - Generate Easy to Remember, Readable UUIDs, that are Shakespearean and Grammatically Correct Sentences.
- [human-id](https://github.com/RienNeVaPlus/human-id) ([npm](https://www.npmjs.com/package/human-id)) - Generates human-readable identifier strings by chaining common (short) words of the English language. 
- [unique-sequence](https://github.com/kayomarz/unique-sequence) ([npm](https://www.npmjs.com/package/unique-sequence)) - Generate short sequential strings.
- [breezeid](https://github.com/tzwel/BreezeID) ([npm](https://www.npmjs.com/package/breezeid)) - Easily generate unique, human-first IDs
- [Sqids](https://sqids.org) ([npm](https://www.npmjs.com/package/sqids)) - Sqids is a small JavaScript library to generate YouTube-like ids from numbers.
- [ksuid](https://github.com/novemberborn/ksuid) ([npm](https://www.npmjs.com/package/ksuid)) - K-Sortable Globally Unique IDs


### Python

- [muid](https://github.com/microprediction/muid) ([PyPI](https://pypi.org/project/muid/)) - Generates IDs whose hashes are, in part, memorable. See [video explanation](https://vimeo.com/397352413)

### Go

- [xid](https://github.com/rs/xid) - Xid is a globally unique id generator thought for the web.
- [ksuid](https://github.com/segmentio/ksuid) - K-Sortable Globally Unique IDs.


## Hash

- [RoboHash](https://robohash.org/) ([GitHub](https://github.com/e1ven/Robohash)) - Generate unique images from any text.

## CLI Tools

- [uuinfo](https://github.com/racum/uuinfo) - A tool to debug unique identifiers (UUID, ULID, Snowflake, etc).
- [OSSP uuid](http://www.ossp.org/pkg/lib/uuid/) - ISO-C API and CLI for generating UUIDs

## Research
* Articles/papers
    - [The definitive guide to modulo bias and how to avoid it](https://research.kudelskisecurity.com/2020/07/28/the-definitive-guide-to-modulo-bias-and-how-to-avoid-it) - Generate unbiased random numbers.
    - [Efficiently generating a number in range](https://www.pcg-random.org/posts/bounded-rands.html) - Discusses performance problems in PRNGs and many algorithms.
    - [Understanding modulo bias](https://web.archive.org/web/20240802033931/https://julian.bayardo.info/understanding-modulo-bias/) (archive)
      
* Collision calculators
  - [Devina.io collision calculator](https://devina.io/collision-calculator)
  - [Nano ID collision calculator (by Alexey Komarov)](https://alex7kom.github.io/nano-nanoid-cc/)
  - [Nano ID collision calculator (by Aleksandr Zhuravlёv)](https://zelark.github.io/nano-id-cc/)

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/tzwel"><img src="https://avatars.githubusercontent.com/u/39600182?v=4?s=100" width="100px;" alt="tzwel"/><br /><sub><b>tzwel</b></sub></a><br /><a href="#content-tzwel" title="Content">🖋</a> <a href="https://github.com/grantcarthew/awesome-unique-id/commits?author=tzwel" title="Documentation">📖</a> <a href="#ideas-tzwel" title="Ideas, Planning, & Feedback">🤔</a> <a href="#maintenance-tzwel" title="Maintenance">🚧</a> <a href="#research-tzwel" title="Research">🔬</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kayomarz"><img src="https://avatars.githubusercontent.com/u/140297?v=4?s=100" width="100px;" alt="Kayomarz"/><br /><sub><b>Kayomarz</b></sub></a><br /><a href="#content-kayomarz" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://madcity.at"><img src="https://avatars.githubusercontent.com/u/343392?v=4?s=100" width="100px;" alt="Matthias Esterl"/><br /><sub><b>Matthias Esterl</b></sub></a><br /><a href="#content-madc" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://microprediction.medium.com/"><img src="https://avatars.githubusercontent.com/u/57455669?v=4?s=100" width="100px;" alt="Peter Cotton"/><br /><sub><b>Peter Cotton</b></sub></a><br /><a href="#content-microprediction" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/amitlzkpa"><img src="https://avatars.githubusercontent.com/u/15354742?v=4?s=100" width="100px;" alt="Amit Nambiar"/><br /><sub><b>Amit Nambiar</b></sub></a><br /><a href="#content-amitlzkpa" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/cuongndc"><img src="https://avatars.githubusercontent.com/u/34389409?v=4?s=100" width="100px;" alt="Cuong Nguyen"/><br /><sub><b>Cuong Nguyen</b></sub></a><br /><a href="#content-cuongndc" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.racum.com/"><img src="https://avatars.githubusercontent.com/u/236879?v=4?s=100" width="100px;" alt="Ronaldo Ferreira"/><br /><sub><b>Ronaldo Ferreira</b></sub></a><br /><a href="#content-Racum" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
