# 🧠 Azure AI – Speech Studio e Language Studio  
### Desafio: Análise de Fala e Linguagem Natural com IA do Azure  
**Formação Microsoft - Fundamentos de IA Generativa | DIO**

---

## 🎯 Objetivo do Desafio

Este projeto tem como finalidade **explorar e aplicar os recursos de Inteligência Artificial da Microsoft Azure** voltados para **fala e linguagem natural**, utilizando o **Speech Studio** e o **Language Studio**.  
O foco é desenvolver habilidades práticas em análise de áudio, texto e linguagem, documentando o processo e os resultados de forma técnica e organizada.

---

## 🧩 Ferramentas Utilizadas

- **Azure Speech Studio** → Reconhecimento e conversão de fala em texto (*Speech to Text*)  
- **Azure Language Studio** → Processamento de Linguagem Natural (*NLP*)  
- **GitHub** → Documentação, versionamento e compartilhamento do projeto  

---

## 🧠 Conceitos Praticados

### 🔹 Speech Studio (Fala)
- Reconhecimento de fala (*Speech to Text*)  
- Conversão de texto em fala (*Text to Speech*)  
- Detecção automática de idioma de áudio  
- Teste de vozes neurais personalizadas  
- Ajustes de pronúncia, ritmo e entonação  

### 🔹 Language Studio (Linguagem)
- Análise de **sentimentos** (positivo, negativo, neutro)  
- **Extração de frases-chave** (identificação de tópicos principais)  
- **Detecção de idioma** automática  
- **Reconhecimento de entidades** (nomes, locais, organizações, etc.)  
- Criação de **base de conhecimento para chatbots** (*QnA Maker*)  

---

## 🧪 Projeto Prático — Speech Studio

### 🎯 Objetivo do Projeto
Explorar o uso do **Azure Speech Studio** para transformar fala em texto, compreender a precisão do reconhecimento de voz e experimentar os recursos de conversão de texto em fala (*Text to Speech*).

---

### 🧰 Ferramentas e Recursos Utilizados
- **Azure Portal** – para criar o recurso de Fala (*Speech Service*).  
- **Speech Studio** – ambiente para teste e visualização dos modelos de voz.  
- **Microfone e arquivos de áudio (.wav / .mp3)** – entradas para os testes.  
- **Interface Web do Speech Studio** – para análise dos resultados e transcrições.  

---

### ⚙️ Etapas Realizadas

1. **Criação do Recurso de Fala**
   - Acesse o portal [portal.azure.com](https://portal.azure.com).  
   - Crie um recurso do tipo **Speech Service**.  
   - Escolha a região mais próxima (ex.: *East US* ou *Brazil South*).  
   - Copie a **Chave de API** e o **Endpoint**.

2. **Acesso ao Speech Studio**
   - Entre em [https://speech.microsoft.com](https://speech.microsoft.com).  
   - Faça login com a mesma conta do Azure.  
   - Vincule o recurso criado anteriormente.

3. **Testes Realizados**
   - Envio de **áudio gravado** para o serviço de **Speech to Text**.  
   - Avaliação da **precisão da transcrição** e reconhecimento de idioma.  
   - Teste com **Text to Speech** usando vozes neurais pré-definidas.  
   - Alteração de **velocidade, entonação e estilo** da fala sintetizada.

4. **Análise dos Resultados**
   - O sistema transcreveu o áudio em tempo real com excelente precisão.  
   - O **modelo neural** conseguiu identificar pausas, pontuações e sotaques.  
   - A conversão de texto em fala apresentou **vozes naturais e expressivas**.  

---

### 📈 Resultados e Insights
- A precisão do reconhecimento aumentou quando o áudio foi **limpo e sem ruído de fundo**.  
- A conversão de texto em fala permite **ajustes finos na voz** para diferentes contextos (narrativa, instrução, atendimento).  
- Esse tipo de tecnologia pode ser usado em:
  - **Atendimento automatizado com voz natural**.  
  - **Aplicativos de acessibilidade**.  
  - **Leitura automática de conteúdos multimídia**.  

---

### 📸 Evidências (exemplo)
> Inclua imagens na pasta `/images/speech`:
> - Criação do recurso no Azure Portal  
> - Tela de teste de Speech to Text  
> - Tela de conversão Text to Speech  

---

## 🧪 Projeto Prático — Language Studio

### 🎯 Objetivo do Projeto
Explorar o uso do **Azure Language Studio** para processar textos, identificar sentimentos, extrair frases-chave e detectar entidades em linguagem natural.

---

### 🧰 Ferramentas e Recursos Utilizados
- **Azure Portal** – para criar o recurso de Linguagem (*Language Service*).  
- **Language Studio** – ambiente de teste e configuração de modelos NLP.  
- **Textos de exemplo (.txt)** – insumos para análise.  
- **Interface Web do Language Studio** – para visualização dos resultados e métricas.  

---

### ⚙️ Etapas Realizadas

1. **Criação do Recurso de Linguagem**
   - Acesse o portal [portal.azure.com](https://portal.azure.com).  
   - Crie um recurso do tipo **Language Service**.  
   - Selecione a região e copie as **chaves de API** e o **endpoint**.

2. **Acesso ao Language Studio**
   - Entre em [https://language.cognitive.azure.com](https://language.cognitive.azure.com).  
   - Conecte o recurso criado anteriormente.  

3. **Testes Realizados**
   - Análise de **sentimentos** (identificando se o texto é positivo, negativo ou neutro).  
   - **Extração de frases-chave**, destacando conceitos principais do conteúdo.  
   - **Detecção de idioma** automático.  
   - **Reconhecimento de entidades nomeadas**, como nomes, locais e organizações.  
   - Criação de um teste de **QnA (Perguntas e Respostas)** com base em um texto.  

4. **Análise dos Resultados**
   - O modelo identificou corretamente **o idioma e a polaridade emocional**.  
   - A **extração de frases-chave** destacou termos relevantes do texto analisado.  
   - As **entidades nomeadas** foram reconhecidas com alta precisão.  
   - O QnA demonstrou como o modelo pode ser usado para **bases de conhecimento automatizadas**.  

---

### 📈 Resultados e Insights
- A Análise de Sentimentos é ideal para **monitoramento de feedbacks e redes sociais**.  
- O Reconhecimento de Entidades pode ser aplicado em **análise de contratos e documentos corporativos**.  
- O recurso de QnA é base para **assistentes inteligentes e copilotos de atendimento**.  
- A combinação de **Language Studio + Speech Studio** cria fluxos completos de voz e texto com IA.  

---

### 📸 Evidências (exemplo)
> Inclua imagens na pasta `/images/language`:
> - Criação do recurso no Azure Portal  
> - Tela de análise de sentimentos  
> - Tela de extração de frases-chave  
> - Tela de reconhecimento de entidades  

---

## 🧭 Insights e Aprendizados Gerais

Durante os experimentos, ficou evidente como os **serviços de IA do Azure** são complementares.  
Enquanto o **Speech Studio** traduz e entende a voz humana, o **Language Studio** interpreta o significado do texto — juntos, eles formam a base de sistemas de **comunicação inteligente e acessível**.

🔹 **Speech Studio** → foco em áudio, voz e acessibilidade.  
🔹 **Language Studio** → foco em contexto, texto e compreensão semântica.  
🔹 Ambos podem ser integrados a **Copilots e chatbots** para oferecer experiências personalizadas e naturais.  

---

## 🧩 Conceitos-Chave Reforçados

| Conceito | Descrição |
|-----------|------------|
| **NLP (Processamento de Linguagem Natural)** | Permite que sistemas entendam o significado de textos e expressões humanas. |
| **Speech to Text / Text to Speech** | Conversão de fala para texto e vice-versa. |
| **Análise de Sentimento** | Classifica o tom do texto (positivo, negativo, neutro). |
| **Entidades e Frases-Chave** | Extraem informações relevantes automaticamente. |
| **Knowledge Base (QnA)** | Gera respostas automáticas com base em conteúdo textual. |

---

## 🧰 Recursos Oficiais

- [🌐 Speech Studio - Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/speech-service/)  
- [🌐 Language Studio - Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/)  
- [🔗 Azure Cognitive Services](https://azure.microsoft.com/products/ai-services/)  
- [📘 GitHub Docs - Guia de Markdown](https://docs.github.com/pt/get-started/writing-on-github)  

---

## 💡 Conclusão

O uso combinado do **Speech Studio** e **Language Studio** reforça o poder da IA generativa aplicada à comunicação humana.  
Essas ferramentas permitem criar **assistentes inteligentes, copilotos personalizados e soluções acessíveis**, que entendem, respondem e se adaptam às necessidades do usuário.  

📌 **Projeto desenvolvido como parte da Formação Microsoft - Fundamentos de IA Generativa (DIO).**

---

### 👨‍💻 Autor
**Padula (Diego Agostinho Padula / Diego A. Padula)**  
Especialista Microsoft em Copilot Studio | Engenheiro de Software Full Stack  
🔗 [github.com/paduladiego](https://github.com/paduladiego)  
🔗 [linkedin.com/in/paduladiego](https://www.linkedin.com/in/paduladiego)
