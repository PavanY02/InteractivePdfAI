# **INTERACTIVE PDF AI - You Get What You Want**

Interactive PDF AI is and online pdf question answering system which can be used  for asking questions related to any pdf and get the out put from it . This Pdf Ai allows you to input multiple pdfs at a time and generate output from whats there in the pdf.


## **Table of Contents**

- Features
- Technologies
- Installation
- Usage
- Contributing

## **Features**

- Streamlit : This application is built using stream lit ,which make the interface user friendly
- Langchain : Most important framework for developing generative ai applications and for  using Open sourced Large Language Models. 
- Huggingface : An important frame work for using Open Sourced Large Language Models I.
- Vector Database: Allows to store the data as vectors,as vectors are very useful when checking the smimilarity


## **Technologies**

- Streamlit
- Langchain
- Huggingfacehub,Huggingface embeddings
- Meta Llama2
- faiss-cpu


## **Installation**


1. Set up Huggingface :

   - Create a Huggingface account at https://huggingface.co/
   - Generate Your own Hugging face - Api Key  in setting -> access tokens of the huggingface hub.
   - Search for llama-2-7b-chat.ggmlv3.q8_0  a request licence to use the model.
   - download the llama-2-7b-chat model and create a new project and save the model in file named models.

2. Clone this repository:

   ```
   git clone : https://github.com/PavanY02/InteractivePdfAI.git
   ```
3. Install the Requirements:

   ```
   pip install -r requirements.txt                                                                                                      
                                                                                   
   ```

4. Run the app:

   ```
   streamlit run main.py
   ```
## **Usage**

- After runnig the main.py ull be desplaying an interface where you can upload your pdf
- after selecting and uploding the pdf click on the process button ,and wait until the process completed is displayed
- now ask your question related to your pdfs and wait for the response 
- your reponse get stored until your session state is done.
