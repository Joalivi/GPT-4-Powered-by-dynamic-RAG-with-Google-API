# GPT-4 Powered by Dynamic RAG with Google API

## Overview
This project enhances the capabilities of GPT-4 by integrating it with dynamic retrieval-augmented generation (RAG) using real-time data fetched from the Google API. It aims to improve the contextual accuracy and depth of GPT-4's responses to complex queries by leveraging up-to-date web content.
### Medium Deep Dive
https://medium.com/@joalivijoao/enhancing-gpt-4-responses-with-dynamic-rag-and-google-api-a-deep-dive-aee59f266776

## Key Features
- **Dynamic Question Reformulation**: Condenses user queries into precise search prompts.
- **Real-Time Data Retrieval**: Fetches relevant information from Google to support responses.
- **Semantic Analysis**: Utilizes embeddings and FAISS for document ranking.
- **Enhanced Answer Generation**: Combines GPT-4 with scraped content to produce enriched answers.

## Workflow
### Step-by-Step Process
1. **User Inputs**: Receive a technical query along with specified relevant sites.
2. **Reformulate Query**: Use GPT-4 to condense the query into a search-optimized phrase.
3. **Execute Search**: Perform an optimized search via SerpAPI to gather data.
4. **Scrape Content**: Extract and clean content from the top search results.
5. **Generate Response**: Integrate the fetched data into GPT-4 to produce a contextually rich answer.

## Technologies Used
- **OpenAI GPT-4**: For generating and reformulating queries.
- **Google API (SerpAPI)**: For real-time data retrieval through SerpAPI.
- **FAISS (Facebook AI Similarity Search)**: For efficient similarity search in large datasets.
- **Python**: Main programming language used for scripting and automation.
- **BeautifulSoup**: Used for scraping and cleaning data from web pages.
- **Pandas**: For data manipulation and analysis.
- **Requests**: To send HTTP requests easily.

## Testing and Results
The project was tested with multiple-choice questions from the Revalida examination, demonstrating a slight improvement in answer accuracy with RAG integration compared to baseline GPT-4. However, it is important to note that these results do not hold statistical significance due to the small sample size of questions evaluated.

## Conclusion
This project showcases the potential of combining GPT-4 with dynamic external data retrieval to enhance the accuracy and relevance of automated responses in practical scenarios.
