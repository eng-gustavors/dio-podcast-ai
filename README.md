# Projeto: Podcast Gerado por IA - Especial Transição Energética (Biogás e Biometano)

Este projeto é a entrega para o desafio de Podcast com IA da DIO. 
Nesta versão, optei por uma arquitetura focada em **privacidade de dados e ferramentas Open Source/Locais**, substituindo o ChatGPT e ecossistemas fechados por modelos abertos e processamento local.

## 🛠️ Tecnologias Utilizadas
- **Roteiro e Estruturação:** Llama 3 (via Ollama - Processamento 100% Local)
- **Geração de Voz (TTS):** Microsoft Edge TTS (Voz Neural)
- **Edição de Áudio:** Audacity

## 📝 Prompts Utilizados no Modelo Local (Llama 3)

**Prompt 1: Estruturação**
> "Aja como um especialista em sistemas de energia e crie um roteiro de 2 minutos para um podcast. O foco deve ser a diferença técnica entre a geração de biogás num biodigestor e o processo de purificação (upgrade) para biometano, abordando o potencial de injeção na rede de gás natural. O tom deve ser direto e técnico, mas acessível."

**Prompt 2: Refinamento Técnico**
> "Ajuste o texto anterior para focar mais na questão da remoção de CO2 e nas propriedades do biometano como substituto direto do gás natural fóssil em veículos pesados."

## 📁 Estrutura do Repositório
- Na pasta `/output` encontra-se o ficheiro final em formato MP3 com a narração gerada por inteligência artificial.
