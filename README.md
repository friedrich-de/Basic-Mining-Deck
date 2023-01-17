# Mining Deck Template
A basic Anki deck template for Japanese language learning.

![Deck Preview](sample_image.png)

## Features
- Requires zero editing of Yomichan templates (handlebars)
and should therefore no longer break on Yomichan updates.
- Determines whether the expression matches the reading and 
if it does, puts the sample sentence on the front of the 
card as recommended by [Animecards](https://animecards.site).  
- Automatically formats the HTML created by Yomichan to
create switchable definitions using the arrow keys or click/touch.
- Sets a few fallback fonts so there is no possibility of Chinese being displayed.
- Should work on all devices.

## Yomichan Fields
| Anki Field    | Yomichan Template        | 
|---------------|--------------------------|
| Word          | {expression}             | 
| Reading       | {reading}                |
| Glossary      | {glossary-no-dictionary} |
| Sentence      | {clipboard-text}         |
| Picture       |                          |
| Audio         | {audio}                  |
| SentenceAudio |                          |
| Graph         | {pitch-accent-graphs}    |
| Hint          |                          |

## Direct Download
TBA
