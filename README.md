Semantic-Search-on-Movies-Dataset
This project demonstrates a semantic search system built on a movies dataset (movie.csv). Instead of searching by exact keywords, the system understands the context and meaning of a query — retrieving movies that are semantically related to the user’s input.


 Semantic Search on Movies Dataset

 Overview
This project demonstrates a "Semantic Search Engine" for movies using the `movie.csv` dataset.  
Unlike traditional keyword search, it retrieves movies based on "meaning and context" from the movie overviews.

 Features
- Converts movie overviews into "semantic embeddings" using "Sentence Transformers (all-MiniLM-L6-v2)" 
- Stores embeddings in a "FAISS vector index" for fast similarity search  
- Allows users to query movies by "descriptive text", e.g., “movies about friendship and robots”  

 Tech Stack
- Python | Pandas | NumPy | FAISS | Sentence Transformers

 How to Run
1. Clone the repo:
```bash
git clone https://github.com/yourusername/semantic-search-movies.git
