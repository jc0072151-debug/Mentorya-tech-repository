ógica de Programação - Primeira Avaliação (Java)
Java

Repositório criado para a Primeira Avaliação da disciplina Mentoria Tech sobre Lógica de Programação em Java, com foco na implementação de algoritmos em Java. O projeto contém duas atividades práticas: a simulação de um sistema escolar para cálculo de médias (bimestrais, semestrais e final) e um programa para a conversão de temperaturas entre as escalas Celsius, Fahrenheit e Kelvin.

👨‍💻 Aluno
Nome:JOSÉ CARLOS DA SILVA 
Email: jose.silva.47@aluno.edu.pi.gov.br
👨‍🏫 Professor
Nome: Helio Lima/Francisco Coelho
📝 Atividades
O projeto consiste na implementação de duas atividades principais:

Atividade	Descrição
Atividade 01	Simular um sistema escolar, recebendo 8 notas anuais. Deve calcular e exibir as médias bimestrais, médias semestrais e a média final de forma clara.
Atividade 02	Receber uma temperatura em graus Celsius (°C). Deve realizar a conversão para Fahrenheit (°F) e Kelvin (K), e exibir todos os resultados.
🛠️ Estrutura do Projeto
O código foi organizado na seguinte estrutura de pastas para manter a clareza e a modularidade:

/seu-projeto-logica/
├── src/
│   ├── Main.java             # Ponto de entrada que executa o menu de atividades
│   ├── Atividade01.java      # Lógica do Sistema Escolar
│   └── Atividade02.java      # Lógica do Conversor de Temperatura
└── README.md                 # Documentação do projeto
🚀 Como Executar
Para compilar e executar o projeto localmente, siga os passos abaixo:

Clone o repositório:

git clone https://github.com/A7zinx/atividade_mentoriatech.git
cd atividade_mentoriatech
Navegue até a pasta src:

cd src
Compile os arquivos Java:

javac Main.java Atividade01.java Atividade02.java
Execute a classe principal:

java Main
☁️ Git: Como Enviar seu Código para o GitHub
Esta seção é um guia para enviar seu código para um repositório no GitHub.

1. Configuração Inicial (Primeiro Envio)
Siga estes passos se você criou o projeto no seu computador e quer enviá-lo para o GitHub pela primeira vez.

Crie um novo repositório no GitHub (sem README.md, .gitignore ou licença).

Abra o terminal na pasta raiz do seu projeto local.

Inicialize o repositório Git e defina a branch principal como main:

git init
git branch -M main
Adicione todos os arquivos do projeto para o controle de versão:

git add .
Crie o primeiro "commit" (um "pacote" de alterações):

git commit -m "Primeiro commit: Estrutura inicial do projeto"
Conecte seu repositório local ao remoto (substitua a URL pela do seu repositório no GitHub):

git remote add origin https://github.com/seu-usuario/seu-repositorio.git
Envie o código para o GitHub:

git push -u origin main
2. Atualizando o Repositório (Envios Futuros)
Após o primeiro envio, use este fluxo mais simples para enviar suas atualizações:

Adicione as modificações: git add .
Crie um novo commit: git commit -m "feat: Adiciona cálculo de média na Atividade 1"
Envie para o GitHub:
git push origin main# Mentorya-tech-repository
Repositório de Mentorya tech
