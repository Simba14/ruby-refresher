# Ruby Refresher

A Ruby refresher containing 41 questions of varying difficulty.
Each question follows the same format: a set of instructions, an empty method for population, and a test.

I have extracted two of the questions below to give an indication of the questions' range of difficulty.

Easier:
> Don't reverse the array, but reverse every word inside it. e.g. ['dog', 'monkey'] becomes ['god', 'yeknom']

Harder:
> In a file, total the number of times words of different lengths appear. So in a file with the text "the cat sat on the blue mat" I have 5 words which are 3 letters long, 1 which is 2 letters long and 1 that is 4 letters long. Return it as a hash in the format word_length => count, e.g. {2 => 1, 3 => 5, 4 => 1

Skills Sharpened
----
* Ability to read and understand Ruby documentation
* Expanded my knowledge of the methods that can be applied to both strings and arrays.
* Now comfortable with using regex for simple to intermediate pattern searches
* Breaking down complex problems into smaller chunks


Tests
----
All tests are contained in the questions_spec.rb found in the spec directory.
Instructions on how to run the tests can be found below.

To run the specs, just run
~~~
$ rspec questions_spec.rb
~~~

**Quick tip**: to run a single example, change `it` to `fit` on that example, then run

~~~
$ rspec spec/questions_spec.rb --tag focus
~~~


### Tips

* Use the ruby docs http://www.ruby-doc.org/core-2.0.0/String.html
* Try and break down the problems into smaller chunks. For e.g. if you google "How to select elements in an array that start with a", you won't have much luck. Try and find out a) how to select certain elements in an array, b) how to test if a string starts with an 'a'
