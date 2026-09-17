# Empty Verb Extractor — Technical Operational Dispatcher

**Framework Author**: William Fitzpatrick (*Writer Science*)  
**Source Lecture**: [Watch this if you want to IMPROVE the way you write](https://www.youtube.com/watch?v=LAmzkEyt60E)  
**Parent Collection**: [Master Collection](../../kirby-fitzpatrick-writers-collection/SKILL.md) | [Global Help](../../../kirby-help/SKILL.md)  

---

## 1. Cognitive Foundation: Nominalizations & Zombie Nouns

A **nominalization** occurs when an active verb is frozen into a heavy, static noun—typically ending in `-tion`, `-ment`, `-ance`, `-ence`, or `-ity`. 

Because the real action has been converted into an object, the writer is forced to introduce a hollow **"empty verb"** (*make*, *conduct*, *perform*, *provide*, *execute*, *give*) simply to hold the grammatical sentence together.

```text
[Frozen Zombie Noun + Empty Verb: 10 words]
"The worker will perform the execution of the batch job."
                 ^^^^^^^^^^^^^^^^^^^^^^
                 Empty Verb + Nominalization

[Unrolled Active Predicate: 6 words]
"The worker executes the batch job."
             ^^^^^^^^
             Direct Action Verb
```

Unrolling nominalizations restores velocity, eliminates passive voice, and cuts sentence length by 30–50%.

---

## 2. Empty Verb Conversion Registry

Identify the weak verb + noun combination and extract the underlying action:

| Hollow Phrase (Empty Verb + Noun) | Direct Active Predicate |
|---|---|
| `perform the implementation of` | `implement` |
| `conduct an analysis of` | `analyze` |
| `carry out a verification of` | `verify` |
| `make an assumption that` | `assume that` |
| `give consideration to` | `consider` |
| `reach a conclusion regarding` | `conclude` |
| `provide authorization for` | `authorize` |
| `bring about a reduction in` | `reduce` |
| `execute a compilation of` | `compile` |
| `effectuate an optimization on` | `optimize` |
| `have a dependency on` | `depend on` |
| `take into consideration` | `consider` |

---

## 3. Engineering Transformation Workflows

### 3.1 RFC & Architecture Proposals
* **Slop**: *"The consensus engine conducts the coordination of state synchronization across quorum nodes."*
* **Unrolled**: *"The consensus engine synchronizes state across quorum nodes."*

### 3.2 Code Reviews & Refactoring Notes
* **Slop**: *"This function makes an allocation of a 64KB slice and performs an initialization of the headers."*
* **Unrolled**: *"This function allocates a 64KB slice and initializes the headers."*

### 3.3 Bug Diagnosis & Post-Mortems
* **Slop**: *"Under high thread contention, the mutex provides protection for the balance sheet, but brings about an increase in lock latency."*
* **Unrolled**: *"Under high thread contention, the mutex protects the balance sheet but increases lock latency."*

---

## 4. Verification & Self-Audit Checklist

- [ ] Has every instance of *"perform [noun]"* or *"conduct [noun]"* been converted into its root verb?
- [ ] Are nouns ending in `-tion`, `-ment`, and `-ance` checked to see if they should be verbs?
- [ ] Is the primary actor directly attached to the action verb?
- [ ] Have bureaucratic filler constructions like *"take into consideration"* been reduced to *"consider"*?
