---
comments: true
layout: post
---

A few days ago as I was browsing around the internet, I noticed a new broadcast by the folks over at GitHub. "GPG signature verification - You can now verify GPG signed commits and tags!". (Check out the broadcast [here](https://github.com/blog/2144-gpg-signature-verification).) Well that's cool I thought; I have heard of GPG, or PGP, or something like that. Needless to say, I should look into this more. Besides, who doesn't want to spend Monday night reading about cryptography just for the fun of it?
<!--more-->
Don't answer that.

What I found out is that a quick search of the internet will provide you with numerous sources, more credible than myself, telling you all there is to know about GPG. So instead of telling you the same things as the rest of the internet, I just wanted to provide a brief introduction to GPG, and the links I found useful on the topic.

## What is GPG

GPG is short for GnuPG, or [GNU Privacy Guard](https://www.gnupg.org/). As stated on their website,
> GnuPG is a complete and free implementation of the OpenPGP standard as defined by [RFC4880](https://tools.ietf.org/html/rfc4880) (also known as PGP). GnuPG allows to encrypt and sign your data and communication, features a versatile key management system as well as access modules for all kinds of public key directories. GnuPG, also known as GPG, is a command line tool with features for easy integration with other applications.

### General Information
  * [http://askubuntu.com/questions/186805/difference-between-pgp-and-gpg]()
  * [https://en.wikipedia.org/wiki/Pretty_Good_Privacy]()

### Key Servers
  * key server I uploaded to [https://pgp.mit.edu/pks/lookup?op=vindex&search=0xBC6E708777BBE2D1]().

## Signing your first commit in GitHub
   * [https://www.digitalocean.com/community/tutorials/how-to-use-gpg-to-encrypt-and-sign-messages-on-an-ubuntu-12-04-vps]()


## Useful Links
 * [GnuPG website](https://www.gnupg.org/)
 * [GitHub broadcast about GPG Support](https://github.com/blog/2144-gpg-signature-verification)
 * [Git SCM documentation on signing commits](https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work)
 * [Dated, but an interesting paper on trust within git](https://mikegerwitz.com/papers/git-horror-story)
