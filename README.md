# Coding Task

1. Spend ~5 minutes browsing customer reviews of Musical Instruments on Amazon (https://www.amazon.com/b?&node=11091801).
2. Brainstorm an approach that identifies, given a customer review, whether the review mentions one or more of the following product facets: **price**, **durability**, and/or **sound quality**.
3. Submit a function that takes an unformatted customer review as input and outputs a JSON consisting of the facets extracted from the review and a snippet pertinent to each facet.

## Example

```
# the language doesn't matter
def extractFacets (reviewText): 
  ... 
  return { "price" : "this watch is way overpriced.", "durability": "not very well built." }
```

If you wish, you may leverage an external knowledge-base (such as WordNet or word embeddings), but please **do not** use a machine learning framework or toolkit for this task. We are mainly evaluating problem solving and coding.

## FAQ

#### Step 3 sounds like information extraction over unstructured text, which cannot be implemented in a couple of hours.

We deliberately chose a complex task to evaluate how you problem solve and prioritize essential functionality, given the limited time scope and constrained access to external resources.

#### How is the solution evaluated?

We are looking for a "reasonable" solution: Does the code use sensible data structures and control flow? Does the approach perform reasonably well given the constraints? How does the solution ensure accuracy when extracting facets and snippets?

#### Does the code have to build?

The code does not have to build, but it should be written in a real programming language (not pseudocode). This ensures that we are able to follow along without guesswork.
