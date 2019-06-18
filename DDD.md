# DDD Patterns

Yes, DDD brings its lot of patterns. Brace yourself; you’re on the brink of learning them in a breeze.

You model your business using Entities (the ID matters) and Value Objects (the values matter). You use Repositories to retrieve and store them. You create them with the help of Factories. If an object is too complex for a single class, you’ll create Aggregates that will bind Entities & Value Objects under the same root. If a business logic doesn’t belong to a given object, you’ll define Services that will manipulate the involved elements. Eventually, when the state of the business changes (a change that matters to business experts), you’ll publish Domain Events to communicate the change.

There you are, we’ve talked about DDD patterns!

*DDD 101 — The 5-Minute Tour*
Gérald Croës
Feb 24, 2018
https://medium.com/the-coding-matrix/ddd-101-the-5-minute-tour-7a3037cf53b8
