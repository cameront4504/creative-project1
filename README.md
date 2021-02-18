# Creative Project: Character Generator / Fantasy Resume

## Features

The goal for this creative project was to experiment more with GPT-2 and attempt to create a character generator that lets the user build off of both random and generated content.

The more I worked on it, however, I ended up pushing for more of a fake, fantasy resume simulator. As a result, the generator:
- Creates a character with randomized properties (name, race, age, title, hobbies, etc.)
- Builds an extended profile using the above properties & GPT-2
- Builds a work history that generates responsibilities of the job
- And conduct an interview with said character using a mix of Markovify and GPT-2

While I did struggle to get everything as connected as I wanted it to be, the program does produce some entertaining results, such as a Necromancer who has about two years of experience working in a pseudo Bed Bath and Beyond. Granted, it does take a while to run due to GPT-2's processing, and is best run through google colab.

## Sources

Namebank:

- Local: btn_givennames.txt
- From: https://www.behindthename.com/api/

Question-bank:

Character Interview
- Local: interview.txt
- From: https://thewritingkylie.com/blog/get-to-know-your-characters-with-character-interviews-115-questions
- Note: Edited out a few section headers

Other:
- Generator uses a mix of my own wordbanks, created from scratch
