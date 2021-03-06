# [![retext][logo]][unified]

[![Build][build-badge]][build]
[![Coverage][coverage-badge]][coverage]
[![Downloads][downloads-badge]][downloads]
[![Size][size-badge]][size]
[![Sponsors][sponsors-badge]][collective]
[![Backers][backers-badge]][collective]
[![Chat][chat-badge]][chat]

**retext** is a natural language processor powered by [plugins][] part of the
[unified][] [collective][].

## Intro

**retext** is an ecosystem of [plugins][] for processing natural language to do
all kinds of things: [check spelling][spell], [fix typography][smartypants], or
[make sure text is readable][readability].

*   Visit [`unifiedjs.com`][website] and peruse its [Learn][] section for an
    overview
*   Read [unified][]’s readme for a technical intro
*   Browse [awesome retext][awesome] to find out more about the ecosystem
*   Follow us on [Twitter][] to see what we’re up to
*   Check out [Contribute][] below to find out how to help out

This repository contains the following projects:

*   [`retext-english`][english] — Parse English prose to a syntax tree
*   [`retext-dutch`][dutch] — Parse Dutch prose to a syntax tree
*   [`retext-latin`][latin] — Parse any Latin-script prose to a syntax tree
*   [`retext-stringify`][stringify] — Serialize a syntax tree
*   [`retext`][api] — Programmatic interface with both `retext-latin` and `retext-stringify`

## Sponsors

Support this effort and give back by sponsoring on [OpenCollective][collective]!

<!--lint ignore no-html-->

<table>
<tr valign="middle">
<td width="20%" align="center" colspan="2">
  <a href="https://www.gatsbyjs.org">Gatsby</a> 🥇<br><br>
  <a href="https://www.gatsbyjs.org"><img src="https://avatars1.githubusercontent.com/u/12551863?s=256&v=4" width="128"></a>
</td>
<td width="20%" align="center" colspan="2">
  <a href="https://vercel.com">Vercel</a> 🥇<br><br>
  <a href="https://vercel.com"><img src="https://avatars1.githubusercontent.com/u/14985020?s=256&v=4" width="128"></a>
</td>
<td width="20%" align="center" colspan="2">
  <a href="https://www.netlify.com">Netlify</a><br><br>
  <!--OC has a sharper image-->
  <a href="https://www.netlify.com"><img src="https://images.opencollective.com/netlify/4087de2/logo/256.png" width="128"></a>
</td>
<td width="10%" align="center">
  <a href="https://www.holloway.com">Holloway</a><br><br>
  <a href="https://www.holloway.com"><img src="https://avatars1.githubusercontent.com/u/35904294?s=128&v=4" width="64"></a>
</td>
<td width="10%" align="center">
  <a href="https://themeisle.com">ThemeIsle</a><br><br>
  <a href="https://themeisle.com"><img src="https://avatars1.githubusercontent.com/u/58979018?s=128&v=4" width="64"></a>
</td>
<td width="10%" align="center">
  <a href="https://boostio.co">BoostIO</a><br><br>
  <a href="https://boostio.co"><img src="https://avatars1.githubusercontent.com/u/13612118?s=128&v=4" width="64"></a>
</td>
<td width="10%" align="center">
  <a href="https://expo.io">Expo</a><br><br>
  <a href="https://expo.io"><img src="https://avatars1.githubusercontent.com/u/12504344?s=128&v=4" width="64"></a>
</td>
</tr>
<tr valign="middle">
<td width="100%" align="center" colspan="10">
  <br>
  <a href="https://opencollective.com/unified"><strong>You?</strong></a>
  <br><br>
</td>
</tr>
</table>

## Contribute

See [`contributing.md`][contributing] in [`retextjs/.github`][health] for ways
to get started.
See [`support.md`][support] for ways to get help.
Ideas for new plugins and tools can be posted in [`retextjs/ideas`][ideas].

A curated list of awesome retext resources can be found in [**awesome
retext**][awesome].

This project has a [code of conduct][coc].
By interacting with this repository, organization, or community you agree to
abide by its terms.

## License

[MIT][license] © [Titus Wormer][author]

<!-- Definitions -->

[logo]: https://raw.githubusercontent.com/retextjs/retext/976354b/logo.svg?sanitize=true

[build-badge]: https://img.shields.io/travis/retextjs/retext.svg

[build]: https://travis-ci.org/retextjs/retext

[coverage-badge]: https://img.shields.io/codecov/c/github/retextjs/retext.svg

[coverage]: https://codecov.io/github/retextjs/retext

[downloads-badge]: https://img.shields.io/npm/dm/retext.svg

[downloads]: https://www.npmjs.com/package/retext

[size-badge]: https://img.shields.io/bundlephobia/minzip/retext.svg

[size]: https://bundlephobia.com/result?p=retext

[sponsors-badge]: https://opencollective.com/unified/sponsors/badge.svg

[backers-badge]: https://opencollective.com/unified/backers/badge.svg

[collective]: https://opencollective.com/unified

[chat-badge]: https://img.shields.io/badge/chat-discussions-success.svg

[chat]: https://github.com/retextjs/retext/discussions

[health]: https://github.com/retextjs/.github

[contributing]: https://github.com/retextjs/.github/blob/main/contributing.md

[support]: https://github.com/retextjs/.github/blob/main/support.md

[coc]: https://github.com/retextjs/.github/blob/main/code-of-conduct.md

[license]: license

[author]: https://wooorm.com

[unified]: https://github.com/unifiedjs/unified

[website]: https://unifiedjs.com

[learn]: https://unifiedjs.com/learn/

[twitter]: https://twitter.com/unifiedjs

[english]: https://github.com/retextjs/retext/tree/main/packages/retext-english

[dutch]: https://github.com/retextjs/retext/tree/main/packages/retext-dutch

[latin]: https://github.com/retextjs/retext/tree/main/packages/retext-latin

[stringify]: https://github.com/retextjs/retext/tree/main/packages/retext-stringify

[api]: https://github.com/retextjs/retext/tree/main/packages/retext

[ideas]: https://github.com/retextjs/ideas

[awesome]: https://github.com/retextjs/awesome-retext

[plugins]: https://github.com/retextjs/retext/tree/main/doc/plugins.md

[spell]: https://github.com/retextjs/retext-spell

[smartypants]: https://github.com/retextjs/retext-smartypants

[readability]: https://github.com/retextjs/retext-readability

[contribute]: #contribute
