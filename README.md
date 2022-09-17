# Happy Hour Challenge

## Default code

```py
import random

bars = ["Shoolbred's",
        "The Wren",
        "The Scratcher",
        "ACME",
        "Blind Barber"]

people = ["Mattan",
          "Chris",
          "that person you forgot to text back",
          "Kanye West",
          "Samule L. Jackson"]

random_bar = random.choice(bars)
random_person = random.choice(people)


print(f"How about you go to {random_bar} with {random_person}?")
```

## Step by Step Explanation 

1. Top of the file

```py
import random
```

*This imports other code. A library called 'random' that later allows us to pick out a random bar or random person from our lists.*

2. Lists of Bars & People

```py
bars = ["Shoolbred's",
        "The Wren",
        "The Scratcher",
        "ACME",
        "Blind Barber"]

people = ["Mattan",
          "Chris",
          "that person you forgot to text back",
          "Kanye West",
          "Samule L. Jackson"]
```

*These are lists of bars and people. They are going to be pulled into...*

3. Pick a random bar and a random person

```py
random_bar = random.choice(bars)
random_person = random.choice(people)
```

*This is where our script picks a random bar and a random person.*

4. Print out the results

```py
print(f"How about you go to {random_bar} with {random_person_one} 
```

*This line prints out the random bar and random person.*


# The Happy Hour Challenge is

- I misspelled Samuel L Jackson's name. Fix the typo.
- Add another person to the list of people.
- Change the script so it prints out two random people instead of one. (ex. How about you go to Lion's Head Tavern with Mattan and Chris?)
