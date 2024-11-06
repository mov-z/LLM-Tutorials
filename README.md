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
<br>


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
<br>

 
## 📌 공부 자료
- [LangChain 한국어 튜토리얼](https://github.com/teddylee777/langchain-kr)
    - Teddy Lee님이 운영하는 레포지토리로 다양한 랭체인 한국어 튜토리얼을 제공해요 (1.2k stars) 
- [Large Language Model Course](https://github.com/mlabonne/llm-course)
    - 다양한 LLM 공부 자료와 LLM Scientist, LLM Engineer 로드맵을 제공해요 (38.8k stars)
- [Building A Generative AI Platform](https://huyenchip.com/2024/07/25/genai-platform.html)
    - LLM 플랫폼을 구축하는 과정에 대한 포괄적인 설명을 제공하는 포스트예요.
    - 이 포스트는 기업들이 생성적 AI 애플리케이션을 어떻게 배포하는지에 대한 공통된 아키텍처와 그 구성 요소들을 다루고 있어요.
    - 기본적인 구조에서 출발하여, 필요에 따라 'Enhance Context', 'Put in Guardrails', 'Add Model Router and Gateway', 'Reduce Latency with Cache'와 같은 컴포넌트들을 추가하는 방법을 설명해줘요.
<br>


## 🙋🏻‍♂️ 추가 설명 
- 예제는 구글 코랩 환경과 로컬 주피터 노트북 환경으로 구성되어 있어요. 
- 로컬 주피터 노트북 환경의 경우 개발 환경 세팅(라이브러리 설치 등)가 필요합니다.
- Google Colab 환경의 예제는 [Colab] 표기
