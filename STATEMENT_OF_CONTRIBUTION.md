# Statement of contribution
### Erik:
wrote tests for extra coverage, tried to implement, added uml diagrams, fixed some tests.

### Boyan:
Refactored SessionWrapper and SessionFactory, added UAFallbackAuth for retry. Fixed some tests.

### Villiam
I formulated the requirements and initialy scoped out our project. I also solved ALOT of tests that were not passing after our first implementation. Added the requests compatability shim mock for mocking out requests instead of httpx that took failing tests from 199 to 57. 

### Willliam
Wrote documentation, updated dependencies, changed some tests in conftest.py
#### Alrik
Wrote the http wrapper, fixed bugs relating to lazy loading of request library in different modules fixed docs build failing and other bugfixes.
