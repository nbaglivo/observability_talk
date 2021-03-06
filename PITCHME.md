@title[fool]

### Don't fool yourself.

To assume that once the code ran, it will work forever is the **unawareness of unexpected behaviour**.

---
@title[fool_img]

![fool](https://cdn-images-1.medium.com/max/1600/1*V7JW8dew6Mbekr2InDRQtQ.jpeg)

---

@title[bug]

A bug is nothing but an unexpected behaviour of one’s code that happened over time under a certain condition or group of conditions.

You can predict that a determined bug will happen.

---

@title[testing]

### Sure, we do have testing but...

One can spend a lot of human-work implementing test cases **trying** to cover all the possible scenarios **that you can think of**.

But at what cost? Both creating and running those will impact directly on the time to market.

---

@title[testing2]

Besides, browsers change, device change, servers change… there is just too much that can change.

---

@title[errors_happend]

### Embrace the fact that

So, let's assume it... **errors will happen**...

---
@title[all_fine_dog]

... No matter how well you test your stuff,

![fool](https://cdn-images-1.medium.com/max/1600/1*nL8P6-ZwmXUDd-hD9f6NoA.png)

---
@title[Debugging]

### So, you will need to debug

It will involve iterative introspection of the various observations and facts reported by the system, making the right deductions and testing whether the theory holds water.

---

@title[Debugging2]

### And we'll need evidence

Evidence cannot be conjured out of thin air nor can it be extrapolated from aggregates, averages, percentiles. It needs to be reported by the systems in the form of highly precise and contextual facts and observations.

---

@title[control_teory]

### Observability.

In control theory, **observability** is a measure of how well internal states of a system can be inferred from knowledge of its external outputs.

---

@title[obeservability_for_mortals]

### Wait, what?.

In other words, **observability** is a property of your system, you can have a low degree of observability, some degree or even high degree.

It allows you to ask why it isn't working. An observable system is one you can fully interrogate.

---

@title[Monitoring]

### Monitoring.

It gives you some degree of observability, but it only allows you to see things that you predicted that could happen.

---

@title[Monitoring2]

Monitoring suggests that you first build a system, then **monitor it for known problems**. It tells you about the **known-unknowns** about your system.

---

@title[Known-unknowns]

### Known-unknowns

Known-unknowns are problems where you know what happened but you aren't sure how it happen. Example: expected errors.
They are (relatively) easy (or at least the paths are well-trodden). Unknown-unknowns are hard.

---

@title[unknown-unknowns2]

But what happens when users are complaining, but your dashboards are all green?
What happens when something new happens and you don’t know where to start looking?
In other words, how do you deal with **unknown-unknowns**?

---

@title[unknown-unknowns]

You can’t predict what information you’re going to need to know to answer a question you also couldn’t predict.

---

@title[unknown-unknowns2]

So you should gather absolutely as much context as possible, all the time.

---

@title[application]

### Application
In practical terms, you don’t need to rely only on tests to define if your code continuously does what it is supposed to do over time.

---

@title[checkpoints]

### Checkpoints of success

You can create this checkpoints for your actions and push those to a controller, which is an isolated part of your infrastructure responsible for the collection and reasoning of interaction signals.
