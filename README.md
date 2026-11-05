# TemporalRDF2Vec

Standard RDF2Vec treats all connected edges with equal probability. When containing time-bound events, random walks jump between temporally distant entities. We will implement custom walking strategy computing temporal edge weights dynamically. Our goal is to demonstrate improved accuracy in time-related tasks compared to RDF2VEC.

## Datasets
| Dataset | Type | Source |
|---|---|---|
| DBpedia events subset | RDF | link |
| ICEWS14 | Temporal KG | link |

## Setup
1. `git clone https://github.com/JoelPestana/TemporalRDF2Vec.git`
2. `python -m venv venv`
3. `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Linux/macOS)
4. `pip install -r requirements.txt`
5. `python TemporalRDF2Vec/src/download_data.py`

## Running the analysis
Run the notebooks in `notebooks/` in order.

## Authors
Lucía Navarro, Pablo Osuna & Joel Pestana
