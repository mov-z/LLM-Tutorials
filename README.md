# LLM-Tutorials

누구나 쉽게 따라할 수 있는 다양한 LLM(Language Model) 관련 예제를 소개하고 실습할 수 있는 공간입니다. 

점점 많은 예제를 추가할 예정이니 많은 관심 부탁드립니다 🤗

## 📌 OpenAI
- [OpenAI_API_call](OpenAI/OpenAI_API_call.ipynb) [Colab]
    - OpenAI API를 사용해 보고 싶다면?
- [OpenAI_RAG_ChatAPI](OpenAI/OpenAI_RAG_ChatAPI.ipynb) [Colab]
    - **Chat API**와 **ChromaDB**를 사용하여, 간단한 **RAG** 기능을 구현해보는 예제
- [OpenAI_RAG_Llama_index](OpenAI/OpenAI_RAG_Llama_index.ipynb) [Colab]
    - **OpenAI**와 **Llama-index**를 이용한, 조금 더 다양한 기능의 **RAG** 기능을 구현해보는 예제
    - **ChromaDB**, **OpenAI Embedding 모델** 사용
    - 고급 검색 및 후처리 적용 (**`similarity_top_k`**, **`similarity_cutoff`** 사용)


## 📌 오픈소스 LLM
### ✅ Basic Chat
- [huggingface_LLM_chat](Open-source_LLM/basic_chat/huggingface_LLM_chat.ipynb) [Colab]
  - Huggingface Open-source LLM으로 **기본적인 질의 응답** 기능을 구현하는 예제
- [langchain_ollama_QnA](Open-source_LLM/basic_chat/langchain_ollama_QnA.ipynb)
  - Langchain과 Ollama를 이용하여 기본적인 **Q&A 시스템**을 구현하는 예제 (대화 내용 기억 X)
- [langchain_ollama_chatbot](Open-source_LLM/basic_chat/langchain_ollama_chatbot.ipynb)
  - Langchain과 Ollama를 이용하여 **대화형 챗봇**을 구현하는 예제 (대화 내용 기억 O)
- [langchain_ollama_prompting](Open-source_LLM/basic_chat/langchain_ollama_prompting.ipynb)
  - Langchain과 Ollama를 이용하여 기본적인 **프롬프트 엔니어링**을 구현하는 예제

### ✅ RAG
- [llama-index_huggingface_RAG_basicce_llama-index_RAG_basic](Open-source_LLM/rag/llama-index_huggingface_RAG_basic.ipynb) [Colab]
  - llama-index와 **huggingface** LLM을 이용하여 **기본적인 RAG** 기능을 구현하는 예제
- [llama-index_ollama_RAG_basic](Open-source_LLM/rag/llama-index_ollama_RAG_basic.ipynb)
  - llama-index와 **ollama** LLM을 이용하여 **기본적인 RAG** 기능을 구현하는 예제


## 🙋🏻‍♂️ 추가 설명 
- 예제는 구글 코랩 환경과 로컬 주피터 노트북 환경으로 구성되어 있어요. 
- 로컬 주피터 노트북 환경의 경우 개발 환경 세팅(라이브러리 설치 등)가 필요합니다.
- Google Colab 환경의 예제는 [Colab] 표기