@title[fool]

### You fool.

Assume that once the code ran, it will work forever is the **unawareness of unexpected behaviour**.

---

@title[bug]

A bug is nothing but an unexpected behaviour of one’s code that happened over time under a certain condition or group of conditions.
At the end, **our goal is to find ways to detect anomalies or unexpected behaviour on our code over time.**

---

@title[fool]

### Testing

Some current testing methodologies help to improve quality and most of them are good to create software but are not great for ensuring quality over time.
One can spend a lot of human-work implementing test cases for all of that, but at what cost? Both creating and running those will impact directly on the time to market.
Besides, browsers change, device change, servers change… there is just too much that can change, **errors will happen**.

---

@title[Monitoring]

### Monitoring

Monitoring suggests that you first build a system, then **monitor** it for known problems. It tells you about the **known-unknowns** about your system.
Known-unknowns are (relatively) easy (or at least the paths are well-trodden). Unknown-unknowns are hard.

---

@title[Monitoring2]

What happens when users are complaining, but your dashboards are all green? What happens when something new happens and you don’t know where to start looking? In other words, how do you deal with **unknown-unknowns**?

---

@title[unknown-unknowns]

You can’t predict what information you’re going to need to know to answer a question you also couldn’t predict. So you should gather absolutely as much context as possible, all the time.

Monitoring tells you whether a system is working, observability lets you ask why it isn't working. An observable system is one you can fully interrogate

---
@title[Debugging]

### Debugging

It is an iterative process, involving iterative introspection of the various observations and facts reported by the system, making the right deductions and testing whether the theory holds water. **Evidence cannot be conjured out of thin air nor can it be extrapolated from aggregates, averages, percentiles,** historic patterns or any other forms of data primarily collected for monitoring purposes. **Evidence needs to be reported by the systems in the form of highly precise and contextual facts and observations**, which can later be used while debugging to theorize as to why something might be not working as expected.

---

@title[control_teory]

### Observability.

In control theory, **observability** is a measure of how well internal states of a system can be inferred from knowledge of its external outputs.

---

@title[application]

### Application
In practical terms, you don’t need to rely only on tests to define if your code continuously does what it is supposed to do over time.

You can create **checkpoints of success** for your actions and push those to a controller, which is an isolated part of your infrastructure responsible for the collection and reasoning of interaction signals.
