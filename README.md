# Moodle_quizzes
Jupyter notebook to generate Moodle quizzes for 1160 course

### How to use:
1. Scroll down to the bottom of the file to the section titled "run these functions first" and run all helper functions below that title.
2. Add the questions to a new cell under the questions below. Surround all text with input = """ {text_here} """
    - Questions can be copy/pasted from the word doc (don't include the lesson description at the top)
    - Each question must start with QUESTION X
    - The question text must be on one line only - if there are links on new lines, they must be backspaced to be on the same line as the rest of the question text.
    - Pictures will not copy/paste correctly and will usually be pasted as some caption text. Make sure to remove this!
    - Add an asterisk before the correct answer/s in each question
3. Run the two cells under the question cells, making sure to change the 'filename' and 'question_number' variables appropriately

#### NOTE:
This file only generates simple multiple choice questions, where users will be able to select one or more answers. If a question requires some random number generation, or is another type of question (e.g. select from dropdown, place statements in correct order, students must enter text, etc) then it will have to be added to the lesson manually. Any such questions must be marked with (manual input) after the question number so that the code will skip them - for example:

QUESTION 1

should have the tag added

QUESTION 1 (manual input)
