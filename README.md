📧 Detector de Spam com Inteligência Artificial
📌 Descrição

Este projeto consiste em um detector de spam desenvolvido em Python utilizando a biblioteca Tkinter para a interface gráfica e o algoritmo de classificação probabilística Naive Bayes para identificar se um e-mail é SPAM ou SEGURO.

O sistema foi treinado com exemplos de mensagens classificadas previamente e utiliza técnicas de processamento de texto para calcular a probabilidade de uma mensagem pertencer a cada categoria.

🚀 Funcionalidades
Interface gráfica amigável desenvolvida com Tkinter.
Classificação automática de mensagens.
Detecção de e-mails SPAM e SEGUROS.
Exibição do nível de confiança da classificação.
Processamento e limpeza automática do texto digitado.
Implementação simples de Machine Learning utilizando Naive Bayes.
🛠️ Tecnologias Utilizadas
Python 3
Tkinter
Math (cálculos logarítmicos)
Algoritmo Naive Bayes

⚙️ Como Funciona
1. Base de Treinamento

O sistema possui uma pequena base de exemplos contendo mensagens classificadas como:

SPAM
SEGURO

Exemplo:

("ganhe dinheiro agora clique aqui", "SPAM")
("oi tudo bem", "SEGURO")
2. Pré-processamento

Antes da análise:

O texto é convertido para minúsculas.
Símbolos especiais são removidos.
O texto é dividido em palavras.

Exemplo:

Entrada:
"Ganhe Dinheiro Agora!!!"

Saída:
["ganhe", "dinheiro", "agora"]
3. Treinamento

Durante o treinamento o sistema:

Conta a frequência de cada palavra.
Armazena palavras de SPAM.
Armazena palavras de mensagens seguras.
Cria um vocabulário geral.
4. Classificação

Quando o usuário digita um e-mail:

O texto é processado.
O algoritmo calcula a probabilidade da mensagem ser SPAM.
Calcula a probabilidade da mensagem ser SEGURO.
A maior probabilidade determina a classificação final.
5. Confiança

O sistema também calcula uma estimativa de confiança baseada na diferença entre as probabilidades encontradas.

Exemplo:

Classificação: SPAM

Confiança da IA: 87%
▶️ Como Executar
Instale o Python

Verifique se o Python está instalado:

python --version

ou

py --version
Execute o programa
python detector_spam.py
📸 Interface

A aplicação apresenta:

Campo de texto para inserir o conteúdo do e-mail.
Botão para iniciar a análise.
Janela de resultado mostrando:
Classificação
Nível de confiança
🧠 Conceitos de Inteligência Artificial Aplicados

Este projeto utiliza conceitos básicos de:

Machine Learning
Processamento de Linguagem Natural (NLP)
Classificação de Texto
Probabilidade Bayesiana
Suavização de Laplace
Logaritmos para evitar underflow numérico
⚠️ Limitações

Por ser um projeto educacional:

Possui uma base de treinamento pequena.
Não aprende novas mensagens automaticamente.
A precisão depende dos exemplos fornecidos.
Não utiliza bibliotecas avançadas de IA como TensorFlow ou Scikit-Learn.
🔮 Melhorias Futuras
Adicionar banco de dados para armazenar treinamentos.
Permitir que o usuário adicione novos exemplos.
Utilizar Scikit-Learn.
Gerar estatísticas de precisão.
Implementar exportação de relatórios.
Suporte para anexos e múltiplos idiomas.
