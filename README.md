# boardgame-rules-helper
Developing an AI model to help with asking questions about gameboard rules
# TODO List
1 - identify where all the data for rules are
2 - setup a way to download all data.
3 - clean data
4 - embeddings for the files
5 - upsert embeddings on pinecone
6 - connect pinecone to ChatGPT
7 - test

## OBS
1 - sending emails to boardgame forums and website to ask for access on their data
2 - download PDFs is more likely, huggingface has a pdf reader. some rulebooks are in other languages needs to see if might interfere
3 - a lot of cleaning up will be needed as pdf readers are going to be bad with colorful rules pages from boardgame rulebook
4 - probably OpenAI embedding
5 - pinecone account.
6 - thinking about using Flowise.ai
7 - I want to test it for multiple languages specially portuguese
