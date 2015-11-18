# opengravestones-data

Open Gravestones is an open source/open data project that will provide public domain ([CC0](https://creativecommons.org/publicdomain/zero/1.0/)) cemetery and burial data that is based on open standards.


## First Principles

### GeoJSON

We use [GeoJSON](http://www.geojson.org) as the primary exchange format for the
gazetteer for two interconnected and complementary reasons:

* It is structured data with the least amount of markup _today_. If someone
creates another markup language with even less scaffolding we might use that
instead but for now GeoJSON is a good happy medium.

* There are lots of tools for working with GeoJSON and, importantly, for
converting it into all the other formats that different people use.

The most atomic piece of information within Open Gravestones is a [Point](http://geojson.org/geojson-spec.html#point) with the following required properties:

* `name`
* `id`


### Open Gravestones is a work in progress

This means a few things:

1. Some (maybe even a lot) of the data will be wrong.

2. Some things are missing.

3. Some (probably most) of the data will change in some way, if only to account for #1.


### Git and GitHub

Don’t get too attached to working with or managing Open Gravestones data
in GitHub (or Git in general). We haven’t quite figured out what the
best way of both distributing the Open Gravestones data and of accepting
corrections or suggestions from community.

Even though the nice people at GitHub continue to do excellent work at
making Git easier for a broader population to use, the reality remains
that Git is a significant barrier to participation for many
people. Absent a more formal decision about an alternative GitHub at
least allows us to point in the general direction of:

* An open and readily distributed dataset that people can download and
work with

* A way for people to contribute corrections (and general nuance)
about a burial

* A way for us to be able to do everything above while still assuring
us a measure of authority around the assertions we make about the data  
* Also a way for us to think about how and where we store an audit
trail (of sorts) for updates to a burial



## Theory

WIP

## Practice

WIP

## License

Crediting Open Gravestones is recommended and linking back to this License is required. 

```
Data from Open Gravestones. <a href="https://github.com/OpenGravestones/opengravestones-data/blob/master/LICENSE">License</a>
```


*Some project guidelines wording copied/borrowed/adapted from https://github.com/whosonfirst/whosonfirst-data*