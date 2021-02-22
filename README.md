# Creative Project: Character Generator / Fantasy Resume

## Features

The goal for this creative project was to experiment more with GPT-2 and attempt to create a character generator that lets the user build off of both random and generated content. And building more generated content off some generated content (as far as Google Colab's RAM allowed).

The more I worked on it, however, I ended up pushing for more of a fake, fantasy resume simulator. As a result, the program now does the following:
- Creates a character with randomized properties (name, race, age, title, hobbies, etc.)
- Builds an extended profile using the above properties & GPT-2
- Builds a work history that generates responsibilities of the job
- Conducts an interview with said character using a mix of Markovify and GPT-2

## How to Run

The .pynb file works best on google colab. Just create a double based off this link(https://colab.research.google.com/drive/1yELunjWyOx1AERCmEKQc9KmIrVUxrTuV?usp=sharing) and then drag the sources folder with the two .txt files into the window. Nothing else really requires interaction aside from one cell which asks for user input.

The output will be created as a .txt file for viewing, as well.

## Samples

While I did struggle to get everything as connected as I wanted it to be, the program does produce some entertaining results, such as a Necromancer who has about two years of experience working in a pseudo Bed Bath and Beyond. Granted, it does take a while to run due to GPT-2's processing, and in fact, it <b>is best to run it through google colab.</b>

At any rate, I have provided a few of my favorite runs in the directory (see any resume_name.txt file) for faster viewing.

## Sources

Namebank:

- Local: btn_givennames.txt
- From: https://www.behindthename.com/api/
- Used code to ignore any m/f gender markings

Question-bank:

Character Interview
- Local: interview.txt
- From: https://thewritingkylie.com/blog/get-to-know-your-characters-with-character-interviews-115-questions
- Note: Edited out a few section headers

Other:
- Generator uses a mix of my own small wordbanks (colors, titles), created from scratch

## Disclaimer

While the project was not influenced by any one work in particular, I do think my enjoyment of The World (According to Computers) might've slipped in somewhere or another. Additionally, I do not claim any credit for the work of BehindTheName or TheWritingKylie's datasets that I used.
