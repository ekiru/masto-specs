# Specifications for some proposed Mastodon extensions

These are specifications for features I want to propose/implement/have in the glitch-soc fork (though upstream or other forks supporting them would be pretty cool, too).

## Why specifications?

A number of Mastodon instances have various customizations or custom functionality implemented. Some of this (and more of what's been considered/proposed by forks) would be useful for other clients (or other servers) to take advantage of when they know that an instance supports them.

But it's hard to really use a feature that's just informally described in some instance/fork-specific docs or, even worse, only by the implementing code. And it's hard to know what features are supported by an instance. Therefore, it's useful to have specifications describing in detail how these extensions work and explicitly say how an instance can indicate their support of an extension.