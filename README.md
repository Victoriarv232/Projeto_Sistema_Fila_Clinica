# Projeto: Gerenciamento de Fluxo de Fila
Nesse projeto, você encontrará um sistema de gerenciamento de fila numa Clínica, desenvolvido com Python e Flask.
(Com geração de senhas a depender da especialidade procurada, e fluxo baseado na simulação de 2 guichês operando atendimento).

## Funcionalidades

- Geração de senhas por tipo de atendimento;
- Fila com prioridade para Preferenciais;
- Limite de senhas por consultório;
- Remoção automática da senha da fila após o atendimento;
- Armazenamento das senhas em banco de dados (Para exibição das mesmas, informando visualmente quais e quantas senhas estão na fila);
- Mecanismo de resetar as senhas (Pensado para quando um novo dia de atendimento se iniciar, havendo a necessidade de recomeçar a contagem de senhas).
- Interface web com navegação entre páginas:
  - Página 1: Gerar senhas / Ir para o Painel / Resetar senhas;
  - Página 2: Painel com senhas em atendimento e em espera / Chamar senhas / Voltar para Gerar Senhas.
    
## Tecnologias utilizadas

- Python 3 
- Flask
- Flask-SQLAlchemy (SQLite)
- HTML
- CSS
- Bootstrap
 
## Instruções de execução

### Clone o repositório do gitHub
No Terminal, insira os seguintes comandos:
```bash
git clone https://github.com/Victoriarv232/Projeto_Sistema_Fila_Clinica.git
cd 'Projeto_Sistema_Fila_Clinica'
```

### Crie um ambiente virtual (venv) e o ative
#### No Linux/MacOS
```bash
python3 -m venv venv
source venv/bin/activate
```
### No Windows
```bash
python3 -m venv venv
source venv/scripts/activate
```

## Instale os recursos requeridos para rodar o projeto
```bash
pip install -r requirements.txt
```

## Execute a aplicação no seu computador
```bash
python app.py
```
## Utilização da aplicação na web
No seu navegador, digite:
  **http://localhost:5000**

## Para encerrar o servidor local da aplicação
  **Abra o terminal e aperte CTRL + C**

## Demonstração do Aplicativo
* Página 1 - Gerar Senhas
  
  ![Imagem Site - Página index (Gerar senha)](https://media.discordapp.net/attachments/836756398569553970/1377431005081895003/image.png?ex=683a4197&is=6838f017&hm=52f290a97a5eb62738ae9be74e5084c017ae0f996008d9ff881b4ce01e816c1b&=&format=webp&quality=lossless&width=822&height=462)


* Página 2 - Painel
  
  ![Imagem Site - Página index (Gerar senha)](https://media.discordapp.net/attachments/836756398569553970/1377431080822640641/56730e17-603e-4f78-ad89-715a869085fb.png?ex=683a41a9&is=6838f029&hm=09dd694032b7bf7c7b93860c0d2208c63ef8d3ed30bc32b1c13d5a11fcdb36b0&=&format=webp&quality=lossless&width=822&height=462)

## Estrutura de Arquivos
![Estrutura de Arquivos](https://media.discordapp.net/attachments/836756398569553970/1377803389710110810/image.png?ex=683a4ae6&is=6838f966&hm=569a3a7434024fc90f34fe88f4e0b04df011ff5d7fef4555cc94c917f3093bfb&=&format=webp&quality=lossless)

## Integrantes do Grupo
* Isaque Barros Pinheiro 
* Juliana Cristina Martins de Deus
* Laura Fernandes Cardoso
* Marcelo Gustavo Simas Freire
* Sofia Sarmento Soares Prados
* Tâmilly Duarte dos Santos
* Victória Resende Vieira
* Vitória Moura dos Santos SIlva
