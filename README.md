# pdf Chatbot on Local Machine
## simple local pdf chatbot using below libraries
 - pdfminer
 - sentence transformer
 - text generationm

## Models used - 
 - sentence-transformers/all-mpnet-base-v2
 - cross-encoder/ms-marco-MiniLM-L-6-v2

## Usage - 
 - Create python virtual environment using provided requirements.txt file.
 - Run with with following arguments
   - --fname : name of file
   - --top-k : top k results
   - --window-size : context window size

Example - 
```sh
python chatbot.py --fname <name of file> --top-k 5 --window-size 10
```

## Credits - 
 - This code is being developed with initial codebase from of awsome video made by [**Abhishek Thakur**](https://github.com/abhishekkrthakur).
 - [Youtube Video](https://www.youtube.com/watch?v=hSQY4N1u3v0&t=1444s)
 - [GitHub Repository](https://gist.github.com/abhishekkrthakur/401c39d422fb6beff1600effe81f498a)

## Status  - 
- **Phase 1**: Read pdf and provide semantic search
- **Phase 2**: In progress