<!-- .slide: data-background-image="images/RH_NewBrand_Background.png" -->
## DevOps Culture and Practice <!-- {.element: class="course-title"} -->
### DDD, BDD & TDD (& DDT) <!-- {.element: class="title-color"} -->
TL500 <!-- {.element: class="title-color"} -->



<div class="r-stack">
<div class="fragment fade-out" data-fragment-index="0" >
  <h2>Open Practice Library</h2>
  <img src="images/opl-complete.png">
</div>
<div class="fragment current-visible" data-fragment-index="0" >
  <h2>Testing Testing Testing 🔨🔨</h2>
  <a target="_blank" href="https://openpracticelibrary.com/practice/test-automation/">
  <img src="images/opl-foundation.png">
  </a>
</div>
</div>



<!-- .slide: id="ddd" -->
## Domain Driven Design



### Domain Driven Design
#### _What Is It?_
Domain-driven design (DDD) is an approach to developing software for complex 
needs by deeply connecting the implementation to an evolving model of the core 
business concepts.



![DDD](images/bdd-tdd/ddd.png)



### Domain Driven Design
#### _How Does It Help?_
* Placing the project's primary focus on the core domain and domain logic
* Basing complex designs on a model of the domain
* Initiating a creative collaboration between technical and domain experts to iteratively 
refine a conceptual model that addresses particular domain problems
* Bridge the gap between domain experts and developers by using the same language to 
create the same understanding



<!-- .slide: id="bdd" -->
## Behavior Driven Development



### Behavior Driven Development
#### _What Is It?_
Behavior-Driven Development (BDD) is a Test-First, Agile Testing practice 
that provides Built-In Quality by defining (and potentially automating) tests 
before, or as part of, specifying system behavior.



![BDD-Cartoon](images/bdd-tdd/bdd.png)



![BDD](images/bdd-tdd/bdd.jpg)



### Behavior Driven Development
#### _How Does It Help?_
* Creates a shared understanding of requirements between 
the business and the Agile Teams
* Helps guide development, decrease rework, and increase flow
* Creates business-facing scenarios that attempt to describe the behavior of a 
Story, Feature, or Capability from a user's perspective.



#### Example Mapping
Based on the idea that multiple examples of specific cases convey information better than a single bad abstraction of a concept.
![example-mapping](images/bdd-tdd/example-mapping.jpg)



#### Example Mapping - World Health Organisation
![example-mapping-who](images/bdd-tdd/example-mapping-who.jpg)



#### Example Mapping story A/Cs and test cases
![example-mapping--test-casess](images/bdd-tdd/example-mapping-to-test-casess.png)



<!-- .slide: id="tdd" -->
## Test Driven Development



### Test Driven Development
#### _What Is It?_
Test Driven Development (TDD) is a software development process that relies on
the repetition of a very short development cycle.
Requirements are turned into test cases, where the software is developed to pass
the tests.

This practice is particularly powerful when combined with
**Continuous Integration**.



![TDD-Cartoon](images/bdd-tdd/tdd.png)



![TDD](images/bdd-tdd/tdd.jpg)



### Test Driven Development
#### _How Does It Help?_
* Creates a detailed specification for the code
* Gives fast feedback
* Indicates whether the last change has broken previously working code
* Allows the design to evolve and adapt as understanding of the problem evolves



![TDD](images/bdd-tdd/TDD_Lifecycle.png)



### DDD & BDD & TDD
![TDD](images/bdd-tdd/ddd-bdd-tdd.jpg)



<!-- .slide: id="revenge-automated-testing-part-2" -->
## Revenge of the Automated Testing
### Part 2
Test Driven Development (TDD) in LEGO

Credit to [Gargoyle Software](http://www.gargoylesoftware.com/ex/lego_tdd)



### Intent
Demonstrate the concepts behind TDD.

How we write the test before we write code and how that forces our design to emerge.



### TDD Lifecylce
![TDD-Simplified](https://i0.wp.com/s3.amazonaws.com/production-wordpress-assets/blog/wp-content/uploads/2017/04/11100523/TDD.jpg?zoom=2&fit=400%2C237&ssl=1)

Red - Write a small test that fails <!-- {.element: class="fragment" style="color: red" data-fragment-index="1"} -->

Green - Do the minimum to make the test pass <!-- {.element: class="fragment" style="color: green" data-fragment-index="2"} -->

Refactor - Eliminate duplication & make it beautiful <!-- {.element: class="fragment" data-fragment-index="3"} -->



### TDD Lifecycle
![Circle of life](https://media.giphy.com/media/DvMHwFYLVHlZe/giphy.gif)  <!-- {.element: class="" style="height:450px"} -->



### Prepare your environment
Our program is made of Lego. Get your equipment ready for coding
![lego-space](images/bdd-tdd/lego-space.jpeg)



### 2 Simple Rules for Lego TDD
KISS - Keep It Simple Stupid  <!-- {.element: class="fragment"  data-fragment-index="1"} -->

YAGNI - You Ain't Gonna Need It!  <!-- {.element: class="fragment"  data-fragment-index="2"} -->

![simple-house](images/bdd-tdd/simple-lego-home.jpg)  <!-- {.element: class="fragment"  data-fragment-index="1" style="height:250px"} -->
![complex-house](images/bdd-tdd/complex-home.jpeg)  <!-- {.element: class="fragment" style="height:250px"  data-fragment-index="2"} -->



### Pair Builds
![pairs](https://i.ebayimg.com/images/g/pfgAAOSw3NtbJ57f/s-l1600.jpg) <!-- {.element: class="" style="height:450px"} -->



### The Steps
1. One person in the pair will write a test, in the form of a question, on a sticky note and place it on the table. For example "Is there a person?". <!-- {.element: class="fragment"  data-fragment-index="1"} -->
2. The other person will then implement something in LEGO that passes that test. <!-- {.element: class="fragment" data-fragment-index="2"} -->
3. When the first person is satisfied that the test is passing, they switch positions. <!-- {.element: class="fragment" data-fragment-index="3"} -->
4. Now the second person writes a test and puts it on the table and the first person implements in LEGO. <!-- {.element: class="fragment" data-fragment-index="4"} -->



### Some example tests

![TDD](images/bdd-tdd/lego-tdd-1.jpg) <!-- {.element: class="inline-image"} -->
- Is there a person in the program? <!-- {.element: class="fragment" data-fragment-index="1"} -->
- Is there a house in the program? <!-- {.element: class="fragment" data-fragment-index="2"} -->
- Is there a window on a wall of the house? <!-- {.element: class="fragment" data-fragment-index="3"} -->
- Is it true that the house is taller than the person? <!-- {.element: class="fragment" data-fragment-index="4"} -->
- The house is wider than the person? <!-- {.element: class="fragment" data-fragment-index="5"} -->
- Is it true that the house has 2 connected walls <!-- {.element: class="fragment" data-fragment-index="6"} -->
- Can the person enter the house? <!-- {.element: class="fragment" data-fragment-index="7"} -->



### The Game Begins!

 - The business requirement is to include the following in our program:
       1. a person
       2. an animal
       3. a plant
       4. a vehicle
       5. a building.
 - There may only be one "broken" test at a time. All previous tests must continue to pass. <!-- {.element: class="fragment" data-fragment-index="1"} -->
 - Nothing must be built in LEGO if there wasn't a failing test that forced that to exist. <!-- {.element: class="fragment" data-fragment-index="2"} -->
 - After each test is passing, the people switch roles. <!-- {.element: class="fragment" data-fragment-index="4"} -->



### Debrief
<!-- speaker info
Sometimes people will build something new that breaks an existing test and they either won't have noticed or won't have cared. If this is the case then discuss why tests must always be passing.

Generally not everyone will have done this. They'll be so busy creating interesting requirements that they don't have time to build the five things that the customer actually asked for. Discuss this.

Have each pair demo two or three of their features. Have them read out the test first and then point out how that was implemented in their model. Stress the fact that if there isn't a test for a given feature, we don't care about it.
Many times people will have built cool things that they didn't have tests for. We stress again that in TDD, we don't build anything until the test has forced us to do that.
 -->
 - What did you observe? How did that feel?
 - Did everyone complete the five base requirements listed above?
 - Are all tests currently passing?



### Team Builds
![teams-at-work](https://www.businessdevelopmentcompany.co.nz/wp-content/uploads/2017/07/Being-a-team-member-768x510.jpg)



### The Game Begins Again!

![TDD](images/bdd-tdd/lego-tdd-2.png) <!-- {.element: class="inline-image" style="height:500px"} -->
 - As a table; Pick a project to build. Projects should be something complex that has lots of different kinds of things in it. Some examples if you're stuck could include _A Zoo_, _Shopping Center_, _a spaceship_ or _a city_.
 - All tests at the table must continue to pass at all times, regardless of which pair wrote them.  <!-- {.element: class="fragment" data-fragment-index="1"} -->
 - This time is that the implementation has to be integrated with the main project in the center of the table. <!-- {.element: class="fragment" data-fragment-index="2"} -->



### Debrief

<!-- Speaker notes
What did you observe?
A wide open question like this will often bring out observations we didn't anticipate.
Look around your table. Are all the tests still passing? If not, discuss.
Often people will now realize that something is broken and they hadn't noticed. This can lead into a discussion of continuous integration servers.
Are there tests that you should have that are missing?
Once a team built a zoo and then didn't complete the fencing around the lion enclosure. Perhaps they'd needed a test to ensure the lions couldn't get out to eat all the other animals.
Did you have any conflicts where a new feature from one pair broke a test from another? What did you do about that?
Was your final design different than you expected? Discuss.
 -->
 - What did you observe?
 - Look around your table. Are all the tests still passing?
 - Are there tests that you should have that are missing?
 - Did you have any conflicts where a new feature from one pair broke a test from another? What did you do about that?
 - Was your final design different than you expected?



## A Little Competition



<!-- .slide: data-background-image="images/chef-background.png", class="white-style" -->
### Related & Used Practices
- [Test Driven Development](https://openpracticelibrary.com/practice/test-driven-development/)
- [Continuous Integration](https://openpracticelibrary.com/practice/continuous-integration/)
- [Example Mapping](https://openpracticelibrary.com/practice/example-mapping/)
