### About

A fast and flexible way to search for researchers using knowledge graphs, language models and natural language processing.

The initial platform was developed at the [University of Bristol](http://www.bristol.ac.uk/) via a [Jean Golding Institute](http://www.bristol.ac.uk/golding/) seed corn grant.

The platform consists of the following components:

- [Setup](https://github.com/researcher-searcher/researcher-searcher-setup) - example using Pure data
- [NLP and search](https://github.com/researcher-searcher/researcher-searcher-search) - Spacy and Elasticsearch
- [Knowledge graph](https://github.com/researcher-searcher/researcher-searcher-graph) - Neo4j
- [API](https://github.com/researcher-searcher/researcher-searcher-api) - FastAPI
- [Web App](https://github.com/researcher-searcher/researcher-searcher-app) - demo using Dash

### Instances

- [University of Bristol - Population Health Sciences](https://rs-phs.mrcieu.ac.uk/)

### Build

1. Create the raw data 
    - people
    - output
    - organisation
    - person->output
    - person->organisation
2. Process raw data using NLP to create all required files
3. Create knowledge graph of people, output, concepts, etc.
4. Create search engine
5. Build the API
6. Build a basic web app. 