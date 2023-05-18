# Title
Improve development quality

# Context
We need to improve the trust of the different stakeholder.
Therefore, we must provide a list of good practices to keep in mind in our development journeys.

# Decision
We agreed to introduce:

## Global
- every work MUST be reviewed by, at least, one other developer that the one that produced the work
- you MUST cover your code with unit test but not be too much focus on it
- main branch on GIT MUST be protected and CAN NOT be deleted
- build & unit tests pipeline must be triggered in opened pull requests
- build & unit tests & integration tests (if existing) must be triggered for every commits on main
- nobody SHOULD push on main branch (some exceptions could be tolerated if everyone is agreed)
- you SHOULD apply [SOLID principle](https://alexsoyes.com/solid/#s-single-responsibility-principle-srp)
- anyone MUST try to keep things [KISS](https://en.wikipedia.org/wiki/KISS_principle)
- [You Ain't Gonna Need It](https://fr.wikipedia.org/wiki/YAGNI) principle SHOULD be kept in mind BUT not too strictly apply
- [Do not Repeat Yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) principle SHOULD be followed BUT not too strictly apply
- you SHOULD try to embrace [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html) (Hexagonal or Oignon Architecture)
- you SHOULD keep in mind [DDD concepets]()
- avoid usage of acronyms as much as possible 
- usage of business/functional wording as much as possible 
- you SHOULD focus you code on business rules, not technical choices to support them
- you SHOULD try to drive your code by test cases if provided
- you SHOULD apply the famous boy scout rule : you SHOULD leave the code cleaner than you found it

## C# Ecosystem
- when using LINQ, you MUST NOT use one letter within the lambda, you MUST use a word that describe what you are manipulating
