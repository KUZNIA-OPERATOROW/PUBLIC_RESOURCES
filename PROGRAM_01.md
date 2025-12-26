# _PROGRAM_01: AI_ENGINEERING_BOOTCAMP_

Kompletny, 12-modułowy bootcamp łączący zaawansowany Python, LLM Engineering oraz budowę autonomicznych systemów agentowych. Od fundamentów do produkcyjnych rozwiązań AI.

---

## 🚀 FAZA 1: FUNDAMENTY (Python & AI Basics)

### **Moduł 1: Wprowadzenie do Modern AI Engineering**

Ikona do wstawienia dla potwierdzenia statusu: ✅

| Lekcja | Temat Główny                                                      | Tech Stack                      | Status |
| ------ | ----------------------------------------------------------------- | ------------------------------- | ------ |
| **01** | Kim jest AI Engineer w 2025? (Rola Solo Operatora w ekosystemie)  | `koncepcje`                     |        |
| **02** | Dlaczego Lean AI? Wady frameworków "heavy-abstraction"            | `architektura`                  |        |
| **03** | Przegląd stacku: PydanticAI, Google SDK, Langfuse, Qdrant         | `pydantic-ai, gemini, langfuse` |        |
| **04** | Modele lokalne (Ollama, DeepSeek) vs Chmura w pełni kontrolowana  | `ollama, deepseek`              |        |
| **05** | Cykl życia aplikacji AI: Od notebooka do mikroserwisu             | `jupyter, fastapi`              |        |
| **06** | Strategia "Code-First": Budowanie systemów, które przetrwają lata | `best-practices`                |        |

**Oczekiwane Wyniki:**

- Zdefiniujesz swoją ścieżkę jako Modern AI Engineer i zrozumiesz rolę w organizacji
- Zrozumiesz dlaczego podejście 'lean' wygrywa z ciężkimi frameworkami
- Skonfigurujesz swój pierwszy profesjonalny stack technologiczny do pracy z modelami

---

### **Moduł 2: Zaawansowany Python dla AI**

| Lekcja | Temat Główny                                              | Tech Stack              | Status |
| ------ | --------------------------------------------------------- | ----------------------- | ------ |
| **01** | Typowanie statyczne: Type Hints i Mypy w usługach AI      | `typing, mypy`          |        |
| **02** | Zaawansowane typowanie: Generics i TypedDict w AI         | `typing`                |        |
| **03** | Programowanie asynchroniczne (asyncio) – wprowadzenie     | `asyncio`               |        |
| **04** | Fundamenty szybkich agentów: Event Loop i Taski           | `asyncio`               |        |
| **05** | Programowanie obiektowe (OOP) w inżynierii AI             | `python-oop`            |        |
| **06** | Podejście funkcyjne vs obiektowe: Kiedy co stosować?      | `functional-python`     |        |
| **07** | Modułowość: Projektowanie "pluggable" systemów agentowych | `design-patterns`       |        |
| **08** | Zarządzanie zależnościami i architektura czystego kodu    | `clean-architecture`    |        |
| **09** | Obsługa błędów i Custom Exceptions w przepływach LLM      | `exception-handling`    |        |
| **10** | Strategie retries i odporność systemów AI                 | `tenacity, backoff`     |        |
| **11** | Optymalizacja wydajności kodu Pythona dla obciążeń AI     | `profiling, cProfile`   |        |
| **12** | Praca z dużymi zbiorami danych i leniwe ładowanie         | `generators, itertools` |        |

**Oczekiwane Wyniki:**

- Napiszesz w pełni typowany i bezpieczny kod Python dla systemów agentowych
- Opanujesz asynchroniczność (asyncio) niezbędną do szybkich interakcji z LLM
- Zbudujesz fundament pod modułowe komponenty AI, które łatwo skalować

---

## 🧠 FAZA 2: LLM CORE & DATA FOUNDATIONS

### **Moduł 3: Pydantic – Fundament Struktury Danych**

| Lekcja | Temat Główny                                                   | Tech Stack            | Status |
| ------ | -------------------------------------------------------------- | --------------------- | ------ |
| **01** | Pydantic jako "Single Source of Truth" w systemach AI          | `pydantic`            |        |
| **02** | Definiowanie schematów wyjściowych (Structured Outputs)        | `pydantic`            |        |
| **03** | Zaawansowana walidacja: Gwarancja jakości danych z LLM         | `pydantic-validators` |        |
| **04** | Serializacja i deserializacja złożonych obiektów JSON          | `pydantic`            |        |
| **05** | Self-correction loop: Automatyczna naprawa błędów formatowania | `pydantic`            |        |
| **06** | Integracja Pydantic z PydanticAI oraz Google SDK               | `pydantic-ai, gemini` |        |

**Oczekiwane Wyniki:**

- Wdrożysz Pydantic jako centralny punkt prawdy o danych w swojej aplikacji
- Uzyskasz gwarancję struktury (Structured Outputs) z dowolnego modelu LLM
- Zautomatyzujesz naprawę błędnych odpowiedzi modeli poprzez pętle walidacji

---

### **Moduł 4: LLM Science & Prompt Engineering**

| Lekcja | Temat Główny                                                  | Tech Stack           | Status |
| ------ | ------------------------------------------------------------- | -------------------- | ------ |
| **01** | Architektura transformera: Wagi, warstwy i mechanizm uwagi    | `transformers`       |        |
| **02** | Reasoning Models: Modele klasy DeepSeek-R1 oraz O1            | `deepseek, openai`   |        |
| **03** | Techniki zaawansowane: Chain-of-Thought i Few-shot            | `prompt-engineering` |        |
| **04** | System Routing i inteligentne kierowanie promptów             | `semantic-routing`   |        |
| **05** | Zarządzanie oknem kontekstowym i problem "lost in the middle" | `context-management` |        |
| **06** | Fine-tuning vs RAG: Kiedy faktycznie trenować własny model?   | `fine-tuning, rag`   |        |

**Oczekiwane Wyniki:**

- Zrozumiesz wewnętrzne działanie najnowszych modeli klasy Reasoning
- Opanujesz techniki promptingu, które wyciskają 100% z dużych modeli
- Samodzielnie ocenisz, czy dany problem wymaga RAG, czy modyfikacji wag modelu

---

## 🔧 FAZA 3: NATIVE SDKs & AGENT FRAMEWORKS

### **Moduł 5: Google Generative AI SDK – Natywna Integracja**

| Lekcja | Temat Główny                                                    | Tech Stack            | Status |
| ------ | --------------------------------------------------------------- | --------------------- | ------ |
| **01** | Praca z rodziną Gemini (Flash, Pro) przez natywne SDK           | `google-generativeai` |        |
| **02** | Autentykacja i limitowanie zapytań w profesjonalnym SDK         | `google-auth`         |        |
| **03** | Konfiguracja System Instructions dla modeli Google              | `gemini`              |        |
| **04** | Safety Settings i precyzyjne filtrowanie treści                 | `gemini-safety`       |        |
| **05** | Native Function Calling: Pozwól Gemini wywoływać Twój kod       | `function-calling`    |        |
| **06** | Projektowanie stabilnych narzędzi (Tools) dla Gemini            | `gemini-tools`        |        |
| **07** | Context Caching: Drastyczne obniżanie kosztów (Długi Kontekst)  | `gemini-caching`      |        |
| **08** | Zarządzanie cyklem życia cache'u w środowisku produkcyjnym      | `cache-management`    |        |
| **09** | Multimodalność: Analiza obrazów i wideo w jednym nurcie         | `gemini-multimodal`   |        |
| **10** | Przetwarzanie dokumentów PDF przez natywne API                  | `gemini-pdf`          |        |
| **11** | Batch API: Przetwarzanie masowe danych poza czasem rzeczywistym | `gemini-batch`        |        |
| **12** | Optymalizacja kosztów i monitoring procesów wsadowych           | `batch-monitoring`    |        |

**Oczekiwane Wyniki:**

- Wykorzystasz pełną moc modeli Gemini (2M tokenów) przez natywne SDK Google
- Wdrożysz Function Calling, pozwalając modelowi operować na Twojej logice biznesowej
- Drastycznie obniżysz koszty infrastruktury dzięki mechanizmowi Context Caching

---

### **Moduł 6: PydanticAI – Budowa Profesjonalnych Agentów**

| Lekcja | Temat Główny                                                      | Tech Stack             | Status |
| ------ | ----------------------------------------------------------------- | ---------------------- | ------ |
| **01** | Architektura PydanticAI: Agenci oparci na typach danych           | `pydantic-ai`          |        |
| **02** | Konfiguracja i inicjalizacja środowiska PydanticAI                | `pydantic-ai`          |        |
| **03** | Definiowanie narzędzi agenta (@agent.tool) z walidacją            | `pydantic-ai-tools`    |        |
| **04** | Integracja narzędzi zewnętrznych i walidacja typów                | `pydantic-ai`          |        |
| **05** | Dependency Injection: Bezpieczne przekazywanie baz danych i API   | `dependency-injection` |        |
| **06** | Zarządzanie stanem i wstrzykiwanie zależności w agentach          | `state-management`     |        |
| **07** | Multi-agent systems: Strategie delegacji zadań (Hand-off)         | `multi-agent`          |        |
| **08** | Koordynacja pracy zespołu agentów i wymiana informacji            | `agent-coordination`   |        |
| **09** | Zarządzanie logiką decyzyjną i "myśleniem" agenta                 | `agent-reasoning`      |        |
| **10** | Dynamiczne instrukcje systemowe w PydanticAI                      | `dynamic-instructions` |        |
| **11** | Testowanie agentów: Unit testy dla zachowań niedeterministycznych | `pytest, mocking`      |        |
| **12** | Ewaluacja i debugowanie agentów na poziomie kodu                  | `debugging-agents`     |        |

**Oczekiwane Wyniki:**

- Zbudujesz zaawansowanych agentów w najbardziej pożądanym frameworku 2025 roku
- Wdrożysz bezpieczne wstrzykiwanie zależności (DI) w logice agentycznej
- Stworzysz systemy wieloagentowe potrafiące płynnie przekazywać zadania

---

## 🔄 FAZA 4: ORCHESTRATION & OBSERVABILITY

### **Moduł 7: Orkiestracja Workflows i State Management**

| Lekcja | Temat Główny                                                    | Tech Stack               | Status |
| ------ | --------------------------------------------------------------- | ------------------------ | ------ |
| **01** | Projektowanie przepływów jako Maszyny Stanów (FSM)              | `state-machines`         |        |
| **02** | Definiowanie grafów stanów i reguł przejść w AI Workflows       | `workflow-graphs`        |        |
| **03** | Human-in-the-loop: Punkty kontrolne w procesach AI              | `hitl-patterns`          |        |
| **04** | Interwencja ludzka: Edycja stanów i akceptacja danych           | `human-feedback`         |        |
| **05** | Zarządzanie długotrwałą pamięcią sesji w PostgreSQL             | `postgresql, sqlalchemy` |        |
| **06** | Projektowanie schematów baz danych pod pamięć agentów           | `database-design`        |        |
| **07** | Architektura Routerów: Inteligentne kierowanie zadań do modeli  | `semantic-router`        |        |
| **08** | Kierowanie zapytaniami na podstawie intencji (Semantic Routing) | `intent-classification`  |        |
| **09** | Obsługa stanów przejściowych i persystencja w systemach         | `state-persistence`      |        |
| **10** | Backup i odtwarzanie stanów agenta w przypadku awarii           | `disaster-recovery`      |        |
| **11** | Optymalizacja przepływów pod kątem opóźnień (Latency)           | `performance-tuning`     |        |
| **12** | Redukcja narzutu czasowego przy orkiestracji wielu modeli       | `optimization`           |        |

**Oczekiwane Wyniki:**

- Zaprojektujesz stabilne i przewidywalne workflows oparte na maszynach stanów
- Zaimplementujesz mechanizmy kontrolne wymagające akceptacji człowieka
- Skutecznie zarządzisz pamięcią sesji i persystencją danych w bazach SQL

---

### **Moduł 8: Observability z Langfuse**

| Lekcja | Temat Główny                                                    | Tech Stack               | Status |
| ------ | --------------------------------------------------------------- | ------------------------ | ------ |
| **01** | Tracing: Śledzenie każdego kroku agenta w czasie rzeczywistym   | `langfuse`               |        |
| **02** | Integracja Langfuse z aplikacjami Python i PydanticAI           | `langfuse-sdk`           |        |
| **03** | Analiza kosztów (Token usage) i wydajności finansowej modeli    | `cost-tracking`          |        |
| **04** | Wyliczanie kosztu na użytkownika i na operację                  | `cost-analytics`         |        |
| **05** | LLM-as-a-judge: Automatyczna ewaluacja jakości odpowiedzi       | `llm-evaluation`         |        |
| **06** | Projektowanie własnych sędziów (Evaluators) do jakości danych   | `custom-evaluators`      |        |
| **07** | Debugowanie produkcji: Szybka identyfikacja "złych" ścieżek     | `production-debugging`   |        |
| **08** | Analiza wizualna śladów (Traces) i identyfikacja wąskich gardeł | `trace-analysis`         |        |
| **09** | Dataset Management: Budowanie bazy testowej (Gold Datasets)     | `dataset-management`     |        |
| **10** | Wykonywanie eksperymentów i porównywanie wersji promptów        | `a-b-testing`            |        |
| **11** | Feedback Loop: Integracja ocen użytkowników z observability     | `user-feedback`          |        |
| **12** | Budowa systemu ciągłego ulepszania na podstawie danych z logów  | `continuous-improvement` |        |

**Oczekiwane Wyniki:**

- Uzyskasz pełną widoczność (Observability) nad każdym zapytaniem Twoich agentów
- Wdrożysz proces automatycznej ewaluacji jakości bez udziału człowieka
- Zbudujesz bazę Gold Datasets służącą do profesjonalnych testów regresji

---

## 🗄️ FAZA 5: VECTOR DATABASES & RAG

### **Moduł 9: Suwerenny RAG z Qdrant Vector DB**

| Lekcja | Temat Główny                                                      | Tech Stack              | Status |
| ------ | ----------------------------------------------------------------- | ----------------------- | ------ |
| **01** | Dlaczego Qdrant? Architektura wektorowa dla skali produkcyjnej    | `qdrant`                |        |
| **02** | Instalacja, konfiguracja i skalowanie Qdrant (Docker)             | `qdrant, docker`        |        |
| **03** | Inżynieria chunkingu i strategie inteligentnego podziału tekstu   | `chunking-strategies`   |        |
| **04** | Embedding strategies: Dobór modelu osadzania do języka polskiego  | `sentence-transformers` |        |
| **05** | Hybrydowe wyszukiwanie: Łączenie wektorów z pełnotekstowym BM25   | `hybrid-search`         |        |
| **06** | Konfiguracja Sparse Vectors w Qdrant dla precyzji słów kluczowych | `sparse-vectors`        |        |
| **07** | Reranking: Drastyczna poprawa trafności dzięki Cross-Encoders     | `cross-encoder`         |        |
| **08** | Implementacja warstwy Reranker w potoku pobierania danych         | `reranking-pipeline`    |        |
| **09** | Filtrowanie metadanych i zaawansowane kolekcje w Qdrant           | `metadata-filtering`    |        |
| **10** | Filtry dynamiczne i payload management w bazach wektorowych       | `payload-management`    |        |
| **11** | Projekt: Prywatna baza wiedzy działająca w 100% lokalnie          | `local-rag`             |        |
| **12** | Bezpieczny RAG On-premise zapewniający suwerenność danych         | `on-premise-deployment` |        |

**Oczekiwane Wyniki:**

- Opanujesz bazę Qdrant – rynkowy standard dla profesjonalnych rozwiązań AI
- Zaimplementujesz hybrydowe wyszukiwanie o najwyższej precyzji rynkowej
- Zbudujesz profesjonalny RAG działający w 100% lokalnie, bez wycieku danych

---

## 🚢 FAZA 6: DEPLOYMENT & PRODUCTION

### **Moduł 10: Deployment & MLOps (FastAPI + Docker)**

| Lekcja | Temat Główny                                                        | Tech Stack                 | Status |
| ------ | ------------------------------------------------------------------- | -------------------------- | ------ |
| **01** | Budowa asynchronicznego API w FastAPI dla systemów AI               | `fastapi`                  |        |
| **02** | Projektowanie schematów wejścia/wyjścia (Pydantic) dla API          | `fastapi, pydantic`        |        |
| **03** | Konteneryzacja: Optymalizacja obrazów Docker (GPU vs CPU)           | `docker`                   |        |
| **04** | Zarządzanie warstwami i multi-stage builds dla mikroserwisów        | `docker-multistage`        |        |
| **05** | Docker Compose Tactical: Pełny stos (App + Qdrant + Monitoring)     | `docker-compose`           |        |
| **06** | Konfiguracja sieci i izolacja usług w Dockerze                      | `docker-networking`        |        |
| **07** | Skalowanie agentów: Workers, Queues (Redis) i Load Balancing        | `redis, celery`            |        |
| **08** | Obsługa kolejek zadań dla długo trwających przemyśleń agenta        | `task-queues`              |        |
| **09** | Bezpieczeństwo API: Autoryzacja i Rate Limiting w AI                | `api-security`             |        |
| **10** | Zabezpieczanie przed atakami typu Prompt Injection na poziomie kodu | `prompt-injection-defense` |        |
| **11** | CI/CD dla AI: Automatyzacja testów i wdrożeń (GitHub Actions)       | `github-actions`           |        |
| **12** | Automatyczne budowanie obrazów i deployment do chmury               | `ci-cd-automation`         |        |

**Oczekiwane Wyniki:**

- Wystawisz swoje agenty jako skalowalne, asynchroniczne API produkcyjne
- Zoptymalizujesz kontenery Docker pod kątem specyficznych wymagań AI
- Wdrożysz pełny cykl MLOps zapewniający bezpieczeństwo i ciągłość działania

---

## 🔌 FAZA 7: ADVANCED PROTOCOLS

### **Moduł 11: Model Context Protocol (MCP)**

| Lekcja | Temat Główny                                                    | Tech Stack          | Status |
| ------ | --------------------------------------------------------------- | ------------------- | ------ |
| **01** | MCP: Nowy standard łączenia LLM z danymi (2025)                 | `mcp`               |        |
| **02** | Architektura serwerów MCP: Host vs Client                       | `mcp-architecture`  |        |
| **03** | Protokół komunikacji i standardy JSON-RPC                       | `json-rpc`          |        |
| **04** | Budowa własnego serwera MCP w Pythonie od podstaw               | `mcp-python`        |        |
| **05** | Łączenie LLM z lokalnymi bazami danych i systemem plików        | `mcp-integrations`  |        |
| **06** | Projektowanie bezpiecznych mostów danych (Data Bridges)         | `data-bridges`      |        |
| **07** | Integracja MCP z systemami operacyjnymi i narzędziami lokalnymi | `os-integration`    |        |
| **08** | Użycie MCP w profesjonalnych środowiskach IDE (Cursor, VS Code) | `ide-integration`   |        |
| **09** | Rozszerzanie możliwości agentów przez dynamiczne zasoby         | `dynamic-resources` |        |

**Oczekiwane Wyniki:**

- Opanujesz Model Context Protocol – standard, który zmienia sposób dostępu do danych
- Zbudujesz autorskie serwery MCP obsługujące Twój lokalny system plików i bazy
- Zintegrujesz swoje agenty z zewnętrznymi narzędziami w ustandaryzowany sposób

---

## 🏆 FAZA 8: CAPSTONE PROJECT

### **Moduł 12: Projekt Końcowy: RODO_EXPERT_AI**

| Lekcja | Temat Główny                                                  | Tech Stack            | Status |
| ------ | ------------------------------------------------------------- | --------------------- | ------ |
| **01** | System Design: Projektowanie architektury całego rozwiązania  | `system-design`       |        |
| **02** | Dobór technologii i modelowanie przepływów biznesowych        | `technology-stack`    |        |
| **03** | Implementacja lokalnego RAG z użyciem Qdrant dla dokumentów   | `qdrant, rag`         |        |
| **04** | Budowa systemu agentów specjalistycznych w PydanticAI         | `pydantic-ai`         |        |
| **05** | Implementacja zaawansowanej logiki weryfikacji w FastAPI      | `fastapi, validation` |        |
| **06** | Tworzenie interfejsu i warstwy komunikacji z użytkownikiem    | `ui-layer`            |        |
| **07** | Wdrożenie pełnego monitoringu Langfuse w kontenerze Docker    | `langfuse, docker`    |        |
| **08** | Testowanie E2E systemu pod kątem halucynacji i bezpieczeństwa | `e2e-testing`         |        |
| **09** | Przygotowanie dokumentacji inżynierskiej projektu końcowego   | `documentation`       |        |
| **10** | Optymalizacja wydajności i kosztów końcowego rozwiązania      | `optimization`        |        |
| **11** | Roadmapa kariery: Jak zostać Architektem Systemów AI          | `career-path`         |        |
| **12** | Finalna prezentacja projektu i podsumowanie bootcampu         | `presentation`        |        |

**Oczekiwane Wyniki:**

- Zrealizujesz system RODO_EXPERT_AI łączący wszystkie technologie kursu
- Zbudujesz portfolio inżynierskie, które otworzy Ci drzwi do topowych firm AI
- Zyskasz pewność w projektowaniu kompleksowych systemów agentowych od zera

---

## 📊 Podsumowanie Bootcampu

- **Całkowity czas nauki:** 2x / tydz. (90–120 min) x 5 mc = 63-84 godzin
- **Liczba modułów:** 12
- **Liczba lekcji:** 123

### **Stack Technologiczny:**

**Core Python:**

- `asyncio, typing, mypy`
- `pydantic, pydantic-ai`
- `fastapi`

**LLM & AI:**

- `google-generativeai (Gemini)`
- `transformers, sentence-transformers`
- `ollama, deepseek`

**Vector DB & RAG:**

- `qdrant`
- `cross-encoder`

**Observability & Testing:**

- `langfuse`
- `pytest`

**MLOps & Deployment:**

- `docker, docker-compose`
- `redis, celery`
- `github-actions`

**Data & State:**

- `postgresql, sqlalchemy`
- `state-machines`

**Protocols:**

- `mcp (Model Context Protocol)`

### **Po ukończeniu będziesz potrafić:**

✅ Projektować i wdrażać zaawansowane systemy agentowe  
✅ Budować skalowalne API dla aplikacji AI  
✅ Implementować RAG z pełną kontrolą nad danymi  
✅ Monitorować i optymalizować koszty produkcyjnych systemów  
✅ Tworzyć bezpieczne, suwerenne rozwiązania AI  
✅ Pracować jako Modern AI Engineer lub Architekt Systemów AI

---

**Author:** TakzenAI: Krzysztof Pika
