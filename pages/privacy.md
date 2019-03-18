---
layout: page
title: Privacy
permalink: /privacy/
weight: 4
---
# Privacy and us
We don't collect or share any kind of information about you.

## Cookies
As you probably already now, [HTTP Cookies](https://en.wikipedia.org/wiki/HTTP_cookie), are files downloaded on our computers when we visit a website.
They are standard in web development because they provide a kind of memory for websites and can be used for a number of things such as counting visitors,
remember our preferences, forms filled or products in our shopping basket, etc.

There are harmless cookies that can be  only accessible from the same domain of the page we are visiting. But also,
there are kind of cookies, called [third-party cookies](https://en.wikipedia.org/wiki/HTTP_cookie#Third-party_cookie),
set by a website other than the one we are currently on. This kind of cookies can be used for right things,
such as with websites that have follow or like buttons, blogs with comments served through a separate system, show us advertisement banners, etc.
But they also can be used for tracking us. They can be usually used for analyze network traffic, and that is good,
but also for tracking us by advertising networks, search engines or social networks that we may not expect.

According with the official standards, browsers should be block third party cookies by default, but almost all permit them.

> When it makes an unverifiable transaction, a user agent MUST disable
> all cookie processing (i.e., MUST NOT send cookies, and MUST NOT
> accept any received cookies) if the transaction is to a third-party
> host.
>
> &mdash; _D. Kristol, L. Montulli_
> [RFC 2965: HTTP State Management Mechanism, p. 13][RFC 2965]


[RFC 2965]: https://www.ietf.org/rfc/rfc2965.txt

The good news is that all main browsers provide ways to control cookies at any time, allowing, blocking or removing them.
Please refer to your browser's help for further information.

As you can notice, viewing the information about this site on your browser, there is a couple of cookies, none of them third-party cookies,
but same-site cookies.

{% include cookies.html title="Cookies in this site" source=site.data.cookies %}
