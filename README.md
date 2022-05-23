# Keyword-Extraction-System-using-Parallel-Computing-
This project is inspired by Information Retrieval. It has a lot of application in real word. As the name suggests “Keyword Extraction” is about searching words in documents parallelly using open MP. This is not just a simple word search but it also ranks the documents based on the relevance of the documents with respect to the searched word. The documents are scanned word by word and a dictionary is maintained so that words can be searched. Since documents can have several thousands of terms scanning each term can take a lot of time and hence there is a lot of scope for parallelization. This project focuses on the principle of multithreaded systems. It uses multiple threads to read multiple files and perform the action. The action here being searching the word through the files, and doing so in very less time as compared to the sequential system. The parameters are similar to that of the sequential method, but the processors are used to do the sequential process on multiple files at the same time. At the end we will compare both the approaches and note down the results.
![image](https://user-images.githubusercontent.com/70505625/169840308-878dc80e-8cff-4381-b5cc-f1fa7ca12ede.png)

# Sequential Approach

![image](https://user-images.githubusercontent.com/70505625/169840555-083be3a2-12b5-45f6-bf33-cd423e849ccb.png)

# Parallel Approach 

![image](https://user-images.githubusercontent.com/70505625/169840704-b6fc6b3a-9a59-4c06-a116-4b44dc98412d.png)
