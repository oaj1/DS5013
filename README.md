# DS5013
Project 3


Requirements for your project:
Your program must include:
load the file with the novel into your python program and save its content into a variable
make sure words are not counted as new words if they have a comma, point, etc, attached to them or if they are lower or upper case
replace commas, points etc, with white spaces
transform the string to all lower case
tokenize the string
Count the number of words and unique words and print a sentence with the results.
count how often each word occurs using a for loop and save the result in a dictionary
tip: Iterate through all your words and fill your dictionary like this:
for word in your_file_contents.split():
    if word in wordcounts:
        wordcounts[word] += 1
but check if this individual word is not yet in your dictionary. If not, add it.
print the result in a table for the most occuring words
Only show results for the roughly 30 most appearing words, for example if the word appears at least 100 (it depends on your novel which value you use) times in the novel.
the table you create with just the print command needs to look somewhat pretty: all entries for a given column start aligned under each other and add a headline
documentation of the programming code
Create a visualization (you can choose which type) which shows how often the most occurring words appear in the novel
add a meaningful title to the diagram which also contains the title of the novel
