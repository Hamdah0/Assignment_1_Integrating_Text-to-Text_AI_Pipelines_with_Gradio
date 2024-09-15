# Assignment_1_Integrating_Text-to-Text_AI_Pipelines_with_Gradio
My submission for assignment1 of Tuwaiq bootcamp.

## Description
I choose an NER model to complete this assignment, simply, my project is to implement a NER model with a gradio interface,
and let the user input a text and the outputs should be:

1-the text with a red highlight on the entities, along with their types.

2-A dataframe of the text showing the entities, their types, confidence scores, start positions, end positions and the full text.

## How to run the code

Install the needed libraries using !pip install package
**1- Gradio
2-pandas
3-Transformers**

Then Import them as shown in **NER_pipleline_with_gradio_interface.ipynb**

implement the needed NER model using pipeline, and put it inside a variable


Start writing the first function which will take the text from the user, using the model all the recoginzed entities will be placed
Inside a list, and that list of entities will be accessed by a for loop and converted to a Data frame.
Follow the code along


Start writing the second function, which will call the first one, and put a red highlight (You can change the color inside the dev block)
on the entities and their types (LOC, ORG, PER, OR MISC).
This function will return the highlighted entities with the whole text.

Start writing the third function, which will only call the first and the second, and return them to use in the gradio interface.

finally follow the gradio interface as shown in the file.



## Hugging Face space
The Hugging Face space link to the assignment:

https://huggingface.co/spaces/hamdah926/NER_model_with_gradio?logs=container


## Video recording of final code



[![YouTube](http://i.ytimg.com/vi/anN_kE1QYDM/hqdefault.jpg)](https://www.youtube.com/watch?v=anN_kE1QYDM)
