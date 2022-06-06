# Pattern Recognition

## Learning Goals

- Understand and explain how to recognize different coding patterns

## Recognizing Patterns

A big aspect of programming is problem-solving. Whether that's bug fixes in
existing code, or problems that businesses come to us to help solve, we are
constantly solving problems. And most of the time, there are more than one
solution to each problem.

As we saw in the previous section, there are many patterns you could leverage to
implement the specific functionality you need to support. So an important skill
to learn is to recognize patterns and apply them appropriately.

Since the problem space is essentially infinite, so are the possible solutions,
and therefore the possible patterns to look for. However, there are a few
methods you should rely on in order to become better at recognizing patterns:

1. Always start with the simplest possible form of implementation you can for
   the specific functionality you are implementing. This will allow you to
   detect complexity as it starts to creep into the system.
2. Make sure your code is both testable and tested. This will give you the
   confidence to re-factor your code as you see specific patterns emerge. Code
   that does not have automated test coverage is much more difficult to
   restructure because it requires a lot of manual work (when it's even
   possible) to validate that the changes do not break previous functionality
3. Lean on the SOLID principles we studied in a previous section. These are
   foundational principles that you can rely on to make sound design decisions
   with your code.
4. Don't be afraid to a) experiment, b) simplify and c) ask questions:
   1. Experiment: if you think something may be doable in a different, better
      way, don't hesitate to test out your theory.
   2. Simplify: a very useful skill for experimentation is to boil down your
      candidate solution to its simplest form and experiment with it "on the
      side". This is because you might be working on a complex system with a lot
      of dependencies and experimentation may be "expensive" (i.e. slow and
      require a lot of work) in that environment. Starting a smaller, standalone
      project where you can iterate more quickly can speed up your
      experimentation cycles.
   3. Ask questions: interrogate every aspect of the code you don't understand.
      This can be done by running tests, adding log statements, asking direct
      questions to people more familiar with the system than you are, ... In
      general, do not assume that something you don't understand makes sense
      because someone else wrote it.
5. Be aware of repeating code, solutions: solving the same problem multiple
   times is a good sign that you should build something that you can leverage in
   the multiple places where this type of problem occurs.
6. Sleep on it: it pays to step away from your code for some time and look at it
   with a fresh pair of eyes after some rest to give you a new perspective.
7. Collaborate: also in the service of getting a different perspective,
   collaborate with others around you so they can lend you their perspective and
   look at the problem you are tackling from a different angle.

Beyond these general strategies, there are specific "code smells" you should
also be on the lookout for. More on this in the following section.
