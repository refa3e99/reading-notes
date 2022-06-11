## How to use Random Module
Randint
If we wanted a random integer, we can use the randint function Randint accepts two parameters: a lowest and a highest number. Generate integers between 1,5. The first value should be less than the second.
Choice 
The choice function can often be used for choosing a random element from a list.
Shuffle
The shuffle function, shuffles the elements in list in place, so they are in a random order.
Randrange
Generate a randomly selected element from range(start, stop, step)

## What is Risk Analysis
The probability of any unwanted incident is defined as Risk. In Software Testing, risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test.
possible risks we could encounter :
- Use of new hardware
- Use of new technology
- Use of new automation tool
- The sequence of code
- Availability of test resources for the application

there are certain risks that are unavoidable
- The time that you allocated for testing

- A defect leakage due to the complexity or size of the application

- Urgency from the clients to deliver the project

- Incomplete requirements

risk magnitude indicators:

**High**: means the effect of the risk would be very high and non-tolerable. The company might face loss.

**Medium**: it is tolerable but not desirable. The company may suffer financially but there is a limited risk.

**Low**: it is tolerable. There lies little or no external exposure or no financial loss.

## Test Coverage

If you make a certain level of coverage a target, people will try to attain it. The trouble is that high coverage numbers are too easy to reach with low quality testing. At the most absurd level you have AssertionFreeTesting. But even without that you get lots of tests looking for things that rarely go wrong distracting you from testing the things that really matter.

Like most aspects of programming, testing requires thoughtfulness. TDD is a very useful, but certainly not sufficient, tool to help you get good tests. If you are testing thoughtfully and well, I would expect a coverage percentage in the upper 80s or 90s. I would be suspicious of anything like 100% - it would smell of someone writing tests to make the coverage numbers happy, but not thinking about what they are doing.
