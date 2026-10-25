# Specialized Technology

## Technology used:
- Natural Language Processing is the area of AI that allows Computers to read and analyze human language to identify certain patterns in human speeches.

## How it works:
- A comment will be processed to identify the overall sentiment of the comment and then compile key points of the comment.

## Key concepts:
- Sentiment analysis: deciding the tonality of a text to determine wether the text is painted in a positive, neutral or negative light.
- Aspect-based sentiment analysis: finding the topics being discussed.
- Supervised learning: training model on comments that humans have labelled.

## Example:
- Comment: "Lecturer explain dengan jelas, tapi class too fast"
- Aspect detection: clarity ("dengan jelas") and pacing ("too fast")
- Sentiment: clarity is positive, pacing is negative
- summary: clarity (positive), pacing (negative)

## How it fits this problem

### Benefits:
- gives lecturers aspect level feedback instead of a single score.
- handles comment volumes that have outgrown manual reading

### limitations and risks:
- need data to train the model
- informal language might make aspect detection harder
- 

### Alternatives
- manual reading and coding of comments by humans: able to handle context well, but it is manual and slow. the comments also runs a risk of being under-analysed because summarising them takes so much time and work.