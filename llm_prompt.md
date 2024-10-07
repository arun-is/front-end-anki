Extract all important points that can be presented as simple trivia questions with a correct answer. Use inline code for any code syntax. For each question provide the following:

1. title of the trivia question flashcard in snake-case (make it verbose to avoid conflicts)
2. the question
3. the answer

Make sure that the trivia questions are accurate and don't contain any falsehoods.
Format like the following and use inline code with backticks for all code syntax:

this-is-a-sample-title.md

```
This is the front of the card including some javascript `console.log(test)`

---

This is the back of the card including some javacript `console.log(test)`
```

After presenting all the flashcards in this format, provide bash commands to create these flashcards as individual files in a new directory. The commands should look like this:

```bash
echo "Question

---

Answer" > filename.md
```

Repeat for each flashcard.

Below is the input content.
