# Description
This project is about RAG (Retrieval-Augmented Generation) using Vector Database as storage for new data.

# Dataset
The new data used for the project is called product_500.csv containing
 - product_id
 - sku
 - brand
 - product_name
 - category
 - description
 - price_usd
 - rating
 - in_stock
 - units_sold

# Vector Database
The vector database used for the project is qdrant_client (https://pypi.org/project/qdrant-client/).

# Data Embedding
The Model used for data embedding is all-MiniLM-L6-v2 (https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2).

# Requirements
## Libraries
To run the script, requirement.txt must be installed.
## Llama file
Local run of llama file (https://www.google.com/search?q=run+the+llamafile&rlz=1C1CHBF_enPH1031PH1031&oq=run+the+llamafile&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIICAEQABgWGB4yCggCEAAYChgWGB4yDQgDEAAYhgMYgAQYigUyDQgEEAAYhgMYgAQYigUyCggFEAAYogQYiQUyBggGEEUYPDIGCAcQRRg80gEINTA0NGowajeoAgCwAgA&sourceid=chrome&ie=UTF-8)
1. Download a llamafile (Meta-Llama-3-8B-Instruct.Q2_K.llamafile was used for this project from https://huggingface.co/mozilla-ai/Meta-Llama-3-8B-Instruct-llamafile/tree/main).
2. Make the llamafile executable.
3. Run the llama file to set up a llama model locally. The notebook contains the script to query it.
