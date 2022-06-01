# Book Categorization
The goal of this project is to create a model that can learn to identify writing patterns and correctly classify books. Can a segment of text be identified correctly as to which book it belongs to? Can we recognize authors across different books? Are there other patterns that can be identified that can help categorize the books?
## Datasets
The book texts will be randomly selected from [Project Gutenberg](https://www.gutenberg.org/). Multiple segments of text will be selected from each book. Target labels such as book name, author and year written will be extracted from the information in the book. An effort will be made to find multiple works from the same authors in order to predict authors.
## Methods
After selecting the data and identifying target goals creating predictive features will be necessary. Tokenizing and cleaning the text will be a large part of the data wrangling portion of this project. The plan is to use n-grams of multiple lengths to try to find writing style patterns.
Once usable features have been created, machine learning models, such as neural networks will be used. Accuracy of predictions will be the primary measure of model success
