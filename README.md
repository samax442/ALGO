# ALGO
Initialize sentence_length to 0
Initialize word_count to 0
Initialize vowel_count to 0

Prompt user to input a sentence

For each character in the sentence:
    Increment sentence_length by 1
    
    If character is a space:
        Increment word_count by 1
        
    If character is a vowel (considering both uppercase and lowercase):
        Increment vowel_count by 1

Add 1 to word_count  // The last word won't have a space after it
