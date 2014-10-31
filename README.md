# Deploy Firefox Accounts (FxA)

A [Salt Stack formula](http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html) to deploy FxA in one or many VMs.

## Context

This will be the Salt stack formula that WebPlatform.org will use to deploy [accounts.webplatform.org](https://accounts.webplatform.org).


## STATUS

At this time, WebPlatform.org deploys FxA manually. It isn’t ready for production deployment. This formula is intended to deploy FxA components for any environment (local development w/ Vagrant, or on publicly available servers).

## Should support

* Ubuntu 14.04
* A way to declare which git repos and branch are to be deployed
* NGINX
