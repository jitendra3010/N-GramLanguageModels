**NOTE : The corpus size on which the models are build are ~60K which is very less for n-gram model**

### Sample data from the models generated:

**Unigrams:**

[('Having',), ('a',), ('little',), ('flexibility',), ('on',), ('that',), ('issue',), ('would',), ('go',), ('a',)]

**Bigrams:**

[('<START>', 'Having'), ('Having', 'a'), ('a', 'little'), ('little', 'flexibility'), ('flexibility', 'on'), ('on', 'that'), ('that', 'issue'), ('issue', 'would'), ('would', 'go'), ('go', 'a'), ('a', 'long'), ('long', 'way'), ('way', 'to'), ('to', 'putting'), ('putting', 'together'), ('together', 'a'), ('a', 'final'), ('final', 'package'), ('package', '.'), ('.', '<STOP>'), ('<START>', 'Long'), ('Long', 'before'), ('before', 'the'), ('the', 'advent'), ('advent', 'of')]

**Trigrams:**

[('<START>', '<START>', 'Having'), ('<START>', 'Having', 'a'), ('Having', 'a', 'little'), ('a', 'little', 'flexibility'), ('little', 'flexibility', 'on'), ('flexibility', 'on', 'that'), ('on', 'that', 'issue'), ('that', 'issue', 'would'), ('issue', 'would', 'go'), ('would', 'go', 'a'), ('go', 'a', 'long'), ('a', 'long', 'way'), ('long', 'way', 'to'), ('way', 'to', 'putting'), ('to', 'putting', 'together'), ('putting', 'together', 'a'), ('together', 'a', 'final'), ('a', 'final', 'package'), ('final', 'package', '.'), ('package', '.', '<STOP>'), ('<START>', '<START>', 'Long'), ('<START>', 'Long', 'before'), ('Long', 'before', 'the'), ('before', 'the', 'advent'), ('the', 'advent', 'of')]


**Perplexity of train and Test:**

<img width="416" alt="image" src="https://github.com/user-attachments/assets/0579b7c2-5d7e-4ba0-a30a-4f5728ce5df6">


### Text generaiton with Greedy approach

Unigram Generated Text:

 `the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the`
 
-------------------------
Bigram Generated Text:

 `<START> The <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> , the <unk> ,`
 
-------------------------
Trigram Generated Text:

 `<START> <START> The <unk> <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> , <unk> ,`

 ### Text generation with Random approach

Unigram Generated Text:

 `lived other is arrived new . <unk> to edited Two is of programs too <STOP>`
 
-------------------------
Bigram Generated Text:

 `<START> The frieze , which has a benchmark 10-year low ebb and adoption of individual financial support the family 's endorsement or <unk> with traders selling about an assist in countries they laid against the scale back all out " It should always more than four seasons in this year , <unk> in Helsinki . <STOP>`
 
-------------------------
Trigram Generated Text:

 `<START> <START> But where to inflict attacks on the Guatemalan government to acquire the Thomson <unk> Center will celebrate decades of operations , financial analysts critical of the escaped teenagers were headed and look at the half-year stage by the base of independent grocers , including next week to negative . <STOP>`

 ### Text generation with top-p approach

Unigram Generated Text:

 `It up a to BST often <unk> 1.4 were . fans million show savings , officer 2008 already study player entire the and 15 a the 30 match <STOP>`
 
-------------------------
Bigram Generated Text:

 `<START> All in a base , Australia steadied Wall Street but they were unlikely champion Sabrina takes <unk> these governments . <STOP>`
 
-------------------------
Trigram Generated Text:

 `<START> <START> " If they wanted to find a <unk> modest castle with a far less common , so why sack him ? <STOP>`
