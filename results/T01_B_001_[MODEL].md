# Results File Naming Convention

Every raw experimental output is saved as its own file.

## Filename Format

```text
T##_Condition_X_Run_###_Model.md
```

### Components

* **T##** = Test number
* **Condition_X** = Experimental condition
* **Run_###** = Independent replicate number
* **Model** = AI model used

---

## Run Number

The run number is simply the count of independent executions of the same test under the same condition.

* **Run_001** = First time the test is run.
* **Run_002** = Second independent run.
* **Run_003** = Third independent run.
* Continue sequentially for additional independent runs.

---

## Examples

First GPT-5.5 run:

```text
T01__Condition_B__Run_001__GPT-5.5.md
```

Second GPT-5.5 run:

```text
T01__Condition_B__Run_002__GPT-5.5.md
```

Third GPT-5.5 run:

```text
T01__Condition_B__Run_003__GPT-5.5.md
```

First Claude run:

```text
T01__Condition_B__Run_001__Claude.md
```

First Gemini run:

```text
T01__Condition_B__Run_001__Gemini.md
```

---

## Rule

Each file contains **one complete, unedited AI response** from one independent execution of one test under one condition.

Raw outputs must not be modified after they are saved.
