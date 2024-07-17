Python program to build a sentence generator program using bi-gram and tri-gram model. You will generate M sentences by starting with random (n-1) gram from the model and then randomly select the next word until reaching a max length of sentence. The corpus used in this assignment is Brown Corpus in NLTK library. Get all sentences from brown corpus. 

Input: 
• m -> Number of sentences to be generated 
• n -> 2 for bigram – 3 for trigram 
• maxLen -> Max number of words in sentence generated. Used as stopping condition in generating a sentence. 
• Corpus -> list of sentences to generate n-gram model from it. 

Output: 
• m sentences each sentence contain maxLen words. 

Steps: 
1-Apply data preprocessing: 
• Tokenize sentences into words (Word Tokenization). 
• Remove punctuation marks from tokens. 
• Convert all tokens to lowercase. 
2-Build N-gram model: 
Build n-gram dictionary, where the keys are tuples of n-1 words (n-1 gram) and the values are lists of possible next words. 
3-Sentence Generator: 
Sentence generation process start with a random n-1 gram from the model and then randomly select the next word until reaching maxLen or unable to find next word.