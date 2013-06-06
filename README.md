mapstory-roadmap
================

This repository is dedicated to maintaining an evolving roadmap for MapStory.

See [roadmap.md](roadmap.md) for the main document.

The [items/](items/) folder contains the actual details on the tasks for the roadmap. 
To read those it is best to just follow the links from the roadmap, as the items will
then be ordered properly.

This roadmap is _not_ a marketing document, other more user/funder
friendly documents can be created for that. The MapStory wiki's 
[Technology Roadmap](http://wiki.mapstory.org/index.php?title=Technology_Roadmap) is currently the best place for that. This is a space for actual
organization of the development work, taking roadmap items and fleshing them out with requirements,
specifications, technology plans, wireframes, issues and more as we move from idea to implementation.

### Adding to the roadmap

To create a new roadmap item add an entry to `roadmap.md` following the same structure as the 
other links, and create a new page under `items/`. You can use this [template](items/template.md)
to copy and paste in to your new item to follow the general structure of other items.

But there are no hard rules for items and the headings, except to make them useful for project
management and developers. 

### Maintaining the roadmap

Every week or two the roadmap should be updated for at least immediate and short term categories. Moving
items from one time frame to another needs to meet some minimum requirements:

##### Immediate Term

Any item listed in [immediate term](https://github.com/MapStory/mapstory-roadmap/blob/master/roadmap.md#immediate-within-4-weeks) 
should have an 'owner' a developer who is working on it, and who expects to finish and deploy to 
production within 4 weeks. This should be placed directly on the main roadmap document. No one should 
own more than one immediate term priority. They can also be working on some short term items, but
the immediate one is their top priority.

Anything in immediate term should also have a 'label' in the issue tracker for it. This tracks all the
bugs and iterations of testing against the topic. The roadmap item should have a link to that label in
its 'issues' section.

##### Short Term

Any item list in [short term](https://github.com/MapStory/mapstory-roadmap/blob/master/roadmap.md#short-1-month---3-months)
should have the people section filled out with who is scheduled to work on it. It should have a complete
set of requirements, and also any relevant wireframes. Wireframes may evolve with testing, but if an 
item needs wireframes it should have them by the time it gets to short term. It should also have a
technology plan of how it will be built - at least some technical thinking should go in to it.

There should be no more than 2 short term items per active developer on the project, and they should
be possible to finish in under a month each.

##### Medium Term

Medium term items should have a real commitment to them, be it funding secured or a volunteer developer
agreed to do all the work. They should have the requirements detailed out to sufficient degree to begin
wireframes or technology plan. Medium term items should also be in accomplishable chunks. If it is a huge
scope in long term than just the first couple milestones should get in to medium term.

##### Long Term and Ideas

These two are more buckets to make sure everything is recorded. Long term should be at least somewhat fleshed
out. Ideas can just be place holders to remind to fill out the requirements. Long term should also ideally be
at least in a funding pitch - the idea to secure funding for it relatively soon.

##### Completed

Completed items should be fully deployed to production. If all the original goals were not accomplished than
another roadmap item can be created to lay out what to do next. But some work towards the end should be 
deployed to production on mapstory.org before marking something as completed.
