<!-- Answers to the Short Answer Essay Questions go here -->

1. In Mocha, what are the differences between `before`, `after`, `beforeEach`, and `afterEach`? When do they run? What are they used for?

All four methods are meant to sort of sandbox your testing environment during the time they are invoked.  before / after will deal with a single unit test while the latter two will encompass an entire codeblock

2. What is the point of Test Driven Development? What do you personally think about this approach?

TDD allows developers to make apps that have less bugs, and have solid functionality by flexing the app through various tests, the end result is much higher confidence from botht the developer as well as any potential users. I think this approach is necessary when creating an extensive app such as an operating system or something that may go into production. It is an essential step in producing a reliable product, which is what determines good from bad.

3. What is a `spy` in `sinon`? How do we use it to effectively test a `callback`?

A spy in sinon can be used as an anonymous function or to wrap methods that already exist in the system under test.



**** To Run *****
GET                  /api/game/get          |                   |
POST                 /api/game/create       |title, genre       |
PUT                  |/api/game/update      |id*, title         |
DELETE               |/api/game/destroy:id   |id*               |