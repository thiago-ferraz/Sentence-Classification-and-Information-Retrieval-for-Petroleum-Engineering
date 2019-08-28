# Sentence-Classification-and-Information-Retrieval-for-Petroleum-Engineering
Dataset containing manually labeled (into: 'Introduction', 'Objectives', 'Methods' and 'Results') abstract sentences from 278 Petroleum Engineering related papers collected from the Journal of Petroleum Exploration and Production Technology (from 2011 to 2018), as well as from IEEE Xplore database.

## Content and format
The file `sentences_classif.json` contains a list of serialized JSON objects that look like the following:

```json
{
   "class": "Introduction",
   "position": 0.0,
   "sentence": "In a petroleum cyber-physical system (CPS), interwell connectivity estimation is critical for improving petroleum production."
}
```

The fields represent the following:

- `class`: the classification of the sentence (Introduction, Objectives, Methods or Results).
- `position`: the relative position of the sentence within the abstract.
- `sentence`: the sentence from the abstract.
