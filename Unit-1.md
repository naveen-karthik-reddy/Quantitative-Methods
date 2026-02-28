# 1.1 Introduction
- **Probability** is the possibility of an uncertain event occurring.
- Uncertainity simply means not knowing what will happen
- Ex: Tossing a coin, Rolling a dice, pick a card from deck.


# 1.2 Standard Terms Used in Probability

## Standard Terms
### 1. Experiment

In probability, an **experiment** is a well-defined process or action that produces an outcome, where the exact result is uncertain but all possible outcomes are known in advance.

**Examples:**
- Tossing a coin  
- Throwing (rolling) a die  

### 2. Event / Outcome

An **event** or **outcome** is the result of an experiment.

**Example:**
- Getting a six when rolling a die  
- Getting head of tossing a coin.

### 3. Sample Space

The **sample space** is the set of all possible outcomes of a random experiment. It is usually denoted by **S**.

**Example:**
- When rolling a die:  
  \[
  S = \{1, 2, 3, 4, 5, 6\}
  \]


## Probability of event E occurring P(E)
````
P(E) = Number of favorable outcomes/Total number of possible outcomes
````

### Example: What's the probability of getting head on tossing a coin.
Faviourable outcome - {Head}

No of faviourable outcomes - 1

Total outcomes - {Head, Tail}

Total outcomes count- 2

P(E) here E is represents getting head

P(E) = Number of favorable outcomes/Total number of possible outcomes

P(E) = 1/2 = 0.5

---
### Example 2: Even Number on a Dice

Experiment: Roll a fair six-sided dice.

Sample Space (S):
{1, 2, 3, 4, 5, 6}

Event (A): Getting an even number

Favorable Outcomes:
{2, 4, 6}

Number of favorable outcomes = 3  
Total number of possible outcomes = 6  

Probability of getting an even number:

P(A) = 3 / 6 = 1 / 2

---
### Example 3: Face Card from a Deck

Experiment: Draw one card from a standard deck of 52 cards.

Total cards in deck = 52

Face Cards:
Jack (J), Queen (Q), King (K)

Each suit (Hearts, Diamonds, Clubs, Spades) has 3 face cards.

Total face cards = 3 × 4 = 12

Event (B): Getting a face card

Probability of getting a face card:

P(B) = 12 / 52 = 3 / 13
---
# Cards
<img width="3008" height="1361" alt="image" src="https://github.com/user-attachments/assets/bd26c750-433d-407c-862a-865205a29971" />

# 🎴 Basic Playing Cards (Standard Deck)

A **standard deck** has:

```
52 cards
```

---

## 1️⃣ Suits (4 Types)

There are **4 suits**, each with 13 cards:

- ♠ Spades  
- ♥ Hearts  
- ♦ Diamonds  
- ♣ Clubs  

So:

```
4 suits × 13 cards = 52 cards
```

## 2️⃣ Ranks (Card Values)

Each suit contains the same 13 ranks:

```
A, 2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K
```

So in the full deck:

- 4 Aces  
- 4 Kings  
- 4 Queens  
- 4 Jacks  
- 4 of every number  

# 🧠 Simple Probability Examples with Cards

When you pick **1 card randomly**, every card has equal chance.

```
Total possible outcomes = 52
```

## Example 1: Probability of getting a King

There are 4 Kings.

```
P(King) = 4 / 52 = 1 / 13
```

## Example 2: Probability of getting a Heart

There are 13 Hearts.

```
P(Heart) = 13 / 52 = 1 / 4
```

## Example 3: Probability of getting King of Hearts

Only one such card exists.

```
P(King of Hearts) = 1 / 52
```

# 🎯 Important Concepts

## 🔹 Face Cards

Face cards are:

- Jack (J)
- Queen (Q)
- King (K)

Total face cards:

```
3 per suit × 4 suits = 12
```

## 🔹 Red Cards

Red suits are:

- Hearts
- Diamonds

```
13 + 13 = 26 red cards
P(Red) = 26 / 52 = 1 / 2
```

## 🔹 Black Cards

Black suits are:

- Spades
- Clubs

```
26 black cards
```

# 1.3 Approaches of Probability

1. Classical (Theoretical) Probability  
2. Empirical (Experimental) Probability  
3. Subjective Probability  

## 1️⃣ Classical Probability (Theoretical Approach)

### Core Idea
Probability is derived from **mathematical reasoning**, assuming all outcomes are **equally likely**.

````
P(E) = Number of favourable outcomes / Total number of possible outcomes
````

### Key Assumption
- Every outcome has equal probability.
- No real-world data is required.
- Purely model-based.

### Typical Use Cases
- Dice rolls  
- Coin tosses  
- Card games  
- Random draws  

## 2️⃣ Empirical Probability (Experimental Approach)

### Core Idea
Probability is calculated using **actual observed data** from repeated trials.

````
P(E) = Number of times event occurs / Total number of trials
````
### Key Characteristics
- Data-driven
- Based on historical records
- Improves with more observations
- Reflects real-world uncertainty

### Example
If a machine fails 12 times in 300 days:

P(Failure) = 12 / 300 = 0.04

As the number of trials increases, empirical probability approaches true probability  

## 3️⃣ Subjective Probability

### Core Idea
Probability is based on **personal judgment, expertise, intuition, or belief**, not necessarily on data.

### Characteristics
- Opinion-based
- Expert-driven
- Context-sensitive
- Can vary between individuals

### Business Example
A marketing manager estimates:
- 70% chance campaign increases sales  

Based on:
- Past experience  
- Market trends  
- Customer feedback  

### Limitation
- Not objectively calculated
- May differ across experts
- Can be biased


# 1.4 Addition Theorm

The addition theorem of probability is used to find the probability that **at least one** of two events (A or B) occurs.

For any two events:

P(A ∪ B) = P(A) + P(B) − P(A ∩ B)

The term P(A ∩ B) is subtracted to avoid double-counting the outcomes common to both events.

P(A ∪ B) represents the probability that:
- Event A occurs, OR
- Event B occurs, OR
- Both A and B occur.

P(A ∩ B) represents the probability that:
- Both event A and event B occur at the same time.

### Example 1: Non-Mutually Exclusive Events (Dice)

Experiment: Roll a fair six-sided die.

Sample Space:
{1, 2, 3, 4, 5, 6}

Let:
A = Getting an even number = {2, 4, 6}
B = Getting a number greater than 3 = {4, 5, 6}

P(A) = 3/6  
P(B) = 3/6  

Common outcomes (A ∩ B):
{4, 6}

P(A ∩ B) = 2/6

Using the formula:

P(A ∪ B) = P(A) + P(B) − P(A ∩ B)

P(A ∪ B) = 3/6 + 3/6 − 2/6  
P(A ∪ B) = 4/6 = 2/3

So, the probability of getting an even number OR a number greater than 3 is 2/3.

### Example 2: Odd and Even (Mutually Exclusive)

Experiment: Roll a fair die.

Sample Space:
{1, 2, 3, 4, 5, 6}

Let:
A = Odd numbers = {1, 3, 5}  
B = Even numbers = {2, 4, 6}

P(A) = 3/6  
P(B) = 3/6  

A ∩ B = ∅  
P(A ∩ B) = 0  

Since a number cannot be both odd and even, they are mutually exclusive.

Formula:
P(A ∪ B) = P(A) + P(B)

P(A ∪ B) = 3/6 + 3/6  
P(A ∪ B) = 6/6 = 1


# 1.5 Common Event Terms and their meaning

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/be3cd53c-7eeb-434d-9c3d-85242d97b1a4" />


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/d7c1defd-7f9c-45ec-bab4-895b2afb259d" />


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/40dd539b-eeb3-429b-a250-6db2fce0f611" />


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4bd2dc15-bee5-426b-acf9-e21b3a48cab4" />


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/1b495a79-e931-445d-a3ed-0f1fa27888db" />


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/6735bd8d-6057-4d4c-9f76-bd5d163680a1" />


# Multiplication Theorem of Probability

The **Multiplication Theorem** is used to find the probability that **two events occur together**.

In simple terms, it helps us calculate:

**𝑃(𝐴∩𝐵)**

where:
P(A∩B) = Probability that both A and B happen

P(A) = Probability of event A

P(B) = Probability of event B


## 1️⃣ Independent Events

Two events are **independent** if the occurrence of one does **not affect** the other.

### Formula

P(A∩B)=P(A)×P(B)

---

### 🎲 Example (With Replacement – Independent Case)

A bag contains:

- 3 Red balls  
- 2 Black balls  

Total balls = 5  

We draw one ball, **replace it**, and draw again.

Let:

- A = First ball is Red
- B = Second ball is Red

Since the first ball is replaced, the second draw is not affected.

P(A) = 3/5

P(B) = 3/5

P(A∩B) = 3/5 × 3/5
​
P(A∩B) = 9/25
---

## 2️⃣ Dependent Events

Two events are **dependent** if the occurrence of one **affects** the other.

### Formula
```
P(A∩B) = P(A)×P(B/A) = P(B)×P(A/B)
```
Where:

- **P(B/A) = Probability of B given that A has already occurred**\
- p(A/B) or p(B/A) is called **conditional probability**


### 🎲 Example (Without Replacement – Dependent Case)

A bag contains:

- 3 Red balls  
- 2 Black balls  

Total balls = 5  

We draw two balls **without replacement**.

Let:

- A = First ball is Red  
- B = Second ball is Red  

P(A) = 3/5

After removing one red ball:

- Remaining balls = 4  
- Remaining red balls = 2  

P(B/A) = 2/4

P(A∩B) = 2/4

P(A∩B) = 3/5 × 2/4

P(A∩B) = 6/20

P(A∩B) = 3/10

# Contingency tables, marginal, conditional and joint probabilities
## 1) Marginal Probability

Marginal probability is the probability of a single event occurring, without considering any other event.
````
Notation:
P(A)

Example:
If 50 out of 100 students are male, then

P(Male) = 50 / 100 = 0.5
````

## 2) Joint Probability
Joint probability is the probability that two events occur together.
````
Notation:
P(A ∩ B)

Example:
If 30 out of 100 students are male and play sports, then

P(Male ∩ Sports) = 30 / 100 = 0.3

This represents the overlap between two events.
````

## 3) Conditional Probability
Conditional probability is the probability of one event occurring given that another event has already occurred.

````
Notation:
P(A | B)

Formula:
P(A | B) = P(A ∩ B) / P(B), where P(B) ≠ 0

Example:
If 40 students play sports and 30 of them are male, then

P(Male | Sports) = 30 / 40 = 0.75
````

## Relationship Between Them

Joint probability connects marginal and conditional probability:

````
P(A ∩ B) = P(A | B) × P(B)
Conditional probability = Joint probability × Marginal probability
````


