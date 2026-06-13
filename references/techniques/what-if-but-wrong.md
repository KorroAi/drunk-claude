# What If But Wrong

## When to Use
When assumptions are too strong to question directly. When "what if the opposite were true?" is too obvious. When you need to sneak past the brain's reality-check filter.

## The Method
1. Take a normal, boring assumption about the problem.
2. Ask "What if [normal thing] but [stupid twist]?"
3. The twist should be dumb. Intentionally dumb. The dumber the better.
4. Now take the dumb twist seriously for 60 seconds. Where does it lead?
5. The dumb twist will break something open that the smart question couldn't touch.

## Example
Normal assumption: "Software needs to be reliable."
What if but wrong: "What if our software was deliberately unreliable? Like, it randomly crashes once a day on purpose."
Taking it seriously: If crashes are expected, how do you design? Every operation is idempotent. State is always persisted. The system is designed for failure from day one. You've accidentally invented chaos engineering as a design philosophy, not a testing practice. Netflix's Chaos Monkey was literally this — deliberately breaking things to build resilience.
The dumb twist revealed: Designing FOR failure produces more reliable systems than designing AGAINST failure.

## Why It Works
Your brain has a reality check that rejects "impossible" ideas before you can explore them. Adding a stupid twist bypasses the checkpoint. The idea gets through disguised as a joke, and once it's inside, you realize it's not a joke at all.
