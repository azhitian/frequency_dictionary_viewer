# Frequency Dictionary Viewer for Mandarin Chinese

I'm learning Mandarin Chinese, and sometimes I have a hard time deciding which words to save and learn. I think it's most valuable to learn words that will show up at least occasionally (but not too often, in which case you're likely to learn them quickly just through immersion) in the things I plan to watch and read. I wrote a python script that takes in text files and outputs a custom dictionary that you can use with Pleco or the webpage provided below that gives you a quick look at how many times each dictionary word shows up in those text files.

![unnamed (1)](https://github.com/Attenius/frequency_dictionary_viewer/assets/45155332/fd0fce13-fe95-41d2-a64f-99a502a7453f)

In this example, 麻雀 shows up 5+ times in the entry "HZ" (活着), 2-4 times in "WitchDollVow" (a web novel I plan to read), and 1 time in "WILL" (a visual novel I'm playing).

## Creating 

Using this Google Colab notebook, you can generate frequency dictionaries for use with the webpage included with this repo or in Pleco (a mobile app with many useful tools Chinese learners):

[Colab Notebook](https://colab.research.google.com/drive/1ilDe3R7r7jJhTgGYfmxqC2fPVatnsobr?usp=sharing)

***Nothing has been tested with traditional characters.** In theory they should work just fine, but using traditional to look up simplified or simplified to look up traditional will not work. I will address this in a future version.*

### Using the dictionary on my webpage

*not tested on mobile*

https://attenius.github.io/frequency_dictionary_viewer/

1. Select frequency dictionary file.

2. Type or paste word anywhere on the page.

3. Titles from your frequency dictionary file will show up as gray (default: 1 occurrence), green+bold (default: 2-4 occurrences), or yellow+italic (default: 5+ occurrences) badges:

![image](https://github.com/Attenius/frequency_dictionary_viewer/assets/45155332/b4e05f73-3786-4372-aa95-fe7e1479955d)

### Using the dictionary in Pleco

1. Copy the dictionary file to your phone.

1. Follow Pleco's instructions on how to import a custom dictionary: https://android.pleco.com/manual/310/dict.html#userdictionaries

1. You should now see your frequency dictionary's entries in Pleco.



