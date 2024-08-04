# Probability
Probability is a measure of likelyhood of an event.
Eg: Ah, Roll a dice {1,2,3,4,5,6}. What is a probability of getting a 6

![image](https://github.com/user-attachments/assets/c5cd0cc4-5bbd-4082-a963-3e7605645eda)

![image](https://github.com/user-attachments/assets/6b01a797-17ea-45b5-96dd-afc38bbee815)

### Key Concepts:
1. **Sample Space (S):** The set of all possible outcomes of an experiment.
2. **Event (A):** A subset of the sample space. It is the outcome or a set of outcomes we are interested in.

# Addition Rule(Probability,'Or')
## Mutual Exclusive Event
Two events are mutual exclusive if they cannot occur at the same time
Eg: Rolling a dice {1,2,3,4,5,6} Here we just get only one number, but not two or three at at time

## Non Mutual Exclusive Event
Multiple events can occur at the same time
Eg: Deck of Cards {King, Heart}

### Example 1 for Mutually Exclusive
When you toss a coin, there are two possible outcomes: landing on heads or landing on tails. These outcomes are mutually exclusive, meaning they cannot happen at the same time. 

To find the probability of either of these mutually exclusive events occurring, you can use the following formula:

![image](https://github.com/user-attachments/assets/8b54ff3e-9d04-4120-a5dd-9118f290be44)

![image](https://github.com/user-attachments/assets/7b246ca7-8ac6-43ef-941d-305506c49c42)

So, the probability of the coin landing on heads or tails is 1, meaning it is certain that the coin will land on either heads or tails.

### Example 1 for Non Mutual Exclusive
To solve the problem of finding the probability of choosing a card that is either a queen or a heart from a standard deck of 52 cards, we need to use the formula for non-mutually exclusive events. Non-mutually exclusive events can occur simultaneously. 

In a deck of 52 cards:
- There are 4 queens.
- There are 13 hearts.
- There is 1 queen of hearts, which is counted in both the 4 queens and the 13 hearts.

![image](https://github.com/user-attachments/assets/cbc0257f-9a3f-46dd-9cc9-67419c96c7b6)

![image](https://github.com/user-attachments/assets/0d2596f3-f588-4a28-90ce-65865823d0ec)

Let:
- A be the event that a card is a queen.
- B be the event that a card is a heart.

![image](https://github.com/user-attachments/assets/a8b43d20-86df-4c4d-a930-71a3a8be9a37)

Using the formula:

![image](https://github.com/user-attachments/assets/1a89c1d8-73e8-4ad3-8508-e9e49cb66913)

Now substitute and solve:
![image](https://github.com/user-attachments/assets/5194664c-8df6-4d12-866c-e83225cc81f1)

![image](https://github.com/user-attachments/assets/49da69c7-5962-4854-bd7e-7f54308b08b5)

# Multiplication Rule
## Independent Event
- Eg: Rolling a dice {1,2,3,4,5,6}
Any event here will not impact any event

## Dependent Event
- Eg: Bag of Marbles
- When one event happened here, it will have impact on other events

### Example 1 for Independent Event
- What is the probability of rolling a "5" and then a "4" in a dice?

To determine the probability of rolling a "5" and then a "4" in two consecutive rolls of a fair six-sided die, you can use the concept of independent events. Two events are independent if the outcome of one event does not affect the outcome of the other.

![image](https://github.com/user-attachments/assets/f71c2297-7c7f-4da3-9d41-d1600bca0cd6)

In this example:
- Event A is rolling a "5".
- Event B is rolling a "4".

![image](https://github.com/user-attachments/assets/76849ec0-5a85-4032-8307-11492805c494)

![image](https://github.com/user-attachments/assets/e102984b-7119-42d2-a880-03d10224e494)

### Example of Dependent Event
- What is the probability of drawing a queen and then a ace form a dect of cards

To determine the probability of drawing a queen and then an ace from a deck of cards without replacement, we need to consider dependent events. The outcome of the first event affects the outcome of the second event.

#### Step-by-Step Solution:

1. **Probability of Drawing a Queen (First Event):**
   - There are 4 queens in a standard deck of 52 cards.
   ![image](https://github.com/user-attachments/assets/ed16b421-f884-4ccb-b432-e1e5027d597e)


2. **Probability of Drawing an Ace (Second Event Given First Event):**
   - After drawing a queen, there are now 51 cards left in the deck.
   - There are still 4 aces in the deck.
   ![image](https://github.com/user-attachments/assets/249c8969-61d0-4399-b7f9-64ca0f47cbbc)


3. **Combined Probability Using the Multiplication Rule for Dependent Events:**
   - The combined probability of both events happening is:
   ![image](https://github.com/user-attachments/assets/b92ec3a8-6c8d-4062-953a-ebf34040af8b)

Therefore, the probability of drawing a queen and then an ace from a deck of cards without replacement is \(\frac{4}{663}\).
