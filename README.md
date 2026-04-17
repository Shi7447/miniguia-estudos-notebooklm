🧠 Miniguia de Estudos: Engenharia de Prompts com NotebookLM
Este repositório contém o projeto prático desenvolvido para o desafio da DIO, focado na criação de um caderno temático utilizando a ferramenta NotebookLM (Google). O objetivo é demonstrar o uso da IA como ferramenta de aprendizagem ativa.
📖 1. Contexto e Objetivos
Tema Escolhido: Engenharia de Prompts (Prompt Engineering).
Objetivo: Consolidar as principais técnicas de escrita de instruções para modelos de linguagem (LLMs), criando um guia de consulta rápida para melhorar a precisão e a utilidade das respostas geradas por IA.
📚 2. Curadoria de Fontes
Para alimentar o NotebookLM, selecionei as seguintes fontes de alta qualidade:
Guia de Prompting da OpenAI (Documentação Oficial): Focado em estratégias práticas como "escrever instruções claras".
Prompt Engineering Guide (DAIR.AI): Um repositório open-source com os frameworks Chain-of-Thought e Few-Shot.
Artigo "Attention Is All You Need" (Trechos selecionados): Para entender a base técnica (Transformers) por trás da necessidade de prompts bem estruturados.
🧪 3. Engenharia de Prompts e "Cicatrizes"
Durante o uso do NotebookLM, testei diferentes abordagens para extrair o melhor dos documentos:
Tentativa 1 (Genérica): "Me explique o que é prompt engineering."
Resultado: Resposta correta, mas superficial. Não usou exemplos dos documentos carregados.
Tentativa 2 (Contextualizada): "Com base nos guias da OpenAI carregados, quais são as 6 principais estratégias para obter melhores resultados?"
Resultado: Excelente. A IA listou pontos como "dar tempo para o modelo pensar" e "usar delimitadores".
Dificuldade Encontrada: O NotebookLM às vezes ignorava exemplos práticos.
Solução (Troubleshooting): Precisei usar o prompt: "Aja como um professor e extraia especificamente os exemplos de 'Few-shot prompting' presentes no PDF 2". Isso forçou a ferramenta a buscar dados brutos e não apenas resumir.
📝 4. Miniguia de Estudo (Entrega Final)
📋 Resumo Estruturado
O que é: A arte de comunicar-se com a IA para guiar seu comportamento e saída.
Principais Técnicas:
Few-Shot: Dar exemplos antes da pergunta.
Chain-of-Thought (Cadeia de Pensamento): Pedir para a IA explicar o passo a passo antes da conclusão.
Delimitadores: Usar """ ou ### para separar instruções de textos de exemplo.
📒 Glossário
LLM: Large Language Model (Ex: GPT-4, Gemini).
Hallucination (Alucinação): Quando a IA inventa fatos com convicção.
Temperature: Parâmetro que controla a criatividade vs. previsibilidade da resposta.
🚀 Prompts Reutilizáveis
"Resuma o texto abaixo em 3 bullet points focados em [Inserir Tópico]."
"Atue como um especialista em [Área] e revise este conteúdo buscando erros técnicos."
"Crie um quiz de 5 perguntas com base nos documentos para testar meu conhecimento."
