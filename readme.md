# Emojis
😀 😬 😁 😂 😃 😄 😅 😆 😇 😉 😊 🙂 🙃 are everywhere. Be sure to test your inputs with an emoji.

# Big List of Naughty Strings
The Big List of Naughty Strings is an evolving list of strings which have a high probability of causing issues when used as user-input data. This is intended for use in helping both automated and manual QA testing; useful for whenever your QA engineer [walks into a bar](http://www.sempf.net/post/On-Testing1.aspx).

## Why Test Naughty Strings?

Even multi-billion dollar companies with huge amounts of automated testing can't find every bad input. For example, look at what happens when you try to Tweet a [zero-width space](https://en.wikipedia.org/wiki/Zero-width_space) (U+200B) on Twitter:

![](http://i.imgur.com/HyDg2eV.gif)

Although this is not a malicious error, and typical users aren't Tweeting weird unicode, an "internal server error" for unexpected input is never a positive experience for the user, and may in fact be a symptom of deeper string-validation issues. The Big List of Naughty Strings is intended to help reveal such issues.



## Disclaimer

The Big List of Naughty Strings is intended to be used *for software you own and manage*. Some of the Naughty Strings can indicate security vulnerabilities, and as a result using such strings with third-party software may be a crime. The maintainer is not responsible for any negative actions that result from the use of the list.

