So Here what we have done is basically we have firstly fine tune in the abstract and title which was provided as a dataset.
We have made a dataframe which consist of the title and abstract together then we have apply all the NLP preprocessing where we have done the tokenization and removing of stopwords and all the basic NLP Preprocessing steps.
Later we have done a summarization of this combine text for all which we have later convert it to PDF format.
We have then make a very basic streamlit Interface for chatbot thing.
In our final model we have used a hugging face pipeline "Question Answering" with max_word_output length 300 and other fine tune parameter which we have trail and test and fine tune it to get the best output from the model
![Final_Output](https://github.com/Siddharth133/Patent_ChatBot/assets/99598353/11bb6835-523c-4a79-b89a-bf41ab23210b)
