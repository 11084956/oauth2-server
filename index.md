---
layout: default
title: Introduction
---

# Introduction

[![Author](http://img.shields.io/badge/author-@alexbilbie-yellow.svg?style=flat-square)](https://twitter.com/alexbilbie)
[![Source Code](http://img.shields.io/badge/source-thephpleague%2Foauth2--server-blue.svg?style=flat-square)](https://github.com/thephpleague/oauth2-server)
[![Latest Version](http://img.shields.io/packagist/v/league/oauth2-server.svg?style=flat-square)](https://github.com/thephpleague/oauth2-server/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)<br />
[![Build Status](https://img.shields.io/travis/thephpleague/oauth2-server/master.svg?style=flat-square)](https://travis-ci.org/thephpleague/oauth2-server)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/thephpleague/oauth2-server.svg?style=flat-square)](http://oauth2.thephpleague.com/master/)
[![Quality Score](https://img.shields.io/scrutinizer/g/thephpleague/oauth2-server.svg?style=flat-square)](https://scrutinizer-ci.com/g/thephpleague/oauth2-server)
[![Total Downloads](https://img.shields.io/packagist/dt/league/oauth2-server.svg?style=flat-square)](https://packagist.org/packages/league/oauth2-server)

This library makes working with OAuth 2.0 trivial. You can easily configure an OAuth 2.0 server to protect your API with access tokens, or allow clients to request new access tokens and refresh them.

It supports out of the box the following grants:

* Authorization code grant
* Client credentials grant
* Resource owner password credentials grant
* Refresh grant

You can also define your own grants.

In addition it supports the following token types:

* Bearer tokens
* MAC tokens
* JSON web tokens (coming soon)

## Changelog

The changelog can be viewed here - [https://github.com/thephpleague/oauth2-server/blob/master/CHANGELOG.md](https://github.com/thephpleague/oauth2-server/blob/master/CHANGELOG.md).

The latest release is `4.1.3` (released 2015-03-22):

* Docblock, namespace and inconsistency fixes (Issue #303)
* Docblock type fix (Issue #310)
* Example bug fix (Issue #300)
* Updated league/event to ~2.1 (Issue #311)
* Fixed missing session scope (Issue #319)
* Updated interface docs (Issue #323)
* `.travis.yml` updates

## Questions?

This library was created by Alex Bilbie. Find him on Twitter at [@alexbilbie](https://twitter.com/alexbilbie).
