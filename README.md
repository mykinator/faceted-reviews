# Coding Task

1. Download the Amazon customer review dataset for Musical Instruments here (2.5 MB): http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Musical_Instruments_5.json.gz
2. Determine a set of suitable facets for this dataset. A facet is an attribute like "price", "material", "battery life", etc. You may do this however you like, with code or just by manually scanning. You need not submit this code. 
3. Submit a function that takes a single customer review as input and outputs a JSON consisting of the facets extracted from the review and a snippet attached to each facet.

## Example

```
# the language doesn't matter
def extractFacets (reviewText): 
  ... 
  return { "price" : "this watch is way overpriced.", "durability": "not very well built." }
```

Please spend no more than 1-2 hours on this task. If you wish, you may leverage an external knowledge-base (such as WordNet or word embeddings), but please do not use a machine learning framework or toolkit for this task. We are mainly evaluating problem solving and coding.
