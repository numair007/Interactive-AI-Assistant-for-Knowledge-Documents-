# Interactive-AI-Assistant-for-Knowledge-Documents-

Tech - Java, LangChain4J, OpenAI API, Cassandra
This project builds a PDF chat application that allows users to ask questions about a PDF document in a conversational way. Here are the technologies used:

Programming languages: Java
Frameworks: Spring Boot
Libraries: Langchain4J
Databases: Astra DB (vector database)
The application first ingests the PDF document and splits it into text segments. It then creates embeddings, which are numerical representations of the text segments, using a large language model. These embeddings are stored in a vector database called Astra DB.

When a user asks a question about the PDF document, the application converts the question into an embedding as well. It then searches the vector database for embeddings that are similar to the query embedding. The most relevant text segments from the PDF document are then retrieved and passed to a chat language model, which generates a human-readable response.
