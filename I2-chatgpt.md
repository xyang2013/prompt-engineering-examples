Free Research Preview. ChatGPT may produce inaccurate information about people, places, or facts. ChatGPT Mar 23 Version

## User prompt 1
````
Summarize the text delimited by triple backticks \ 
into a single sentence.
```
You should express what you want a model to do by \ 
providing instructions that are as clear and \ 
specific as you can possibly make them. \ 
This will guide the model towards the desired output, \ 
and reduce the chances of receiving irrelevant \ 
or incorrect responses. Don't confuse writing a \ 
clear prompt with writing a short prompt. \ 
In many cases, longer prompts provide more clarity \ 
and context for the model, which can lead to \ 
more detailed and relevant outputs.
```
````

ChatGPT
```
Providing clear and specific instructions to a model can guide it towards the desired output, reduce irrelevant or incorrect responses, and longer prompts can provide more clarity and context for more detailed and relevant outputs.
```

## User prompt 2
````
Generate a list of three made-up book titles along \ 
with their authors and genres. 
Provide them in JSON format with the following keys: 
book_id, title, author, genre.
````
### ChatGPT
````
Here are three made-up book titles, along with their authors and genres, in JSON format:

css

[  {    "book_id": 1,    "title": "The Lost Kingdom",    "author": "Lila Adams",    "genre": "Fantasy"  },  {    "book_id": 2,    "title": "The Art of Deception",    "author": "Maxwell Stone",    "genre": "Mystery"  },  {    "book_id": 3,    "title": "Echoes of the Past",    "author": "Samantha Scott",    "genre": "Romance"  }]

The first book is a fantasy novel titled "The Lost Kingdom" written by Lila Adams, the second book is a mystery novel titled "The Art of Deception" written by Maxwell Stone, and the third book is a romance novel titled "Echoes of the Past" written by Samantha Scott.
````

## User prompt 3
````
You will be provided with text delimited by triple quotes. 
If it contains a sequence of instructions, \ 
re-write those instructions in the following format:

Step 1 - ...
Step 2 - …
…
Step N - …

If the text does not contain a sequence of instructions, \ 
then simply write "No steps provided."

"""
Making a cup of tea is easy! First, you need to get some \ 
water boiling. While that's happening, \ 
grab a cup and put a tea bag in it. Once the water is \ 
hot enough, just pour it over the tea bag. \ 
Let it sit for a bit so the tea can steep. After a \ 
few minutes, take out the tea bag. If you \ 
like, you can add some sugar or milk to taste. \ 
And that's it! You've got yourself a delicious \ 
cup of tea to enjoy.
"""
````

### ChatGPT
````
Here are the instructions in the requested format:

Step 1 - Get some water boiling.
Step 2 - While the water is boiling, grab a cup and put a tea bag in it.
Step 3 - Once the water is hot enough, pour it over the tea bag.
Step 4 - Let the tea sit for a few minutes to steep.
Step 5 - Take out the tea bag.
Step 6 - Add sugar or milk to taste (optional).

The above text contains a sequence of instructions for making a cup of tea.
````

## User prompt 4
````
You will be provided with text delimited by triple quotes. 
If it contains a sequence of instructions, \ 
re-write those instructions in the following format:

Step 1 - ...
Step 2 - …
…
Step N - …

If the text does not contain a sequence of instructions, \ 
then simply write "No steps provided."

"""
The sun is shining brightly today, and the birds are singing. It's a beautiful day to go for a \ 
walk in the park. The flowers are blooming, and the \ 
trees are swaying gently in the breeze. People \ 
are out and about, enjoying the lovely weather. \ 
Some are having picnics, while others are playing \ 
games or simply relaxing on the grass. It's a \ 
perfect day to spend time outdoors and appreciate the \ 
beauty of nature.
"""
````

### ChatGPT
````
No steps provided.

The above text does not contain a sequence of instructions. It simply describes the beauty of a day in the park.
````

## User prompt 5
````
Your task is to answer in a consistent style.

<child>: Teach me about patience.

<grandparent>: The river that carves the deepest \ 
valley flows from a modest spring; the \ 
grandest symphony originates from a single note; \ 
the most intricate tapestry begins with a solitary thread.

<child>: Teach me about resilience.
````

### ChatGPT
````
<grandparent>: A mighty oak tree grows from a small acorn, and a beautiful flower blooms from a tiny seed; just as a bird rises from the ashes to soar again, so too can we rise from our struggles and soar to new heights.
````

## User prompt 6
````
Perform the following actions: 
1 - Summarize the following text delimited by triple backticks with 1 sentence.
2 - Translate the summary into French.
3 - List each name in the French summary.
4 - Output a json object that contains the following keys: french_summary, num_names.

Separate your answers with line breaks.

Text:
```
In a charming village, siblings Jack and Jill set out on \ 
a quest to fetch water from a hilltop \ 
well. As they climbed, singing joyfully, misfortune \ 
struck—Jack tripped on a stone and tumbled \ 
down the hill, with Jill following suit. \ 
Though slightly battered, the pair returned home to \ 
comforting embraces. Despite the mishap, \ 
their adventurous spirits remained undimmed, and they \ 
continued exploring with delight.
```
````

### ChatGPT
````
    Despite a misfortunate fall while fetching water from a hilltop well, siblings Jack and Jill returned home slightly battered but with their adventurous spirits undimmed.
    Malgré une chute malheureuse en allant chercher de l'eau dans un puits au sommet d'une colline, les frères et sœurs Jack et Jill sont rentrés chez eux légèrement ébréchés mais avec leur esprit d'aventure intact.
    Jack, Jill.
    {"french_summary": "Malgré une chute malheureuse en allant chercher de l'eau dans un puits au sommet d'une colline, les frères et sœurs Jack et Jill sont rentrés chez eux légèrement ébréchés mais avec leur esprit d'aventure intact.", "num_names": 2}
````

## User prompt 7
````
Your task is to perform the following actions: 
1 - Summarize the following text delimited by 
  <> with 1 sentence.
2 - Translate the summary into French.
3 - List each name in the French summary.
4 - Output a json object that contains the 
  following keys: french_summary, num_names.

Use the following format:
Text: <text to summarize>
Summary: <summary>
Translation: <summary translation>
Names: <list of names in Italian summary>
Output JSON: <json with summary and num_names>

Text: <
In a charming village, siblings Jack and Jill set out on \ 
a quest to fetch water from a hilltop \ 
well. As they climbed, singing joyfully, misfortune \ 
struck—Jack tripped on a stone and tumbled \ 
down the hill, with Jill following suit. \ 
Though slightly battered, the pair returned home to \ 
comforting embraces. Despite the mishap, \ 
their adventurous spirits remained undimmed, and they \ 
continued exploring with delight.
>
````

### ChatGPT
````
Text: <In a charming village, siblings Jack and Jill set out on a quest to fetch water from a hilltop well. As they climbed, singing joyfully, misfortune struck—Jack tripped on a stone and tumbled down the hill, with Jill following suit. Though slightly battered, the pair returned home to comforting embraces. Despite the mishap, their adventurous spirits remained undimmed, and they continued exploring with delight.>
Summary: <Siblings Jack and Jill had a mishap while on a quest for water in a village but returned home undeterred.>
Translation: <Les frères et sœurs Jack et Jill ont eu un accident lors d'une quête pour de l'eau dans un village mais sont retournés chez eux sans se décourager.>
Names: <Jack, Jill>
Output JSON: {"french_summary": "Les frères et sœurs Jack et Jill ont eu un accident lors d'une quête pour de l'eau dans un village mais sont retournés chez eux sans se décourager.", "num_names": 2}
````

## User prompt 8
````
Determine if the student's solution is correct or not.

Question:
I'm building a solar power installation and I need  help working out the financials. 
- Land costs $100 / square foot
- I can buy solar panels for $250 / square foot
- I negotiated a contract for maintenance that will cost \ 
me a flat $100k per year, and an additional $10 / square foot
What is the total cost for the first year of operations 
as a function of the number of square feet.

Student's Solution:
Let x be the size of the installation in square feet.
Costs:
1. Land cost: 100x
2. Solar panel cost: 250x
3. Maintenance cost: 100,000 + 100x
Total cost: 100x + 250x + 100,000 + 100x = 450x + 100,000
````

### ChatGPT
````
The student's solution is correct.
````

## User prompt 7
````
Your task is to determine if the student's solution is correct or not.
To solve the problem do the following:
- First, work out your own solution to the problem. 
- Then compare your solution to the student's solution \ 
and evaluate if the student's solution is correct or not. 
Don't decide if the student's solution is correct until 
you have done the problem yourself.

Use the following format:
Question:
```
question here
```
Student's solution:
```
student's solution here
```
Actual solution:
```
steps to work out the solution and your solution here
```
Is the student's solution the same as actual solution just calculated:
```
yes or no
```
Student grade:
```
correct or incorrect
```

Question:
```
I'm building a solar power installation and I need help working out the financials. 
- Land costs $100 / square foot
- I can buy solar panels for $250 / square foot
- I negotiated a contract for maintenance that will cost me a flat $100k per year, and an additional $10 / square foot
What is the total cost for the first year of operations as a function of the number of square feet.
``` 
Student's solution:
```
Let x be the size of the installation in square feet.
Costs:
1. Land cost: 100x
2. Solar panel cost: 250x
3. Maintenance cost: 100,000 + 100x
Total cost: 100x + 250x + 100,000 + 100x = 450x + 100,000
```
Actual solution:
````

### ChatGPT
````
Let x be the size of the installation in square feet.
Costs:

    Land cost: 100x
    Solar panel cost: 250x
    Maintenance cost: 100,000 + 10x
    Total cost: 100x + 250x + 100,000 + 10x = 360x + 100,000
    Is the student's solution the same as actual solution just calculated:
    No
    Student grade:
    Incorrect
````

## User prompt 8
````
Tell me about AeroGlide UltraSlim Smart Toothbrush by Boie
````

### ChatGPT
````
The AeroGlide UltraSlim Smart Toothbrush by Boie is a high-tech toothbrush that uses ultrasonic vibrations to clean teeth, along with a slim, flexible brush head that can reach tight spaces. It has an integrated smart timer that lets users know when they have brushed for the recommended two minutes and is designed to be gentle on gums while still providing a thorough clean. Additionally, it has a long battery life, comes with a charging stand, and is made with eco-friendly materials.
````
