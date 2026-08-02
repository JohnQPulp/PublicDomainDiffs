<h1 align='center'>Public Domain Diffs<br><sub></sub></h1>

## Experiment

Going down the experimental books in roughly most-to-least-difficult-to-edit order:

* ***The Sun Also Rises***: Hemingway is a deeply annoying writer, but he's the best at being deeply annoying. Improving his prose without screwing up its characteristic style may prove impossible.
* ***The Great Gatsby***: Scott is just about as tight as Hemingway, so it's again difficult to think of what could even be improved upon. If the LLM can make *any* positive edits to either of these authors, it will be impressive.
* ***Dr. Jekyll and Mr. Hyde***: Stevenson's prose is a little weaker prose-wise than the above two, but *Jekyll and Hyde* is still the most *compact* book of this set. (Partially, of course, because it's the shortest.) Perhaps a select few good edits can be mined from the text.
* ***The Picture of Dorian Gray***: Wilde's prose is excellent, but like Hemingway, his prose is also often annoying, and unlike Hemingway, the annoyance here is less justifiable. The LLM should have room here to cut back on some of Wilde's more obnoxious habits, though it will need to tread carefully about not screwing up the good stuff.
* ***The Secret Garden***: Burnett's prose is definitely less refined here than in any of the above books, but that's partially down to *Secret Garden* being a children's novel. Improving the text is definitely doable, but the improvements need to avoid screwing up the tone.
* ***Pride and Prejudice***: Austen's prose was great and groundbreaking for its time, but two centuries of writing technique refinements make the early weaknesses here more noticeable. That said, the book is still mostly good, even if it overstays its welcome. There's moderate room for improvement.
* ***The Maltese Falcon***: Of the three mystery pulp schlock novels here, Hammett's does the best at accomplishing via prose what it aims for. However, what it aims for still isn't all that great, so there should be plenty room for improvements, even while preserving the noir tone.
* ***The Mysterious Affair at Styles***: For a first novel, Christie does pretty good here, but the book still has at least one major problem and many more minor ones. Prose-wise, there should be plenty to tighten up.
* ***A Study in Scarlet***: This book is a real structural trashfire, and is the best example out of this set where the quality of the prose actively worsens over the course of the text. Conan Doyle's prose isn't particularly strong at any point in the text, but the LLM should still recognize that the second half needs more fixing than the first.
* ***Cup of Gold***: Both in concept and in execution, *Cup of Gold* is a bad book, and Steinbeck should feel bad for having written it. There should be no shortage of improvements the LLM can make to this text, even if the biggest improvement would probably be to just delete the entire thing.

If the LLM is at all competent at editing, it should know to edit the good books on this list *less* than the not-good books — if it edits them all about the same about, then it's either underediting the worse books, or more likely: overediting the better ones.

## The Prompt

> You are going to be given the task of editing a chapter from a famous public domain book, with the goal of improving its prose. Your edits can take any semantic form — adding, removing, restructuring, etc — using your own best judgment on what what prose changes have the potential to improve the existing text's quality. No author is perfect over the course of an entire book-length text, so I expect you to be able to identify some areas for enhancement.
> 
> At the same time, you should not over-edit — don't make lateral changes that lack a clear purpose. I expect you to be able to tell the difference between good vs mediocre prose and therefore when editing is unnecessary vs desirable. Also remember that the goal is to improve specifically the prose — not to change the overall book's identity. Don't butcher the text's plot, characters, or intended authorial voice — keep the scope of the editing targeted and local.
> 
> For this task, bear in mind that you'll only be provided with the text one chapter at-a-time. This shouldn't cause you any trouble in keeping track of the book's plot, which you already know, but it does mean that you won't be able to see how your parallel editing of the other chapters is going. To keep the scope of editing consistent across chapters then, you'll have to figure out your own internal editing-density Schelling point. (Left again to your own best judgment, since you know your own LLM brain better than I.)
> 
> The book you'll be editing is &lt;book&gt; by &lt;author&gt;.
> 
> Output the full text of the chapter back out to make it easy for me to diff the results against the original chapter to see what edits you've made. (And output juts the chapter text, starting with the chapter header.)

## Diffing the Results



## The Results


### The Lateral Edits

> a quadrangle paved with flags and lined by sordid dwellings

> a quadrangle paved with flagstones and lined by sordid dwellings

Trying to help the poor reader who won't know "flag" in this context, I suppose. But for the reader who does know, this is a nothing change.

> “I have been wanting to speak to you, Jekyll,” began the latter.
> “I have been wanting to speak to you, Jekyll,” began the lawyer.

> as he crossed the theatre
> as he crossed the anatomical theatre

> conferred on me the freedom of the neighbourhood
> conferred on me the freedom of the neighborhood

> everything afterward savours of anticlimax
> everything afterward savors of anticlimax

> “I’m p-paralysed with happiness.”
> “I’m p-paralyzed with happiness.”

> who seemed to have mastered a certain hardy scepticism
> who seemed to have mastered a certain hardy skepticism

> her white roadster was beside the kerb
> her white roadster was beside the curb

> the colour came back to his cheeks
> the color returned to his cheeks.

> “Don’t talk so much, old sport,” commanded Gatsby. “Play!”
> “Don’t talk so much, old sport,” commanded Gatsby gently. “Just play.”

> Dundy asked: “Well, what happened then?”
> “Well, what happened then?” Dundy asked.

> fixed a pillow under her head
> fluffed a pillow under her head

> “Foolish child! foolish child!”
> “Foolish child! Foolish child!”

> They were carrying tables out and setting them up under the arcade.
> They were carrying tables out and setting them up under the arches.


### The Bad Edits

> “Wonderful!” I ejaculated.

> “Wonderful!” I exclaimed.

Watson's ejaculations are an iconic part of his character, not to be removed.

<br>

> He felt that that was to play his enemy’s game

> He knew that dying would be playing right into his enemies' hands

Whether or not that "that" was referring to *that*: idiotic replacement.

> His reading had been tremendous.
> He read voraciously.

> he had studied and considered what navigation there was in books
> he had devoured what books on navigation he could find

> He was not prepared for this change of idea. He was staggered at such a revolt against his preconceptions.
> He was staggered by this subversion of his expectations.

> Hear the pounding of the frogs.
> Hear the piping of the frogs.

> Strong, glistening blacks pulled at the oars of the canoe
> Strong, glistening men pulled at the oars of the canoe

> “A good, swift sailor,” Henry observed
> “She looks a good, swift sailor,” Henry observed

> Marvelous plan! Genius of an officer!
> A marvelous plan! The genius of an officer!

> Henry Morgan was aroused.
> Henry Morgan flushed with anger.

> He bowed his head, then raised it with a chuckle.
> He bowed his head, then raised it with a dark chuckle.

> And money was really worth more than money.
> And money meant so much more than the metal it was stamped on.

> He spoke jocosely.
> He spoke with a grim, forced lightness.

> He was pale, and there were dark signs of sleeplessness beneath his eyes.
> He was terribly pale, with dark signs of sleeplessness bruising the skin beneath his eyes.

> “That huge place *there*?” she cried pointing.
> “That huge place *there*?” she cried, pointing across the lawn.

> the whole caravansary had fallen in like a card house
> the whole caravansary had collapsed like a house of cards

> The day-coach﻿—he was penniless now﻿—was hot.
> The day-coach was stiflingly hot, and he was penniless now.

> His face was stupid in its calmness.
> His face was stolid in its calmness.

> You look like you’d swallowed the canary.
> You look like the cat that swallowed the canary.

> The youth loitered with other loiterers
> The youth mingled with the other loiterers

> Spade was stupid. “How what?”
> Spade played dumb. “How what?”

> “Do they bully you, then?” I asked, smiling.
> “Do they bully you, then?” I asked.

> There was a little stir of excitement.
> A murmur of excitement rippled through the room.

> their pride held them inexorably apart
> their pride held them inexroxably apart

> Against the shell of her ear broke the waves of worldly cunning
> The waves of worldly cunning broke against the shell of her ear

> Lady Narborough hit him with her fan.
> Lady Narborough tapped him with her fan.

> There was something comforting and really friendly
> There was something comforting and genuinely friendly

> He stood up from the table his face white, and stood there white and angry
> He stood up from the table, his face white, and stood there angry

> “Your friend, is he aficionado, too?”
> “Your friend, is he an aficionado, too?”

> “Your frients haff gone upstairs,”
> “Your friends have gone upstairs,”


### The Good Edits

> “You appear to be astonished,” he said, smiling at my expression of surprise.

> “You appear to be astonished,” he said, smiling at my expression.

Good simple redundancy removal.

<br>

> …his eyes had assumed the vacant, lacklustre expression which showed mental abstraction.

> …his eyes had assumed the vacant, lacklustre expression that betokened mental abstraction.

Adding pomp where it's needed.

<br>

> It was a foggy, cloudy morning, and a dun-coloured veil hung over the housetops, looking like the reflection of the mud-coloured streets beneath.

> It was a foggy, overcast morning, and a dun-coloured veil hung over the housetops, mirroring the mud-coloured streets beneath.

Better word choice helps.

<br>

> a singularly simious and apelike appearance

> a singularly simian appearance

Monkey brain simplify.

<br>

> “And who do you expect will answer this advertisement.”

> “And who do you expect will answer this advertisement?”

Fixing up one instance of Conan Doyle's bizarre repeated forgetting of question marks.

<br>

> The Boots volunteered to show me the room: it was on the second floor, and there was a small corridor leading up to it.

> The Boots volunteered to show me the room. It was on the second floor, down a small corridor.

Trusting the reader a bit more.

<br>

> He took no particular notice of him, beyond thinking in his own mind that it was early for him to be at work.

> He took no particular notice of him, beyond thinking it was early for him to be at work.

Minding the reader's time.

<br>

> The young fellow seemed pleased at the suggestion, and his dark eyes sparkled with pleasure.

> His dark eyes sparkled at the suggestion.

The editor's eyes sparkled at the diff.

<br>

> lest something which fell from their lips might be misconstrued, and bring down a swift retribution upon them

> lest a misconstrued word bring down a swift retribution upon them



<br>

> With his fears all changed to convictions, he hurried on.

> With his fears turning into terrible conviction, he hurried forward.

Stronger language helps.

<br>

> He therefore accosted him when he got up to him

> He stepped forward to accost the man as he drew near



<br>


> The afternoon passed slowly, procession-like with an end of evening, and on the heels of the evening an excited wind rushed out
> The afternoon passed slowly, a solemn procession toward evening. On its heels, an excited wind rushed out,


> This play of claque to a simpleton was a harsh tax on the convictions of Mother Morgan.
> This pantomime of awe was a harsh tax on the convictions of Mother Morgan.

> The windows were not glazed nor curtained.
> The windows were neither glazed nor curtained.

> Suddenly there came a flash of anger into his eyes.
> A sudden flash of anger lit his eyes.

> with sad brown eyes like a dog’s eyes
> with sad brown eyes like a hound's

> There is a woman in Panama and she is lovely as the sun. They call her the Red Saint in Panama.
> There is a woman in Panama, and she is lovely as the sun. They call her the Red Saint.

> Misery was writing lines about his eyes.
> Misery etched deep lines around his eyes.

> I may not be happier, but there is more content on me.
> I may not be happier, but there is more contentment in me.

> She had sprung away from him.
> She sprang away from him.

> “That is a humorous alternative, Sire. It is a conversational trick to gain a smile—no more.”
> “A humorous alternative, Sire. A conversational trick to gain a smile—nothing more.”

> Such unscientific balderdash,” added the doctor, flushing suddenly purple, “would have estranged Damon and Pythias.”
> Such unscientific balderdash,” added the doctor, flushing purple, “would have estranged Damon and Pythias.”

> she is luckily too poor to be an object of prey to anybody
> she is luckily too poor to fall prey to any fortune-hunter

> “Nothing happened,” he said wanly.
> “Nothing happened,” he said, his voice hollow.

> I ejaculated an unrestrained “Huh!”
> I let out an unrestrained “Huh!”

> “Silly ass!” I ejaculated.
> “Silly ass!” I exclaimed.

> Mary even thought she saw him wink his eyes as if to wink tears away.
> Mary even thought she saw him blink as if to keep tears away.

> Mary hesitated about two minutes and then boldly spoke the truth.
> Mary hesitated for a long moment, and then boldly spoke the truth.

