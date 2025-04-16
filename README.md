# more-data

idea to create more training data from raw text

## 1 generate_text
tags: memory, generate
task: generate random text from raw text

## 2 generate_sentence
tags: memory, generate
task: generate random sentence from raw text

## 3 generate_text_from_word
tags: memory, generate
task: generate random text from random word

## 4 generate_sentence_from_word
tags: memory, generate
task: generate random sentence from random word

## 5 generate_text_from_topic
tags: memory, generate, LLM, topic
task: generate random text from topic or use LLM to generate topic

## 6 generate_sentence_from_topic
tags: memory, generate, LLM, topic
task: generate random sentence from topic or use LLM to generate topic

## 7 generate_missing_word
tags: understand
task: generate missing word from given text

## 8 generate_missing_sentence
tags: understand
task: generate missing sentence from given text

## 9 pick_missing_word
tags: understand, verifiable
task: select missing word from list of given word and text
output: `[D]`

## 10 pick_missing_sentence
tags: understand, verifiable
task: select missing sentence from list
output: `[D]`

## 11 generate_reorder_word
tags: understand
task: generate ordered text from random order word

## 11 pick_reorder_word
tags: understand
task: pick ordered text from random order word

## 12 generate_reorder_sentence
tags: understand
task: generate ordered sentence from random order sentence

## 13 pick_reorder_sentence
tags: understand, verifiable
task: pick ordered sentence from random order sentence
output: `[D,A,E,B,C]`





# addon
## add noise to text
## add noise to word
## pick one of list example (1) [D,A,E,B,C] (2) [A,B,C,D,E] (3) [A,B,C,E,D]





