# Semantic-Information-Analyzer

Goals:
  Summarize documents/papers/speeches
  Return relavant information pertaining to key political information
  Metric for determing political leaning from words authored by the document
  
Nice to have:
  Ingest hand written documents
  Translate different languages to English
 
 speech_summary.py program does the following:
  1. Loads the text and converts it to a string.
  2. Tokenizes the text into words and sentences.
  3. Removes stop words with no contextual content.
  4. Counts the remaining words.
  5. Uses the count to rank the sentences.
  6. Displays the highest-ranking sentences.
    
  
  
