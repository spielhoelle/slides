# Artificial intelligence


# Today's agenda

- Attention is all we need <!-- .element: class="fragment" data-fragment-index="2" -->
- Vectors <!-- .element: class="fragment" data-fragment-index="3" -->
- API's <!-- .element: class="fragment" data-fragment-index="4" -->
- Large scale data <!-- .element: class="fragment" data-fragment-index="5" -->
- Langchain <!-- .element: class="fragment" data-fragment-index="6" -->
- Icecream revenue prediction <!-- .element: class="fragment" data-fragment-index="8" -->
- Volmne, Velocity, Variety <!-- .element: class="fragment" data-fragment-index="8" -->
- Algorithms <!-- .element: class="fragment" data-fragment-index="9" -->
- Types compared to real-life things <!-- .element: class="fragment" data-fragment-index="10" -->
- Examples <!-- .element: class="fragment" data-fragment-index="11" -->


# Policts: What does Trump have for implications

- loosen Artificial Intelligence (AI) Regulation <!-- .element: class="fragment" data-fragment-index="2" -->
- Trade Policies and Tariffs <!-- .element: class="fragment" data-fragment-index="3" -->
- loosen Antitrust Enforcement <!-- .element: class="fragment" data-fragment-index="4" -->
- tariffs on european/chinese products <!-- .element: class="fragment" data-fragment-index="5" -->


# The paper
## "Attention is All You Need"
### The Birth of the Transformer Model

- https://arxiv.org/pdf/1706.03762

Speaker Notes:

    - Introduce the seminal paper published in 2017 by Vaswani et al., which revolutionized natural language processing. <!-- .element: class="fragment" data-fragment-index="2" -->
    - Explain the key contribution: the Transformer model, which relies entirely on an attention mechanism, discarding the need for recurrent layers. <!-- .element: class="fragment" data-fragment-index="3" -->
    - Highlight how Transformers achieve higher accuracy in translation tasks with less training time compared to previous models like RNNs and LSTMs. <!-- .element: class="fragment" data-fragment-index="4" -->
    - Discuss the impact of this model on a wide range of applications including language translation, text generation, and even extending to image processing tasks. <!-- .element: class="fragment" data-fragment-index="5" -->
    - Mention how this architecture forms the backbone of popular models like BERT, GPT, and T5, which dominate the field of AI research and application today. <!-- .element: class="fragment" data-fragment-index="6" -->


# OpenAi

- lets make an account and get an API key


# Vectors

- https://youtu.be/6yLmbL1o3Ow?t=767 <!-- .element: class="fragment" data-fragment-index="2" -->
- Multidimensional space https://colab.research.google.com/drive/1lTb2maWnoDhVdz0oamu2Vag86FBhhRP5 <!-- .element: class="fragment" data-fragment-index="3" -->
- Semantics != keywordbased <!-- .element: class="fragment" data-fragment-index="3" -->
- Embeddings <!-- .element: class="fragment" data-fragment-index="4" -->


# APIs
- request => processing => response  <!-- .element: class="fragment" data-fragment-index="4" -->
- connectors between apps <!-- .element: class="fragment" data-fragment-index="5" -->
- can be interfaces, description of softwaresystems <!-- .element: class="fragment" data-fragment-index="6" -->


# Examples of APIs

- Restaurant Example <!-- .element: class="fragment" data-fragment-index="2" -->
- Bank Teller Example <!-- .element: class="fragment" data-fragment-index="3" -->
- Travel Agent Example <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:

- Restaurant Example: Think of an API like a waiter in a restaurant. You (the client) give the waiter (API) your order, and they take it to the kitchen (server) to fulfill it. The waiter then brings you back the food (response). <!-- .element: class="fragment" data-fragment-index="4" -->
- Bank Teller Example: Imagine going to a bank and asking a teller to perform a transaction. You provide the necessary information (request), the teller processes it (processing), and then gives you the result (response). <!-- .element: class="fragment" data-fragment-index="5" -->
- Travel Agent Example: A travel agent can be thought of as an API between you and airlines, hotels, etc. You give them your travel requirements (request), they book the trip for you (processing), and provide you with the itinerary (response). <!-- .element: class="fragment" data-fragment-index="6" -->


# Exercise 

- Let's run some `curl` commands
- https://jsonplaceholder.typicode.com/posts
- ai.tmy.io
```
curl https://ai.tmy.io/api/chat -d '{
  "model": "llama3.1",
  "stream": false,
  "messages": [
    {
      "role": "user",
      "content": "Explain me linear algebra as if I am a 6th grader. Answer short."
    }
  ]
}'
```
- add flags like: `curl -I` or `curl -v`
- do it in python notebook https://colab.research.google.com/drive/1kOJTPDYns5UFXXv8rkheT5_7dAjkPua6


# RAG

- retrieval augmented generation <!-- .element: class="fragment" data-fragment-index="2" -->
- similarity search <!-- .element: class="fragment" data-fragment-index="3" -->
- Checkout some patterns https://vectorize.io/multimodal-rag-patterns/ <!-- .element: class="fragment" data-fragment-index="4" -->


# Chains

- [Strip email, date, customer from plaintext]( https://github.com/spielhoelle/capsule/blob/main/capsule/email/prompts.py ) <!-- .element: class="fragment" data-fragment-index="2" -->
- [langchain_email_stock_check]( https://colab.research.google.com/drive/1nExcMEYEWi2VlMF1FnPVlu_rCGEZ4V_V#scrollTo=Lehhy0tMpBmw ) <!-- .element: class="fragment" data-fragment-index="3" -->


# How to build agents

- Checkout some nodes & edges https://langchain-ai.github.io/langgraphjs/tutorials/


# First steps
## Setting Up the Environment
- Python and virtual environments
- Installing LangChain and other dependencies
- Choosing a model (Mistral, Ollama)
- Build software (if/else) around LLM calls

Speaker Notes:

- Guide on setting up Python virtual environments to manage dependencies.
- Instructions for installing LangChain via pip and setting up Mistral or Ollama as the model runtime.
- Discuss the benefits of each model choice in terms of performance and compatibility.


# Exercise: Interpret Titanic dataset 

- Explore this dataset https://storage.googleapis.com/tf-datasets/titanic/train.csv
- feature engineering examples titanic dataset https://colab.research.google.com/drive/15Cyy2H7nT40sGR7TBN5wBvgTd57mVKay#forceEdit=true&sandboxMode=true&scrollTo=GltdTjiERfWi


# Other challenges with AI applications
- Short/long term memory <!-- .element: class="fragment" data-fragment-index="2" -->
- Persistence of which vectors <!-- .element: class="fragment" data-fragment-index="3" -->
- How questions and systemprompts are arranged <!-- .element: class="fragment" data-fragment-index="4" -->
- If and what finetune model we take <!-- .element: class="fragment" data-fragment-index="5" -->


# Computer vision

- Simple travolta example: https://huggingface.co/spaces/Scrimba/vanilla-js-object-detector <!-- .element: class="fragment" data-fragment-index="2" -->
- Simple OCR https://tesseract.projectnaptha.com/ <!-- .element: class="fragment" data-fragment-index="3" -->
- How that works https://colab.research.google.com/drive/1ZZXnCjFEOkp_KdNcNabd14yok0BAIuwS#forceEdit=true&sandboxMode=true <!-- .element: class="fragment" data-fragment-index="4" -->
- More examples https://www.v7labs.com/blog/computer-vision-applications <!-- .element: class="fragment" data-fragment-index="5" -->


# Whisper voice to text

- What it is https://github.com/openai/whisper?tab=readme-ov-file
- https://huggingface.co/spaces/Xenova/whisper-web
- Lets play around with more examples 


# Explore metrics
- show ssh'ed nvtop during inference curl <!-- .element: class="fragment" data-fragment-index="2" -->
- GPU memory, CPU, Network, hyperparams <!-- .element: class="fragment" data-fragment-index="3" -->
- Modeldownload/storage <!-- .element: class="fragment" data-fragment-index="4" -->


# Advanced Integration Techniques
- Streaming, summarization, nextcloud assistant example <!-- .element: class="fragment" data-fragment-index="2" -->
- Combine with traditional programming techniques <!-- .element: class="fragment" data-fragment-index="3" -->
- Copilot as only profitable AI product right now https://github.com/features/copilot <!-- .element: class="fragment" data-fragment-index="4" -->


# Deployment 
- Own hardware or cloud provider <!-- .element: class="fragment" data-fragment-index="2" -->
- AI api provider or local development <!-- .element: class="fragment" data-fragment-index="3" -->
- Best practices for deployment <!-- .element: class="fragment" data-fragment-index="4" -->
- Open-source tools and platforms for deployment <!-- .element: class="fragment" data-fragment-index="5" -->
- https://cloud.google.com/vertex-ai <!-- .element: class="fragment" data-fragment-index="6" -->


## Discovering the Universe of Large Scale Data

Speaker Notes:

- Welcome participants to the workshop.
- Briefly introduce the day's agenda and the objective to understand what big data is and how it is used today.


# What is Big Data?
- **Volume:** Immense amounts of data <!-- .element: class="fragment" data-fragment-index="3" -->
- **Velocity:** Generated at high speeds <!-- .element: class="fragment" data-fragment-index="4" -->
- **Variety:** Different types of data <!-- .element: class="fragment" data-fragment-index="5" -->

Speaker Notes:

- Explain the three V's of big data: Volume, Velocity, and Variety.
- Use an example like social media platforms generating large amounts of data every second.


## Volume

- Example: Facebook generates 4 petabytes of data daily <!-- .element: class="fragment" data-fragment-index="2" -->
- Challenge: Storing and processing this data <!-- .element: class="fragment" data-fragment-index="3" -->
- Solution: Distributed storage and processing systems <!-- .element: class="fragment" data-fragment-index="4" -->


## Velocity

- Example: Twitter generates 500 million tweets daily <!-- .element: class="fragment" data-fragment-index="2" -->
- Challenge: Processing data in real-time <!-- .element: class="fragment" data-fragment-index="3" -->
- Solution: Stream processing systems <!-- .element: class="fragment" data-fragment-index="4" -->


## Variety

- Example: Data from social media, sensors, logs, etc. <!-- .element: class="fragment" data-fragment-index="2" -->
- Challenge: Handling different data types <!-- .element: class="fragment" data-fragment-index="3" -->
- Solution: Flexible data models and storage systems <!-- .element: class="fragment" data-fragment-index="4" -->


# Everyday Examples of Big Data

- Social Media Statistics <!-- .element: class="fragment" data-fragment-index="2" -->
- Online Shopping Patterns <!-- .element: class="fragment" data-fragment-index="3" -->
- Smart Home Devices <!-- .element: class="fragment" data-fragment-index="4" -->

Speaker Notes:

- Illustrate with examples: Mention how every like, comment, and share on social media adds to big data.
- Discuss how online shopping records every purchase and customer preference.


# Ethical Considerations in AI and Big Data

- Bias and Fairness <!-- .element: class="fragment" data-fragment-index="2" -->
- Transparency <!-- .element: class="fragment" data-fragment-index="3" -->
- Privacy <!-- .element: class="fragment" data-fragment-index="4" -->
- Accountability <!-- .element: class="fragment" data-fragment-index="5" -->
- Environmental Impact <!-- .element: class="fragment" data-fragment-index="6" -->
- Consent and Data Ownership <!-- .element: class="fragment" data-fragment-index="7" -->
- Security <!-- .element: class="fragment" data-fragment-index="8" -->
- Misuse and Dual-Use <!-- .element: class="fragment" data-fragment-index="9" -->

Speaker Notes:

- Bias and Fairness: Ensure AI models don't reinforce existing biases, as biased data can lead to unfair outcomes.
- Transparency: Make AI decisions understandable and interpretable for users; avoid "black box" models when transparency is crucial.
- Privacy: Protect personal data through strict adherence to data privacy laws (e.g., GDPR, CCPA) and minimize data collection to only what's necessary.
- Accountability: Establish clear responsibility for AI-driven decisions, especially in critical areas like healthcare or finance.
- Environmental Impact: Consider the carbon footprint of large AI models; optimize compute resources where possible.
- Consent and Data Ownership: Ensure users consent to how their data is used and stored, respecting ownership and control over personal data.
- Security: Safeguard AI and data systems from cyber threats, as breaches can have significant repercussions.
- Misuse and Dual-Use: Anticipate and prevent harmful applications of AI, especially in areas where misuse could cause societal harm (e.g., surveillance, disinformation).


# Algorithms

- Linear regression <!-- .element: class="fragment" data-fragment-index="2" -->
- Logistic regression <!-- .element: class="fragment" data-fragment-index="3" -->
- Random forrest <!-- .element: class="fragment" data-fragment-index="4" -->
- KNN <!-- .element: class="fragment" data-fragment-index="6" -->
- Neural network <!-- .element: class="fragment" data-fragment-index="7" -->
- Clustering <!-- .element: class="fragment" data-fragment-index="8" -->


## Exercise
- Explore huggingface datasets
  - [mlabonne/guanaco-llama2-1k](https://huggingface.co/datasets/mlabonne/guanaco-llama2-1k)
  - [openbmb/UltraInteract_sft](https://huggingface.co/datasets/openbmb/UltraInteract_sft)

Speaker Notes:

- Empathize the dataset viewer


# Hands-On

## Icecream revenue prediction


# **Exercise**:
Explore [this](/IceCreamData.csv) data set on your own


# **Solution**:
See and explain on [Kaggle](https://www.kaggle.com/code/tariquepce/ice-cream-revenue-prediction/input)


# Data Types and Sources

- Structured vs Unstructured Data <!-- .element: class="fragment" data-fragment-index="2" -->
- Examples from daily life <!-- .element: class="fragment" data-fragment-index="3" -->

Speaker Notes:

- Explain the difference between structured and unstructured data with examples like a formatted database vs. videos and images.


## Structured Data

- Definition: Data with a clear format and organization <!-- .element: class="fragment" data-fragment-index="2" -->
- Examples: Relational databases, spreadsheets <!-- .element: class="fragment" data-fragment-index="3" -->
- Characteristics: Easy to analyze and process <!-- .element: class="fragment" data-fragment-index="4" -->
- Challenge: Limited flexibility and horizontal scalability <!-- .element: class="fragment" data-fragment-index="5" -->


## Unstructured Data

- Definition: Data without a predefined format <!-- .element: class="fragment" data-fragment-index="2" -->
- Examples: Videos, images, social media posts <!-- .element: class="fragment" data-fragment-index="3" -->
- Characteristics: Difficult to analyze and process <!-- .element: class="fragment" data-fragment-index="4" -->
- Challenge: Extracting meaningful insights <!-- .element: class="fragment" data-fragment-index="5" -->


## Examples:

- MySQL (structured) <!-- .element: class="fragment" data-fragment-index="2" -->
- MongoDB (structured) <!-- .element: class="fragment" data-fragment-index="3" -->


# Data Types again?


## Comparing Ingredients in Cooking

- Structured: Recipe ingredients <!-- .element: class="fragment" data-fragment-index="2" -->
- Unstructured: Cooking style <!-- .element: class="fragment" data-fragment-index="3" -->

Speaker Notes:

- Use the cooking analogy to make the concept more relatable.
- Discuss how structured ingredients follow a recipe, whereas unstructured cooking styles vary.


# Integers
## Counting Apples
- Analogy: Think of counting apples like integers in programming. Just whole numbers, no fractions. <!-- .element: class="fragment" data-fragment-index="2" -->
- Integers are used to count discrete items like people in a room, pages in a book, and buildings on a street. <!-- .element: class="fragment" data-fragment-index="3" -->


# Floats
## Measuring Ingredients
- Analogy: Floating point numbers allow for fractions, similar to measuring ingredients in cooking. <!-- .element: class="fragment" data-fragment-index="2" -->
- Real-life Use: Floats are useful whenever precise measurements are needed. <!-- .element: class="fragment" data-fragment-index="3" -->


# Strings
## Naming Pets
- Analogy: Strings in programming are sequences of characters used for text. <!-- .element: class="fragment" data-fragment-index="2" -->
- Real-life Use: Strings are used for names, addresses or passwords <!-- .element: class="fragment" data-fragment-index="3" -->


# Boolean
## Light Switch
- Analogy: A Boolean type has two possible values: true or false. <!-- .element: class="fragment" data-fragment-index="2" -->
- Real-life Use: Booleans are used in real life for decisions that have a binary outcome <!-- .element: class="fragment" data-fragment-index="3" -->


# Arrays
## Grocery List
- Analogy: An array in programming stores multiple items. <!-- .element: class="fragment" data-fragment-index="2" -->
- Real-life Use: Arrays reflect any collection of items <!-- .element: class="fragment" data-fragment-index="3" -->


# Objects
## Personal Information
- Analogy: In programming, an object is a collection of properties that are related <!-- .element: class="fragment" data-fragment-index="2" -->
- Real-life Use: Objects are mirrored in the way we organize information in real life <!-- .element: class="fragment" data-fragment-index="3" -->


# Data Processing Technologies
- Batch Processing (e.g., Hadoop MapReduce)
- Real-time Processing (e.g., Apache Storm, Apache Flink)
- Stream Processing (e.g., Kafka Streams)

Speaker Notes:

- Batch Processing: Suitable for processing large volumes of data when time isn't a critical factor.
- Real-time Processing: Necessary when data needs to be processed quickly to produce immediate results.
- Stream Processing: Designed for data that continuously flows, allowing for incremental responses.


# Challenges in Data Storage and Processing
- Scalability
- Security
- Data Integrity
- Accessibility

Speaker Notes:

- Scalability: Handling growing data without performance loss.
- Security: Protecting data from unauthorized access and breaches.
- Data Integrity: Ensuring accuracy and consistency of data over its lifecycle.
- Accessibility: Making data available to users and systems as needed.


# Theory & Applications

- Play pacman https://www.tensorflow.org/js
- bodypix, mobilenet, segment-anything
- essence of linear algebra matrix multiplication
- essence of calculus finding the minimum
- gradient decent
