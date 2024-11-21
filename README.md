In this project I have used llmsherpa library in python to create chunks of the pdf file.
The created chunks are passed to the llm (google/flan-t5-large  in this case) and iteratively the response is generated 
The model currently being used (google/flan-t5-large) has low accuracy, any other model can be used to generate better responses
We need to include nlm-ingestor(from the github repository) file into this repository and run apache tika server
The model is downloaded and then used in the file
