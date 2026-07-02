# About Computer Motivators Search

Computer Motivators Search is a [metasearch engine] that aggregates results from other
{{link('search engines', 'preferences')}} without storing information about its users.

It is operated by **Computer Motivators** and built on the open-source [SearXNG] project.

## Why use it?

- Computer Motivators Search may not offer you as personalized results as Google, but it does not
  generate a profile about you.
- It does not care about what you search for, never shares anything with a
  third party, and cannot be used to compromise you.
- The underlying engine is free software; the code is open, and the community is welcome to
  improve it.

If you care about privacy and want a conscious search experience, use Computer Motivators Search
as your default search engine.

## How do I set it as the default search engine?

Computer Motivators Search supports [OpenSearch]. For more information on changing your default
search engine, see your browser's documentation:

- [Firefox]
- [Microsoft Edge] — Behind the link, you will also find some useful instructions
  for Chrome and Safari.
- [Chromium]-based browsers only add websites that the user navigates to without
  a path.

When adding a search engine, there must be no duplicates with the same name. If
you encounter a problem where you cannot add the search engine, you can either:

- Remove the duplicate (default name: Computer Motivators Search) or
- Contact the instance maintainer to give the instance a different name.

## How does it work?

Computer Motivators Search is powered by [SearXNG], a fork of the well-known [searx] [metasearch engine]
inspired by the [Seeks project]. It provides basic privacy by mixing your queries with searches on
other platforms without storing search data.

## Built on SearXNG

This instance runs on [SearXNG], an open privacy-respecting metasearch engine maintained by a
global community. Source code, documentation, and issue tracking for the upstream project are
available on [GitHub].

[metasearch engine]: https://en.wikipedia.org/wiki/Metasearch_engine
[SearXNG]: https://github.com/searxng/searxng
[searx]: https://github.com/searx/searx
[Seeks project]: https://benjamin.sonntag.fr/Seeks/
[OpenSearch]: https://github.com/dewitt/opensearch/blob/master/opensearch-1-1-draft-6.md
[Firefox]: https://support.mozilla.org/en-US/kb/add-or-remove-search-engine-firefox
[Microsoft Edge]: https://support.microsoft.com/en-us/microsoft-edge/add-or-remove-a-search-engine-in-microsoft-edge-44fac142-256f-e014-018a-c4378eb9885d
[Chromium]: https://www.chromium.org/tab-to-search
[GitHub]: https://github.com/searxng/searxng
