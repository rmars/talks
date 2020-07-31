# What happens when service mesh maintainers get a taste of their own mesh?

### co-presented with Carol Scott ([@scottcarol](https://github.com/scottcarol))

What happens when a service mesh creator has to eat its own dogfood?
What's it like being on call for a service mesh? Until recently, the
creators of Linkerd have never needed to run Linkerd in production,
simply because they had no production services to maintain. With the
introduction of a SaaS app for Linkerd users that is itself built on
Linkerd, Linkerd maintainers were suddenly on call for Linkerd. In this
talk, we describe several complex bugs we discovered, diagnosed, and
debugged as a result of running Linkerd ourselves, and how this change
in our relationship with our own service mesh changed the nature of
product development.
