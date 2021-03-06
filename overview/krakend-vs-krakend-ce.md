---
lastmod: 2018-10-20
date: 2018-06-23
linktitle: KrakenD vs. KrakenD-CE
description: What is the difference between KrakenD and KrakenD-CE?
notoc: true
menu:
  documentation:
    parent: getting started
title: KrakenD vs. KrakenD-CE
weight: 100
---
If you had a quick look at our git repositories, you might be confused at first, as we have a repository named `krakend` and another one named `krakend-ce`.

# Difference between KrakenD, KrakenD-CE, and Enterprise
**TL;DR;**

- KrakenD is a framework
- KrakenD-CE is an API Gateway ready to use
- KrakenD Enterprise are our professional services to businesses

## KrakenD framework
KrakenD ([repo](https://github.com/devopsfaith/krakend)) is an open-source project created by [@devopsfaith](https://twitter.com/devopsfaith) to accelerate the creation of custom API Gateways. The KrakenD framework provides several components for assembling your API Gateway and can be used in its entirety or just importing it as Go libraries to take only some of the functionality it brings.

Unlike the rest of API Gateways in the space, KrakenD framework aims to bring together Go enthusiasts and professionals to collaborate towards building API Gateways. KrakenD is very modular and lets you replace the components or add new ones (middlewares).

KrakenD focuses on providing a core framework and functionality that a pure API gateway needs, and it keeps it clean and extensible, so that you can create your custom gateway without any trouble.

<a class="btn btn-light" href="https://github.com/devopsfaith/krakend"><i class="fab fa-github"></i> Source code</a>

## KrakenD Community Edition
`KrakenD-CE` ([repo](https://github.com/devopsfaith/krakend-ce)) is a ready-to-use API gateway, assembled the way we think it delivers more value to the general audience. The KrakenD-CE uses the KrakenD framework in its core and extends its functionality by adding in the final binary some of the several [middleware contributions](https://github.com/devopsfaith/krakend-contrib) we thought an API Gateway should have.

KrakenD-CE adds to the KrakenD framework more functionality like logging, service discovery, developer tools, metrics, circuit breaker, rate limiting, OAuth, security and other exciting stuff.

The good news is that we always refer to both things as "KrakenD" :)

<a class="btn btn-secondary btn-circle" href="/download/"><i class="fa fa-download"></i> Download</a>
<a class="btn btn-light" href="https://github.com/devopsfaith/krakend-ce"><i class="fab fa-github"></i> Source code</a>

## KrakenD Enterprise
Customers of the [KrakenD Enterprise](/enterprise) package enjoy the development, consultancy, support, and training services offered by the very same KrakenD creators. As per the software, KrakenD Enterprise users have SaaS functionalities that allow remote management, observability, and other features. There is also more tooling around KrakenD to increase productivity, and enable working with KrakenD in large groups of developers.

**Our commitment to open-source is still in the center of our business**, and this is why our Enterprise solution is built on top of the open-source version.  The Enterprise version uses the same OSS binary and extends it with a great variety of pluggable solutions. We want to make sure that both enterprise and community users have the excellent quality and reliability they are used to.

[Learn more about Enterprise](/enterprise/)