# mnist-cnn-image-recognition

MNIST CNN Image Recognition
Este projeto implementa uma Rede Neural Convolucional (CNN) para a classificação de dígitos manuscritos usando o famoso dataset MNIST. O objetivo é demonstrar como construir uma CNN básica para resolver um problema clássico de classificação de imagens em machine learning.

📋 Descrição
O MNIST é um dataset popular que contém 70.000 imagens de dígitos manuscritos (60.000 para treino e 10.000 para teste). Utilizamos uma CNN para identificar qual número (0-9) está presente em cada imagem.

🔧 Tecnologias Utilizadas
Python: Linguagem principal do projeto.
TensorFlow/Keras: Framework para construção da rede neural.
Matplotlib: Para visualização dos resultados.
NumPy: Para manipulação de arrays e cálculos.
📂 Estrutura do Projeto
bash
Copiar código
mnist-cnn-image-recognition/
│
├── mnist_cnn.ipynb         # Notebook Jupyter com a implementação completa
├── cnn_mnist.py            # Arquivo Python com a CNN implementada
├── README.md               # Documentação do projeto
├── requirements.txt        # Lista de dependências do projeto
├── results/                # Pasta contendo as visualizações e gráficos gerados
│   └── predictions.png     # Exemplo de predições feitas pelo modelo
└── LICENSE                 # Licença do projeto
🚀 Como Executar o Projeto
Pré-requisitos
Certifique-se de ter o Python 3.x instalado.

Instale as dependências necessárias:

bash
Copiar código
pip install -r requirements.txt
Executando o Código
Clone este repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/mnist-cnn-image-recognition.git
Para executar o projeto, use o Jupyter Notebook ou rode o script diretamente:

Executando no Jupyter Notebook:

bash
Copiar código
jupyter notebook mnist_cnn.ipynb
Executando o script Python:

bash
Copiar código
python cnn_mnist.py
🧠 Explicação do Modelo
A CNN implementada possui a seguinte estrutura:

Camadas Convolucionais: Duas camadas de convolução (32 e 64 filtros) com ativação ReLU.
Camadas de Pooling: Camadas MaxPooling para redução dimensional.
Camada Densa: Com 64 neurônios e ativação ReLU.
Camada de Saída: Camada densa com 10 neurônios e ativação softmax para classificação.
📊 Resultados
A CNN foi treinada por 5 épocas, atingindo uma precisão de ~99% no conjunto de teste. Aqui está uma amostra das previsões feitas pelo modelo:


🔗 Referências
Documentação do Keras
Dataset MNIST
📄 Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
