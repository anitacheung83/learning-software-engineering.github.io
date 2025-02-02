## Resources for Development Process


### Git Flow:
#### Git Branching
* [Learn Git Branching](https://learngitbranching.js.org/)
  * **Learn Git Branching** is an interactive websites that teaches git branching concepts/commands through visualization. The website cover local and remote Git concepts, including cherry-picking, rebasing, fetching, pushing etc. The interactive learning experience allows CSC301 student learn by doing challeges and exercises. The visualization helps student understand abstract git concepts, including git history and git branching. Thus, Learn Git Branching is a great resource for anyone looking to learn Git and improve their Git skills.
  * Feel free to checkout their GitHub: [Learn Git Branching GitHub](https://github.com/pcottle/learnGitBranching), as they have provided some website instruction including levels and sandbox mode. You can also contribute to it if you are interested.
* Main
  * ```git commits -m "[MESSAGE]"```
     * Records a snapshot of the state of the repository
     * When commit is made, you stage the changes and then commit them
     * The command create a new commit that includes the changes you have made, along with a messages that describe the changes
     * Maintain a history of commits that were made (Use ```git log``` to see full commit history)
  * ```git branch [BRANCH NAME]```
     * Pointers to specific commit
     * Developer can work on a specific feature or bug fix on a branch before merging with the main branch
  * ```git checkout [BRANCH NAME]```
     * Move to [BRANCH NAME] 
     * ```git checkout -b [BRANCH NAME]```: Create a new branch and check it out at the same time 
  * ```git merge [BRANCH NAME]```
     * Combining branches into a single branch
     * Merging the current branch with [BRANCH NAME]
     * Three possible outcomes, including fast forward merge, recursive merge, merge conflict
  * ```git rebase [BRANCH NAME]```
     * Another way to combine work between branches
     * Move the entire branch to [BRANCH NAME], apply changes on the current branch to [BRANCH NAME]
     * Produce a linear sequence of commit, commit history will be cleaner

* Remote
  * ```git fetch```
     * Download commits from remote that are missing in local repository
     * Note that it does not change any of your local files
  * ```git pull```
     * fetching remote changes and merging it to the current state


### [Django Project Deployment: AWS, Vercel, and Railway](./Development_Process/Django_Deployment_AWS_Railway_Vercel.md)
### [Automated Frontend Deployment with Vercel](./Development_Process/Frontend_Automated_Deployment_Vercel.md)
### [Quality Assurance Testing](./Development_Process/QA_testing.md)
- [Automated Testing](./Development_Process/Automated_Testing.md)
### [Getting Started With Docker](./Development_Process/Docker.md)


## Build requirements
### [Requirements.txt](./Development_Process/Build_Requirements/Requirements_txt.md)

## React Testing Library
### [React Testing Library](./Development_Process/React_Testing_Library.md)

## SOLID PRINCIPLES: 

SOLID is a mnemonic acronym that represents a set of five very important software development principles which lead to code that is easier to read, maintain, and extend, leading to higher-quality software that is easier to evolve over time.

The SOLID principles are:

 - Single Responsibility Principle (SRP): A class should only have one cause to change, according to the Single Responsibility Principle (SRP). According to this theory, a class ought to have just one duty, which implies that there ought to be just one motivation for change. This makes the class more understandable, maintainable, and reuseable as well as more flexible.

 - Open/Closed Principle (OCP): Software entities (classes, modules, functions, etc.) should be available for extension but closed for modification, according to the available/Closed Principle (OCP). According to this principle, a system should be able to introduce new functionality without requiring changes to the existing code. Interfaces, polymorphism, and generalization are used to accomplish this.

 - Liskov Substitution Principle (LSP): Subtypes must be able to be used in place of their parent types. According to this concept, it should be possible to swap out objects from a superclass for objects from a subclass without having any negative effects on the program's correctness. This necessitates abiding by the superclass's compact.

 - Interface Segregation Principle (ISP): Clients should not be forced to depend on interfaces they do not use. This principle states that a client should not be forced to implement an interface if it does not use all of the methods defined by the interface. This helps to avoid the creation of fat interfaces, which are interfaces that contain more methods than the client needs.

 - Dependency Inversion Principle (DIP): High-level modules should not depend on low-level modules. Both should depend on abstractions. Abstractions should not depend on details. Details should depend on abstractions. This principle suggests that classes should depend on abstractions rather than concrete implementations, which makes the system more flexible and easier to modify.
 
 
 ## Resource that gives examples of the uses cases of SOLID principles
  LINK :  https://www.youtube.com/watch?v=_jDNAf3CzeY 

