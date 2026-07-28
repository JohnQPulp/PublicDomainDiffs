<h1 align='center'>Public Domain Diffs<br><sub></sub></h1>

## Experiment

Going down the experimental books in roughly most-to-least-difficult-to-edit order:

* *The Sun Also Rises*: Hemingway is a deeply annoying writer, but he's the best at being deeply annoying. Improving his prose without screwing up its characteristic style may prove impossible.
* *The Great Gatsby*: Scott is just about as tight as Hemingway, so it's again difficult to think of what could even be improved upon. If the LLM can make *any* positive edits to either of these authors, it will be impressive.
* *Dr. Jekyll and Mr. Hyde*: Stevenson's prose is a little weaker prose-wise than the above two, but *Jekyll and Hyde* is still the most *compact* book of this set. (Partially, of course, because it's the shortest.) Perhaps a select few good edits can be mined from the text.
* *The Picture of Dorian Gray*: Wilde's prose is excellent, but like Hemingway, his prose is also often annoying, and unlike Hemingway, the annoyance here is less justifiable. The LLM should have room here to cut back on some of Wilde's more obnoxious habits, though it will need to tread carefully about not screwing up the good stuff.
* *The Secret Garden*: Burnett's prose is definitely less refined here than in any of the above books, but that's partially down to *Secret Garden* being a children's novel. Improving the text is definitely doable, but the improvements need to avoid screwing up the tone.
* *Pride and Prejudice*: Austen's prose was great and groundbreaking for its time, but two centuries of writing technique refinements make the early weaknesses here more noticeable. That said, the book is still mostly good, even if it overstays its welcome. There's moderate room for improvement.
* *The Maltese Falcon*: Of the three mystery pulp schlock novels here, Hammett's does the best at accomplishing via prose what it aims for. However, what it aims for still isn't all that great, so there should be plenty room for improvements, even while preserving the noir tone.
* *The Mysterious Affair at Styles*: For a first novel, Christie does pretty good here, but the book still has at least one major problem and many more minor ones. Prose-wise, there should be plenty to tighten up.
* *A Study in Scarlet*: This book is a real structural trashfire, and is the best example out of this set where the quality of the prose actively worsens over the course of the text. Conan Doyle's prose isn't particularly strong at any point in the text, but the LLM should still recognize that the second half needs more fixing than the first.
* *Cup of Gold*: Both in concept and in execution, *Cup of Gold* is a bad book, and Steinbeck should feel bad for having written it. There should be no shortage of improvements the LLM can make to this text, even if the biggest improvement would probably be to just delete the entire thing.

If the LLM is at all competent at editing, it should know to edit the good books on this list *less* than the not-good books — if it edits them all about the same about, then it's either underediting the worse books, or more likely: overediting the better ones.

## The Prompt

```
You are going to be given the task of editing a chapter from a famous public domain book, with the goal of improving its prose. Your edits can take any semantic form — adding, removing, restructuring, etc — using your own best judgment on what what prose changes have the potential to improve the existing text's quality. No author is perfect over the course of an entire book-length text, so I expect you to be able to identify some areas for enhancement.

At the same time, you should not over-edit — don't make lateral changes that lack a clear purpose. I expect you to be able to tell the difference between good vs mediocre prose and therefore when editing is unnecessary vs desirable. Also remember that the goal is to improve specifically the prose — not to change the overall book's identity. Don't butcher the text's plot, characters, or intended authorial voice — keep the scope of the editing targeted and local.

For this task, bear in mind that you'll only be provided with the text one chapter at-a-time. This shouldn't cause you any trouble in keeping track of the book's plot, which you already know, but it does mean that you won't be able to see how your parallel editing of the other chapters is going. To keep the scope of editing consistent across chapters then, you'll have to figure out your own internal editing-density Schelling point. (Left again to your own best judgment, since you know your own LLM brain better than I.)

The book you'll be editing is <book> by <author>.

Output the full text of the chapter back out to make it easy for me to diff the results against the original chapter to see what edits you've made. (And output juts the chapter text, starting with the chapter header.)
```

## Diffing the Results



## The Results
