# _PROGRAM_02: FINANCIAL_AI_ENGINEERING_

Kompletny, 12-modułowy bootcamp łączący Quant Finance, Machine Learning oraz budowę autonomicznych systemów tradingowych. Od fundamentów do produkcyjnego funduszu inwestycyjnego.

---

## 🚀 FAZA 1: FUNDAMENTY (Data Engineering & Financial RAG)

### **Moduł 1: Financial Data Engineering (uv & Pydantic)**

Ikona do wstawienia dla potwierdzenia statusu: ✅

| Lekcja | Temat Główny                                                             | Tech Stack                  | Status |
| ------ | ------------------------------------------------------------------------ | --------------------------- | ------ |
| **01** | Środowisko Quant: Zarządzanie pakietami przez uv i izolacja projektów    | `uv, python`                |        |
| **02** | Inżynieria danych (ETL): Pobieranie danych giełdowych                    | `yfinance, alpaca, polygon` |        |
| **03** | Strict Validation: Modele Pydantic dla walut, tickerów i transakcji      | `pydantic`                  |        |
| **04** | Async Data Stream: Budowa asynchronicznych kolektorów danych             | `fastapi, asyncio`          |        |
| **05** | Projektowanie schematów SQL dla szeregów czasowych                       | `postgresql`                |        |
| **06** | PROJEKT #1: Pipeline danych giełdowych z walidacją w czasie rzeczywistym | `pydantic, fastapi`         |        |

**Oczekiwane Wyniki:**

- Zbudujesz wydajny i bezpieczny rurociąg danych finansowych z pełną walidacją
- Opanujesz ultraszybkie zarządzanie pakietami za pomocą 'uv'
- Zrozumiesz architekturę baz danych pod szeregi czasowe (Time-Series)

---

### **Moduł 2: Financial RAG: Analiza Dokumentów (Qdrant)**

| Lekcja | Temat Główny                                                          | Tech Stack           | Status |
| ------ | --------------------------------------------------------------------- | -------------------- | ------ |
| **01** | Architektura RAG dla finansów: Dlaczego FAISS to za mało?             | `rag-architecture`   |        |
| **02** | Qdrant Vector DB: Budowa bazy wiedzy o raportach rocznych             | `qdrant`             |        |
| **03** | Inżynieria Chunkingu: Parsowanie tabel finansowych                    | `pdfplumber, gemini` |        |
| **04** | Semantic Search: Wyszukiwanie sentymentu i ryzyk w prospektach        | `semantic-search`    |        |
| **05** | Hybrydowe wyszukiwanie: Łączenie wektorów z metadanymi finansowymi    | `hybrid-search`      |        |
| **06** | PROJEKT #2: "Earnings Call Analyzer" – RAG na transkrypcjach zarządów | `qdrant, gemini`     |        |

**Oczekiwane Wyniki:**

- Zautomatyzujesz wydobywanie kluczowych informacji z setek stron dokumentacji finansowej
- Zbudujesz suwerenną bazę wiedzy o spółkach giełdowych
- Opanujesz precyzyjne parsowanie tabel, co jest 'świętym graalem' RAG w finansach

---

## 🧠 FAZA 2: MACHINE LEARNING & QUANT ANALYSIS

### **Moduł 3: Machine Learning w Finansach**

| Lekcja | Temat Główny                                                       | Tech Stack              | Status |
| ------ | ------------------------------------------------------------------ | ----------------------- | ------ |
| **01** | EDA: Wykrywanie anomalii i czyszczenie "brudnych" danych rynkowych | `pandas, seaborn`       |        |
| **02** | Modele regresyjne: Przewidywanie zwrotów                           | `sklearn, ridge, lasso` |        |
| **03** | Klasyfikacja: AI decydujące o sygnale KUP/SPRZEDAJ                 | `xgboost, lightgbm`     |        |
| **04** | Feature Engineering: Budowa wskaźników technicznych                | `pandas, ta-lib`        |        |
| **05** | Pipeline'y ML: Automatyzacja treningu modeli finansowych           | `sklearn-pipeline`      |        |
| **06** | PROJEKT #3: Demand Forecasting – Prognozowanie popytu i płynności  | `xgboost`               |        |

**Oczekiwane Wyniki:**

- Zastosujesz topowe algorytmy Gradient Boosting do przewidywania ruchów rynkowych
- Zrozumiesz, jak inżynieria cech (features) wpływa na zyskowność Twoich modeli
- Stworzysz potoki ML, które same trenują się na nowych danych rynkowych

---

### **Moduł 4: Quantitative Risk Management**

| Lekcja | Temat Główny                                                          | Tech Stack           | Status |
| ------ | --------------------------------------------------------------------- | -------------------- | ------ |
| **01** | Statystyka rynkowa: Rozkłady, skośność i "Grube Ogony"                | `scipy, numpy`       |        |
| **02** | Korelacja dynamiczna: Macierze korelacji i Rolling Correlation        | `pandas, seaborn`    |        |
| **03** | Metryki Quant: Sharpe Ratio, Sortino, Drawdown, Beta i Alpha          | `numpy`              |        |
| **04** | Value at Risk (VaR): Obliczanie ryzyka Monte Carlo i Historyczna      | `scipy, monte-carlo` |        |
| **05** | Teoria Markowitza: Optymalizacja portfela (Efficient Frontier)        | `scipy, cvxpy`       |        |
| **06** | PROJEKT #4: Risk Manager Dashboard – Wizualizacja ekspozycji portfela | `matplotlib, plotly` |        |

**Oczekiwane Wyniki:**

- Wdrożysz matematyczne standardy zarządzania ryzykiem stosowane w funduszach hedge
- Zoptymalizujesz portfel pod kątem najlepszego stosunku zysku do ryzyka
- Zrozumiesz zagrożenia płynące z nietypowych rozkładów statystycznych cen

---

## 📈 FAZA 3: TIME SERIES & FINANCIAL AGENTS

### **Moduł 5: Time Series & Modern Forecasting**

| Lekcja | Temat Główny                                                      | Tech Stack          | Status |
| ------ | ----------------------------------------------------------------- | ------------------- | ------ |
| **01** | Klasyka szeregów czasowych: ARIMA, GARCH (prognoza zmienności)    | `statsmodels, arch` |        |
| **02** | Deep Learning w TS: Time-Series Transformers i architektury NHITS | `neuralforecast`    |        |
| **03** | Detekcja reżimu rynkowego: Czy jesteśmy w hossie, czy w bessie?   | `regime-detection`  |        |
| **04** | Wektorowy Backtesting: Szybka weryfikacja strategii               | `vectorbt`          |        |
| **05** | Walk-Forward Analysis: Unikanie błędu przeuczenia                 | `walk-forward`      |        |
| **06** | PROJEKT #5: Volatility Forecaster – System prognozowania krachów  | `arch, garch`       |        |

**Oczekiwane Wyniki:**

- Wykorzystasz najnowsze architektury Transformers do pracy z czasem
- Zbudujesz profesjonalny silnik do testowania strategii (Backtesting)
- Zrozumiesz, jak prognozować okresy podwyższonej zmienności na giełdzie

---

### **Moduł 6: PydanticAI Financial Agents**

| Lekcja | Temat Główny                                                                 | Tech Stack             | Status |
| ------ | ---------------------------------------------------------------------------- | ---------------------- | ------ |
| **01** | PydanticAI Architecture: Budowa agentów finansowych sterowanych typami       | `pydantic-ai`          |        |
| **02** | Tools for Agents: Jak agent wywołuje funkcje matematyczne w Pythonie         | `pydantic-ai-tools`    |        |
| **03** | Dependency Injection: Przekazywanie sesji giełdowych i kluczy API            | `dependency-injection` |        |
| **04** | Stateful Agents: Zarządzanie stanem portfela bez frameworków grafowych       | `state-management`     |        |
| **05** | Multi-Agent Systems: Zespół (Analityk Fundamentalny + Quant + Krytyk)        | `multi-agent`          |        |
| **06** | PROJEKT #6: "Autonomous Research Agent" – Agent piszący raporty inwestycyjne | `pydantic-ai`          |        |

**Oczekiwane Wyniki:**

- Stworzysz zespół autonomicznych agentów, którzy samodzielnie analizują rynek
- Wdrożysz bezpieczny przepływ danych finansowych do myślenia agenta
- Opanujesz orkiestrację agentów w najbardziej stabilnym frameworku 2025 roku

---

## 🤖 FAZA 4: FINE-TUNING & OBSERVABILITY

### **Moduł 7: Fine-Tuning Modelów Finansowych**

| Lekcja | Temat Główny                                                            | Tech Stack           | Status |
| ------ | ----------------------------------------------------------------------- | -------------------- | ------ |
| **01** | Teoria: Quantization (GGUF/EXL2) i LoRA dla modeli finansowych          | `peft, lora`         |        |
| **02** | Przygotowanie danych: Budowa instrukcji z terminologii bankowej         | `datasets`           |        |
| **03** | Trening lokalny: Dostrajanie DeepSeek lub Qwen                          | `unsloth, peft`      |        |
| **04** | Ewaluacja: LLM-as-a-Judge – Sędzia oceniający analizy studenta          | `gemini, evaluation` |        |
| **05** | Deployment: Uruchamianie własnego modelu finansowego przez Ollama       | `ollama`             |        |
| **06** | PROJEKT #7: "Sentiment Trader" – Model wytrenowany na żargonie rynkowym | `peft, ollama`       |        |

**Oczekiwane Wyniki:**

- Dostosujesz model językowy do specyficznego języka rynków kapitałowych
- Obniżysz koszty i zwiększysz bezpieczeństwo poprzez hostowanie własnego modelu
- Opanujesz techniki 'quantization' pozwalające uruchamiać duże modele na domowym sprzęcie

---

### **Moduł 8: Financial Observability (Langfuse)**

| Lekcja | Temat Główny                                                         | Tech Stack             | Status |
| ------ | -------------------------------------------------------------------- | ---------------------- | ------ |
| **01** | Tracing Agentów: Śledzenie logiki decyzyjnej bota tradingowego       | `langfuse`             |        |
| **02** | Monitorowanie kosztów tokenów w dużych analizach portfela            | `cost-tracking`        |        |
| **03** | Debugowanie błędów: Dlaczego agent podjął błędną decyzję?            | `production-debugging` |        |
| **04** | Ewaluacja RAG: Mierzenie precyzji odpowiedzi (Context Precision)     | `rag-evaluation`       |        |
| **05** | Feedback Loop: Wykorzystanie Langfuse do zbierania korekt od tradera | `feedback-loop`        |        |
| **06** | PROJEKT #8: System monitoringu dla floty autonomicznych agentów      | `langfuse, docker`     |        |

**Oczekiwane Wyniki:**

- Będziesz wiedzieć dokładnie, dlaczego Twój agent podjął taką, a nie inną decyzję rynkową
- Zoptymalizujesz koszty tokenów przy skomplikowanych procesach analitycznych
- Wdrożysz pętlę ciągłego poprawiania jakości odpowiedzi agentów

---

## 🕸️ FAZA 5: ADVANCED STRUCTURES & ALGO TRADING

### **Moduł 9: GraphRAG & Financial Networks**

| Lekcja | Temat Główny                                                       | Tech Stack             | Status |
| ------ | ------------------------------------------------------------------ | ---------------------- | ------ |
| **01** | Teoria Grafów: Relacje między spółkami, zarządami i dostawcami     | `networkx`             |        |
| **02** | Budowa Knowledge Graph: Mapowanie powiązań w sektorze finansowym   | `networkx, neo4j`      |        |
| **03** | GraphRAG: Łączenie bazy wektorowej Qdrant z grafem relacji         | `qdrant, networkx`     |        |
| **04** | Fraud Detection: Wykrywanie anomalii i prania pieniędzy w sieciach | `fraud-detection`      |        |
| **05** | GNN (Graph Neural Networks) w analizie ryzyka systemowego          | `pyg, torch-geometric` |        |
| **06** | PROJEKT #9: "AML Detective" – Grafowy system wykrywania anomalii   | `networkx, qdrant`     |        |

**Oczekiwane Wyniki:**

- Zidentyfikujesz ryzyka systemowe niewidoczne w tradycyjnych bazach danych
- Zbudujesz systemy RAG nowej generacji, które rozumieją relacje biznesowe
- Opanujesz zaawansowane techniki wykrywania nadużyć finansowych

---

### **Moduł 10: Algorithmic Trading & Execution**

| Lekcja | Temat Główny                                                          | Tech Stack                 | Status |
| ------ | --------------------------------------------------------------------- | -------------------------- | ------ |
| **01** | Architektura bota: Data Engine -> Strategy Engine -> Execution Engine | `trading-architecture`     |        |
| **02** | Zarządzanie pozycją: Kryterium Kelly'ego i skalowanie pozycji         | `kelly-criterion`          |        |
| **03** | Optymalizacja parametrów strategii: Grid Search vs Bayesian           | `optuna, hyperopt`         |        |
| **04** | Symulacja giełdy: Obsługa poślizgów (Slippage) i prowizji             | `backtesting.py`           |        |
| **05** | Kill-Switch: Mechanizmy bezpieczeństwa w handlu automatycznym         | `risk-management`          |        |
| **06** | PROJEKT #10: AI Trading Bot Backtest – Symulacja bota na danych Tick  | `backtesting.py, vectorbt` |        |

**Oczekiwane Wyniki:**

- Zbudujesz kompletny silnik do handlu automatycznego od podstaw
- Zastosujesz algorytmy optymalizacji matematycznej do zwiększania zysków
- Wdrożysz rygorystyczne mechanizmy bezpieczeństwa chroniące kapitał

---

## 🔌 FAZA 6: MCP & CAPSTONE

### **Moduł 11: MCP w Finansach (Model Context Protocol)**

| Lekcja | Temat Główny                                                    | Tech Stack            | Status |
| ------ | --------------------------------------------------------------- | --------------------- | ------ |
| **01** | MCP Standard: Łączenie LLM z terminalami danych i Excel         | `mcp`                 |        |
| **02** | Budowa serwera MCP dla danych SQL i lokalnych baz Quant         | `mcp-python`          |        |
| **03** | Bridge danych: Dynamiczne dostarczanie cen akcji do Gemini      | `mcp, gemini`         |        |
| **04** | Bezpieczeństwo: Izolacja agenta wykonującego operacje finansowe | `security-isolation`  |        |
| **05** | Integracja MCP z profesjonalnymi narzędziami analitycznymi      | `mcp-integrations`    |        |
| **06** | PROJEKT #11: "AI Bloomberg Bridge" – Autorski protokół danych   | `mcp, financial-data` |        |

**Oczekiwane Wyniki:**

- Połączysz dowolne źródło danych finansowych z agentem w nowoczesnym standardzie
- Stworzysz własne wtyczki do środowisk analitycznych
- Zapewnisz najwyższy poziom izolacji i bezpieczeństwa przy operacjach na kapitale

---

## 🏆 FAZA 7: CAPSTONE PROJECT

### **Moduł 12: CAPSTONE: Hedge Fund in a Box**

| Lekcja | Temat Główny                                                     | Tech Stack            | Status |
| ------ | ---------------------------------------------------------------- | --------------------- | ------ |
| **01** | System Design: Integracja ML, LLM, Quant i RAG w jeden organizm  | `system-architecture` |        |
| **02** | Budowa "Decision Core" na PydanticAI                             | `pydantic-ai`         |        |
| **03** | Implementacja Dashboardu w Streamlit (Wykresy, sygnały, ryzyko)  | `streamlit, plotly`   |        |
| **04** | Deployment: Konteneryzacja całego systemu w Docker-Compose       | `docker-compose`      |        |
| **05** | Dokumentacja inżynierska i Video Demo projektu                   | `documentation`       |        |
| **06** | WIELKI FINAŁ: Prezentacja Autonomicznego Funduszu Inwestycyjnego | `presentation`        |        |

**Oczekiwane Wyniki:**

- Zintegrujesz wszystkie poznane technologie w jeden kompleksowy produkt
- Zbudujesz potężne portfolio, które wyróżni Cię na rynku Quant AI
- Zdobędziesz unikalną wiedzę o budowie autonomicznych funduszy inwestycyjnych

---

## 📊 Podsumowanie Bootcampu

- **Całkowity czas nauki:** 2x / tydz. (90–120 min) x 5 mc = 63-84 godzin
- **Liczba modułów:** 12
- **Liczba lekcji:** 72

### **Stack Technologiczny:**

**Data Engineering:**

- `uv, python`
- `yfinance, alpaca, polygon`
- `pydantic, fastapi`
- `postgresql`

**Machine Learning & Quant:**

- `sklearn, xgboost, lightgbm`
- `scipy, numpy, pandas`
- `statsmodels, arch`
- `neuralforecast, vectorbt`
- `ta-lib`

**LLM & AI:**

- `pydantic-ai`
- `gemini, ollama`
- `peft, lora, unsloth`

**Vector DB & RAG:**

- `qdrant`
- `pdfplumber`
- `semantic-search`

**Graph & Networks:**

- `networkx, neo4j`
- `pyg (torch-geometric)`

**Trading & Backtesting:**

- `backtesting.py`
- `optuna, hyperopt`

**Observability:**

- `langfuse`

**Deployment:**

- `docker, docker-compose`
- `streamlit`

**Protocols:**

- `mcp (Model Context Protocol)`

### **Po ukończeniu będziesz potrafić:**

✅ Budować profesjonalne rurociągi danych finansowych z pełną walidacją  
✅ Implementować zaawansowane systemy RAG dla dokumentów finansowych  
✅ Stosować ML i Quant w przewidywaniu ruchów rynkowych  
✅ Zarządzać ryzykiem portfela według standardów funduszy hedge  
✅ Prognozować zmienność i wykrywać reżimy rynkowe  
✅ Tworzyć autonomicznych agentów finansowych w PydanticAI  
✅ Fine-tunować modele językowe dla finansów  
✅ Monitorować i optymalizować koszty systemów AI  
✅ Wykrywać nadużycia finansowe za pomocą Graph Neural Networks  
✅ Budować i testować algorytmy tradingowe  
✅ Integrować źródła danych przez Model Context Protocol  
✅ Projektować kompletne autonomiczne fundusze inwestycyjne

---

**Author:** TakzenAI: Krzysztof Pika
