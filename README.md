<img src = "https://camo.githubusercontent.com/3cefee189432defff4cb59838ead898a2bd661cd4b475e25391c87edd2241782/68747470733a2f2f7374617469632e7769787374617469632e636f6d2f6d656469612f3038316535625f35353533383033666465656334636262383137656434653835653138393962327e6d76322e706e672f76312f66696c6c2f775f3234362c685f3130362c616c5f632c715f38352c75736d5f302e36365f312e30305f302e30312c656e635f6175746f2f313025323041636164656d7925323046412d30322532302d2532307472616e73706172656e742532306261636b67726f756e642532302d25323063726f707065642e706e67">

# LLM Finetuning: Generate Amharic based creative text Ad contents
***

### Project Overview

Given Telegram's growing prominence as a messaging platform, AiQEM (an African startup focused on AI and Blockchain business solutions) needs to adjust its advertising strategy to better fit this ever-changing ecosystem. 

This project intends to improve the effectiveness of their promotional efforts by integrating powerful AI capabilities for Amharic text manipulation, in particular creating an Amharic RAG pipeline that will help generate Amharic based creative text Ad contents given campaign information such as brief (brand and product information) and the content history of a telegram channel. 

This project makes sure that their advertisements are both catchy and relevant to the Telegram community. To achieve this, the technology is required to have quality **amharic text embedding** and **text generation** capability.

### Project Guide

After choosng a suitable opensource LLM model with appropriatevwith better trainings and one that should already have a capability to embed amharic texts, a dataset will be utilized to finetune it further to deliver the business needs. That is made possible by using an efficient RAG system to help generate ideal Ad contents in Amharic. The data contains exported Telegram messages in JSON format representing 25 telegram public channels. The structure of the JSON object provides information about the sender, timestamps, message types, and any associated multimedia content.

In the end, A RAG pipline will be set for the final Ad generation which will be hosted on Streamlit/React.

### Approaches and Techniques

The data seems to be a dump and needs to get cleaned and labeled so as to get the desired and ideal dataset to finetune the opensource model. After that this can be used as a model so it is possbile to generate a more likable, tailored and successful Ad.
