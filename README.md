# lionfish.app

Repository to talk about lionfish.app or report issues.

[lionfish.app](https://lionfish.app/) is a side project under heavy development. It's still **pre-alpha** software. It was announced originally [on Twitter](https://twitter.com/gimenete/status/1466785498253381632?s=20) and I'm making this repo to talk about it and allow people to report issues.

## Purpose

lionfish.app aims to be an alternative GitHub UI focused on your day to day work, speed, and at the same time provide a lot of information density. Instead of being document-based, it is a single page application where you can navigate from one piece of information to another without having to close previous views or opening new tabs.

## Implementation details

It's a 100% static app. There's no backend. It uses React, react-query, jotai and Primer React components.

Right now the login is done using a GitHub Personal Access Token for a few reasons:

- Doesn't require a backend.
- Doesn't require to ask administrators to gran access to some repositories that may require it.
- Once you know how to do it it's easy to revoke or generate new tokens with different permissions, or change the permissions of an existing token, etc.

If you want to sign in, create a [new token](https://github.com/settings/tokens/new). Recommended scopes are `repo`, `gist`, `notifications` and `user`.

## FAQ

**Is it open source?**

Not now. Eventually, maybe.

**Can I report a problem?**

Sure. Create an issue [here](https://github.com/gimenete/lionfish.app/issues/new).

**Can I discuss something or request a feature?**

Sure. Create an issue [here](https://github.com/gimenete/lionfish.app/issues/new).

**How can I get updates on the development status?**

[Follow me on Twitter](https://twitter.com/gimenete) or watch this repo!
