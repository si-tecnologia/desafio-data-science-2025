# Desafio: API para Detecção de Incêndios/Fumaça

Bem-vindo e parabéns por chegar até esta etapa do processo seletivo!

Este desafio foi desenvolvido para avaliar suas habilidades como Cientista de Dados. Nossa ideia é que você construa uma solução completa para detecção de fumaça/incêndio utilizando imagens reais. Lembre-se de que o principal objetivo não é reinventar a roda, mas mostrar seu raciocínio, suas escolhas e como você resolve problemas utilizando técnicas e recursos existentes.

## Objetivo
Desenvolver uma solução end-to-end que:
- Busque / construa um dataset imagens de fumaça (preferencialmente de câmeras instaladas em torres);
- Realize o pré-processamento dos dados;
- Treine um modelo de detecção de objetos para identificar fumaça/incêndio;
- Disponibilize uma API que receba imagens e retorne os resultados do modelo (bounding boxes com scores).

## Tarefas
1. **Dataset**:
  - Busque / construa um dataset de sua escolha relacionado a imagens de fumaça/incêndio.

2. **Pré-processamento**: Realize as operações necessárias (limpeza, normalização, data augmentation, etc.). Justifique as escolhas feitas nesta etapa.

3. **Treinamento de Modelo**:
- Escolha o framework que achar mais adequado (TensorFlow, PyTorch, etc.).
- Utilize técnicas como transfer learning ou modelos pré-treinados se considerar vantajoso.
- Defina e justifique as métricas que serão utilizadas (ex.: precisão, recall, tempo de inferência).

4. **API**:
- Desenvolva uma API que receba uma imagem como input e retorne o resultado do modelo (bounding boxes e scores).
- A escolha da tecnologia para a API é livre; dockerizar a solução será considerado um diferencial, assim como incluir um script que demonstre a inferência da API em algumas imagens.

## Entrega do desafio
Se você chegou até aqui, é porque achamos que você tem um fit com nosso time. Porém, infelizmente, não podemos contratar todos os candidatos que realizarão o desafio. Pensando nisso, para a entrega do teste, você deve criar um repositório no seu próprio GitHub, e caso não seja selecionado, sentiremos muito, e esperamos que o desafio tenha contribuído para a construção do seu portfólio e para o seu aprendizado pessoal

- O repositório deve conter um README com:
  - Instruções para treinar o modelo.
  - Instruções para rodar a API.
  - Explicações detalhadas sobre as decisões tomadas (por exemplo, por que escolheu aquele dataset, quais operações de pré-processamento realizou, as métricas escolhidas e referências utilizadas).
- Organize seu repositório no GitHub da maneira que julgar melhor – não há uma estrutura obrigatória.
- Se preferir realizar o treinamento no Colab, inclua o link no repositório.
- Caso encontre artigos ou referências interessantes, sinta-se à vontade para incluí-los.

## Apresentação e Critérios de Avaliação

Você terá 30 minutos para apresentar sua solução.
A avaliação será em função de: 
- Raciocínio e solução de problemas: Como você estruturou a solução e justificou suas escolhas.
- Qualidade da documentação: Clareza e organização do README e demais explicações.
- Desempenho do modelo: Acurácia e eficácia na detecção de fumaça/incêndio.