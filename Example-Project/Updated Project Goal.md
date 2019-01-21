# Updated Project Goal

Linear learner worked functionally, but it was not highly accurate. Next iteration:

1. Use ETL to add:
      - is_precipitation 
      - is_hot
      - increase in temperature from yesterday
      - crimes-to-date on that block 

2. Use Obj2Vec to create embeddings
      - Each block & feature vector should have its own embedding

3. Use Factorization Machines
      - Generate a matrix of all blocks against all types of crime
      - Actually want to train on sequence of criminal activity on that block

4. Run KNN
      - Build a similarity engine 
      - Run queries to find blocks with high crime likelihood

5. Put into a heat map 
      - Use Folium
      - Extend with an SMS subscription service:
        - If there's likely to be a crime on your block, get a notification

## References
      - https://arxiv.org/pdf/1806.01486.pdf 
