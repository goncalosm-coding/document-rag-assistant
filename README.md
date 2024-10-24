## Setup Instructions

### Chroma Database Setup
The Chroma database is used to store document embeddings. This folder is generated dynamically when you run the script to populate the database.

1. Ensure the necessary documents are in the appropriate folder.
2. Run the 'populate_database.py' script to generate the Chroma database (or click the 'Update Database' button after login).

### Data Folder
The 'data' folder contains the documents that the app uses for retrieval and answering questions and should be created by the user on the root folder. 

- You can add your own documents or download the default ones to this folder.
- Make sure the documents are in the correct format (PDF).

### General Information

If there is no Documents loaded, or the question asked isn't mentioned in the documents the assistant won't provide more than "No Relevant Documents Found." for an answer (this happens in order to only use our gathered data).
