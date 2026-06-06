# kargo-poc
Test kargo promotion tool

I will also use this readme to take notes.

## Continuous deployment Or Preogressive deployment

Some define progressive deployment the fact of incrementally roll out
a new workload. It can be done using kubernetes roll out or at global
scale using networking techniques. In that case progressive deployment
is a set of deployment techniques used to progressively make a new version
of a service available to users.

## Continuous Deployment

Continuous deployment is a method to organise deployments in a way that
they are done any time a new version of a software is made availabe.

A software is made available after it had been validated by the `continous
integration` step.

Said differently, to implement the continuous deployment model deployment
techniques must be used whether they are progressive or not.

But now one question remains, how do we manage what versions are brought
to production in which environment? Maybe we would like to send some versions
only after they remained a certain in dev or staging environment. Maybe for
some internal reasons some environments can be released a certain day of
the week. All of these concerns revolve around promotion issues.

## Software Promotion

The interest of using kargo is to manage complex promotion scenari.
