# _PROGRAM_03: NEURAL_ARCHITECTURE_

Kompletny, 12-modułowy bootcamp łączący fundamenty PyTorch, zaawansowane architektury neuronowe oraz budowę custom foundation models. Od tensor operations do enterprise-grade AI systems.

---

## 🚀 FAZA 1: FUNDAMENTY (PyTorch & Optimization)

### **Moduł 1: PyTorch Foundations & Tensor Engineering**

Ikona do wstawienia dla potwierdzenia statusu: ✅

| Lekcja | Temat Główny                                                           | Tech Stack         | Status |
| ------ | ---------------------------------------------------------------------- | ------------------ | ------ |
| **01** | Architektura PyTorch: Dlaczego Tensory rządzą światem AI?              | `pytorch, tensors` |        |
| **02** | Hardware Acceleration: Zarządzanie pamięcią GPU                        | `cuda, mps, rocm`  |        |
| **03** | Operacje na tensorach: Broadcasting, Reshaping, Einstein Summation     | `einsum`           |        |
| **04** | Pydantic for Architectures: Definiowanie hiperparametrów jako schematy | `pydantic`         |        |
| **05** | Projektowanie powtarzalnych eksperymentów (Seeding & Determinism)      | `reproducibility`  |        |
| **06** | PROJEKT #1: Autorski silnik do przetwarzania wielowymiarowych danych   | `pytorch`          |        |

**Oczekiwane Wyniki:**

- Opanujesz fundamenty PyTorch i niskopoziomowe operacje na tensorach
- Zrozumiesz jak efektywnie zarządzać pamięcią GPU w procesie treningu
- Zbudujesz powtarzalne środowisko do eksperymentów Deep Learning

---

### **Moduł 2: Autograd & Optimization Theory**

| Lekcja | Temat Główny                                                     | Tech Stack              | Status |
| ------ | ---------------------------------------------------------------- | ----------------------- | ------ |
| **01** | Mechanizm Autograd: Jak PyTorch liczy gradienty pod maską        | `autograd`              |        |
| **02** | Funkcje straty (Loss Functions): Od MSE po Contrastive Loss      | `loss-functions`        |        |
| **03** | Optymalizatory: Anatomia SGD, Adam, AdamW i najnowszych          | `sgd, adam, lion, adan` |        |
| **04** | Schedulery: Zarządzanie Learning Rate (Cosine Annealing, Warmup) | `lr-schedulers`         |        |
| **05** | Debugowanie gradientów: Vanishing & Exploding Gradients          | `gradient-clipping`     |        |
| **06** | PROJEKT #2: Budowa własnego optymalizatora od zera               | `custom-optimizer`      |        |

**Oczekiwane Wyniki:**

- Zrozumiesz matematykę stojącą za wsteczną propagacją błędu
- Nauczysz się dobierać i modyfikować funkcje celu do specyficznych problemów AI
- Opanujesz techniki stabilizacji treningu głębokich sieci neuronowych

---

## 🧠 FAZA 2: NEURAL ARCHITECTURES (Custom Layers & CNNs)

### **Moduł 3: Custom Layers & OOP in PyTorch**

| Lekcja | Temat Główny                                                        | Tech Stack              | Status |
| ------ | ------------------------------------------------------------------- | ----------------------- | ------ |
| **01** | nn.Module: Budowa modułowych architektur sieci neuronowych          | `nn.Module`             |        |
| **02** | Custom Layers: Tworzenie własnych warstw (Linear, Conv, Activation) | `custom-layers`         |        |
| **03** | Inicjalizacja wag: Xavier, He i wpływ na zbieżność modelu           | `weight-initialization` |        |
| **04** | Warstwy normalizacji: Batch Norm, Layer Norm, RMSNorm               | `normalization`         |        |
| **05** | Functional API vs Modular API: Kiedy wybierać które?                | `api-patterns`          |        |
| **06** | PROJEKT #3: Budowa hybrydowej sieci do analizy sygnałów giełdowych  | `pytorch, finance`      |        |

**Oczekiwane Wyniki:**

- Zaprojektujesz autorskie warstwy sieci neuronowych w podejściu obiektowym
- Wdrożysz standardy normalizacji stosowane w najnowocześniejszych modelach LLM
- Zrozumiesz subtelne różnice w technikach inicjalizacji wag modelu

---

### **Moduł 4: Computer Vision: CNNs & Beyond**

| Lekcja | Temat Główny                                                     | Tech Stack                    | Status |
| ------ | ---------------------------------------------------------------- | ----------------------------- | ------ |
| **01** | Convolutional Neural Networks (CNN): Od LeNet po ResNet          | `cnn, resnet`                 |        |
| **02** | Downsampling & Pooling: Jak sieć "widzi" cechy obrazu            | `pooling, downsampling`       |        |
| **03** | Transfer Learning: Wykorzystanie wag pre-trenowanych modeli      | `transfer-learning, imagenet` |        |
| **04** | Vision Transformers (ViT): Czy uwaga (Attention) zastąpi sploty? | `vit, attention`              |        |
| **05** | Augmentacja danych: Techniki zwiększania generalizacji modeli    | `data-augmentation`           |        |
| **06** | PROJEKT #4: System rozpoznawania wzorców na wykresach świecowych | `pytorch, computer-vision`    |        |

**Oczekiwane Wyniki:**

- Zbudujesz systemy widzenia komputerowego o najwyższej precyzji
- Nauczysz się adaptować potężne modele wizyjne do specyficznych nisz rynkowych
- Opanujesz nowoczesną architekturę Vision Transformers

---

## 🔄 FAZA 3: SEQUENCE MODELS & TRANSFORMERS

### **Moduł 5: Sequence Models & Attention Mechanism**

| Lekcja | Temat Główny                                                           | Tech Stack              | Status |
| ------ | ---------------------------------------------------------------------- | ----------------------- | ------ |
| **01** | Recurrent Neural Networks (RNN/LSTM/GRU): Dlaczego od nich odchodzimy? | `rnn, lstm, gru`        |        |
| **02** | Mechanizm Uwagi (Attention): Skalowany iloczyn skalarny                | `attention-mechanism`   |        |
| **03** | Multi-Head Attention: Serce nowoczesnego AI                            | `multi-head-attention`  |        |
| **04** | Positional Encoding: Jak nauczyć model kolejności danych               | `positional-encoding`   |        |
| **05** | Encoder-Decoder Architecture: Fundament systemów tłumaczenia           | `encoder-decoder`       |        |
| **06** | PROJEKT #5: Silnik tłumaczący "Financial Talk" na "Plain English"      | `seq2seq, transformers` |        |

**Oczekiwane Wyniki:**

- Zrozumiesz matematyczne podstawy mechanizmu uwagi (Attention)
- Zaprojektujesz systemy przetwarzające sekwencje danych o dowolnej długości
- Opanujesz architekturę Encoder-Decoder niezbędną w zadaniach tekstu-na-tekst

---

### **Moduł 6: Custom Transformer Design (The SLM Blueprint)**

| Lekcja | Temat Główny                                                      | Tech Stack                  | Status |
| ------ | ----------------------------------------------------------------- | --------------------------- | ------ |
| **01** | Budowa własnego "Small Language Model" (SLM) od zera w PyTorch    | `transformers, slm`         |        |
| **02** | Tokenizacja WordPiece vs BPE: Budowa własnego tokenizera          | `tokenizers, bpe`           |        |
| **03** | Causal Masking: Jak sieć uczy się przewidywać następny token      | `causal-masking`            |        |
| **04** | Optymalizacja pamięci: Flash Attention i KV Caching               | `flash-attention, kv-cache` |        |
| **05** | Pre-training: Budowa pipeline'u do treningu na własnych korpusach | `pretraining`               |        |
| **06** | PROJEKT #6: "Micro-Gemini" – Twój własny, lokalny model językowy  | `pytorch, llm`              |        |

**Oczekiwane Wyniki:**

- Zbudujesz i wytrenujesz własny model językowy od pierwszej linii kodu
- Opanujesz krytyczne optymalizacje pamięciowe (Flash Attention, KV Caching)
- Nauczysz się budować własne tokenizery dopasowane do specyficznych danych

---

## 🎨 FAZA 4: GENERATIVE AI & ALIGNMENT

### **Moduł 7: Generative AI: Diffusion & VAEs**

| Lekcja | Temat Główny                                                           | Tech Stack               | Status |
| ------ | ---------------------------------------------------------------------- | ------------------------ | ------ |
| **01** | Modele Dyfuzyjne: Jak szum zamienia się w dane (Stable Diffusion math) | `diffusion-models`       |        |
| **02** | Variational Autoencoders (VAE): Reprezentacje w przestrzeni ukrytej    | `vae`                    |        |
| **03** | Generative Adversarial Networks (GAN): Generator vs Dyskryminator      | `gan`                    |        |
| **04** | Sampling: Techniki generowania obrazów i dźwięku                       | `sampling-techniques`    |        |
| **05** | Image-to-Image i ControlNet: Sterowanie procesem generatywnym          | `controlnet, img2img`    |        |
| **06** | PROJEKT #7: Generator syntetycznych danych do testowania strategii     | `pytorch, generative-ai` |        |

**Oczekiwane Wyniki:**

- Zrozumiesz procesy stochastyczne stojące za generowaniem obrazów i danych
- Zbudujesz generatywne modele zdolne do uzupełniania brakujących informacji
- Stworzysz potężne narzędzie do generowania syntetycznych danych treningowych

---

### **Moduł 8: Alignment & Fine-Tuning (RLHF)**

| Lekcja | Temat Główny                                                          | Tech Stack                 | Status |
| ------ | --------------------------------------------------------------------- | -------------------------- | ------ |
| **01** | Instrukcyjne dostrajanie (Instruction Tuning): Sterowalność modelu    | `instruction-tuning`       |        |
| **02** | RLHF (Reinforcement Learning from Human Feedback): PPO i DPO          | `rlhf, ppo, dpo`           |        |
| **03** | Reward Models: Budowa sieci oceniającej jakość odpowiedzi             | `reward-modeling`          |        |
| **04** | Parameter-Efficient Fine-Tuning (PEFT): LoRA, QLoRA w czystym PyTorch | `lora, qlora, peft`        |        |
| **05** | Ewaluacja modeli: Benchmarking (MMLU, HumanEval) i własne metryki     | `evaluation, benchmarking` |        |
| **06** | PROJEKT #8: Dostrajanie modelu SLM do roli "Finansowego Doradcy"      | `pytorch, fine-tuning`     |        |

**Oczekiwane Wyniki:**

- Nauczysz się 'wychowywać' modele językowe, by odpowiadały zgodnie z intencją
- Wdrożysz zaawansowane techniki RLHF stosowane przez gigantów AI
- Opanujesz PEFT, by móc trenować modele na pojedynczych kartach graficznych

---

## 🕸️ FAZA 5: ADVANCED ARCHITECTURES (GNN & Distributed)

### **Moduł 9: Graph Neural Networks (GNN)**

| Lekcja | Temat Główny                                                  | Tech Stack               | Status |
| ------ | ------------------------------------------------------------- | ------------------------ | ------ |
| **01** | Reprezentacja danych jako grafy: Węzły, krawędzie, sąsiedztwo | `graph-theory`           |        |
| **02** | Message Passing: Jak informacje płyną przez sieć grafową      | `message-passing`        |        |
| **03** | Graph Convolutional Networks (GCN) i Graph Attention (GAT)    | `gcn, gat`               |        |
| **04** | Zastosowanie: Wykrywanie prania pieniędzy i analiza ryzyka    | `fraud-detection`        |        |
| **05** | Praca z biblioteką PyTorch Geometric                          | `torch-geometric`        |        |
| **06** | PROJEKT #9: System detekcji oszustw w sieciach transakcyjnych | `pytorch-geometric, gnn` |        |

**Oczekiwane Wyniki:**

- Zbudujesz modele zdolne do analizy skomplikowanych powiązań sieciowych
- Opanujesz standardy PyTorch Geometric do pracy z danymi grafowymi
- Wdrożysz systemy AI wykrywające anomalie w strukturach relacyjnych

---

### **Moduł 10: Scaling & Distributed Training**

| Lekcja | Temat Główny                                                     | Tech Stack                  | Status |
| ------ | ---------------------------------------------------------------- | --------------------------- | ------ |
| **01** | Data Parallelism (DP) vs Distributed Data Parallel (DDP)         | `ddp, data-parallel`        |        |
| **02** | Model Parallelism & Pipeline Parallelism: Trenowanie gigantów    | `model-parallel, pipeline`  |        |
| **03** | Techniki Mixed Precision (FP16/BF16): Przyspieszanie treningu    | `mixed-precision, amp`      |        |
| **04** | Checkpointing: Zapisywanie i wznawianie gigantycznych procesów   | `checkpointing`             |        |
| **05** | Profilowanie PyTorcha: Znajdowanie wąskich gardeł                | `profiling, bottleneck`     |        |
| **06** | PROJEKT #10: Uruchomienie rozproszonego treningu na klastrze GPU | `ddp, distributed-training` |        |

**Oczekiwane Wyniki:**

- Będziesz wiedzieć, jak skalować trening modeli na wiele kart graficznych i maszyn
- Drastycznie przyspieszysz procesy treningowe dzięki automatycznej mieszanej precyzji
- Nauczysz się profilować kod AI, by eliminować przestoje w wykorzystaniu GPU

---

## 🔧 FAZA 6: OPTIMIZATION & DEPLOYMENT

### **Moduł 11: Model Optimization & Quantization**

| Lekcja | Temat Główny                                                               | Tech Stack                      | Status |
| ------ | -------------------------------------------------------------------------- | ------------------------------- | ------ |
| **01** | Post-Training Quantization (PTQ): Przejście z FP32 na INT8/INT4            | `quantization, ptq`             |        |
| **02** | Quantization Aware Training (QAT): Trening uwzględniający błędy            | `qat`                           |        |
| **03** | Pruning: Wycinanie niepotrzebnych wag (Sparsity)                           | `pruning, sparsity`             |        |
| **04** | Knowledge Distillation: Przelewanie wiedzy z giganta (Teacher) do studenta | `knowledge-distillation`        |        |
| **05** | Eksport modeli: ONNX, TensorRT i kompilacja PyTorch 2.0                    | `onnx, tensorrt, torch-compile` |        |
| **06** | PROJEKT #11: Optymalizacja modelu pod kątem urządzeń Edge                  | `edge-deployment`               |        |

**Oczekiwane Wyniki:**

- Odchudzisz modele AI bez znaczącej utraty jakości odpowiedzi
- Przygotujesz swoje modele do pracy na procesorach mobilnych i edge
- Opanujesz techniki destylacji wiedzy stosowane w Small Language Models

---

## 🏆 FAZA 7: CAPSTONE PROJECT

### **Moduł 12: CAPSTONE: Custom Foundation Model**

| Lekcja | Temat Główny                                                           | Tech Stack                | Status |
| ------ | ---------------------------------------------------------------------- | ------------------------- | ------ |
| **01** | System Design: Projektowanie autorskiej architektury sieci neuronowej  | `system-architecture`     |        |
| **02** | Przygotowanie Datasetu: Skalowanie, czyszczenie i tokenizacja danych   | `data-preparation`        |        |
| **03** | Trening: Przeprowadzenie pełnego procesu z monitoringiem i logowaniem  | `training-pipeline`       |        |
| **04** | Ewaluacja i Fine-tuning: Optymalizacja pod konkretne zadanie biznesowe | `evaluation, fine-tuning` |        |
| **05** | Deployment: Pakowanie modelu w Docker i serwowanie przez TorchServe    | `docker, torchserve`      |        |
| **06** | WIELKI FINAŁ: Prezentacja autorskiej sieci neuronowej klasy Enterprise | `presentation`            |        |

**Oczekiwane Wyniki:**

- Stworzysz od zera unikalną architekturę sieci neuronowej dla biznesu
- Zbudujesz potężne portfolio architekta Deep Learning
- Zyskasz kompetencje pozwalające na projektowanie autorskich modeli fundamentalnych

---

## 📊 Podsumowanie Bootcampu

- **Całkowity czas nauki:** 2x / tydz. (90–120 min) x 5 mc = 63-84 godzin
- **Liczba modułów:** 12
- **Liczba lekcji:** 72

### **Stack Technologiczny:**

**Core PyTorch:**

- `pytorch, tensors, autograd`
- `nn.Module, custom-layers`
- `cuda, mps, rocm`
- `pydantic`

**Optimization:**

- `sgd, adam, adamw, lion, adan`
- `lr-schedulers`
- `gradient-clipping`
- `mixed-precision (fp16/bf16)`

**Computer Vision:**

- `cnn, resnet`
- `vision-transformers (vit)`
- `transfer-learning`
- `data-augmentation`

**Sequence Models & Transformers:**

- `rnn, lstm, gru`
- `attention-mechanism`
- `multi-head-attention`
- `encoder-decoder`
- `tokenizers (bpe, wordpiece)`
- `flash-attention, kv-cache`

**Generative AI:**

- `diffusion-models`
- `vae, gan`
- `controlnet`
- `sampling-techniques`

**Alignment & Fine-Tuning:**

- `instruction-tuning`
- `rlhf, ppo, dpo`
- `lora, qlora, peft`
- `reward-modeling`

**Advanced Architectures:**

- `graph-neural-networks (gcn, gat)`
- `torch-geometric`
- `message-passing`

**Distributed Training:**

- `ddp (distributed-data-parallel)`
- `model-parallel, pipeline-parallel`
- `checkpointing`
- `profiling`

**Optimization & Deployment:**

- `quantization (ptq, qat)`
- `pruning, sparsity`
- `knowledge-distillation`
- `onnx, tensorrt`
- `torch-compile`
- `torchserve, docker`

### **Po ukończeniu będziesz potrafić:**

✅ Operować na tensorach z pełną kontrolą nad pamięcią GPU  
✅ Budować autorskie optymalizatory i funkcje straty  
✅ Projektować custom layers i moduły neuronowe od zera  
✅ Implementować state-of-the-art architektury CNN i Vision Transformers  
✅ Rozumieć matematykę mechanizmu uwagi (Attention)  
✅ Budować własne Small Language Models (SLM) od podstaw  
✅ Tworzyć generatywne modele (Diffusion, VAE, GAN)  
✅ Stosować zaawansowane techniki fine-tuningu (RLHF, LoRA, PEFT)  
✅ Implementować Graph Neural Networks dla złożonych struktur relacyjnych  
✅ Skalować trening na wiele GPU i maszyn (DDP, Model Parallelism)  
✅ Optymalizować modele przez quantization, pruning i distillation  
✅ Deployować modele production-grade przez TorchServe i ONNX  
✅ Projektować autorskie foundation models klasy enterprise

---

**Author:** TakzenAI: Krzysztof Pika
