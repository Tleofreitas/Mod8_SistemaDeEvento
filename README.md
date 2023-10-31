# Projeto Modelo de domínio e ORM
## Desafio proposto
Você deve criar um projeto no Spring Boot com Java e banco de dados H2, e implementar o modelo conceitual conforme 
especificação a seguir. 
![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/9874c497-274b-4017-967b-b856a5001f28)

Além disso, você deve fazer o seeding da base de dados conforme diagrama de objetos que segue.
![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/c34436ee-a158-4034-a7fb-a91082490924)

---
## *Pré-requisitos para testes locais* 
Para testar localmente você deve ter instalados em sua máquina:

### 1) Descompactador de arquivos
O Windows 10 já possui um programa padrão para visualizar arquivos compactados. Caso seu sistema operacional seja anterior ao Windos 10, realize o passo abaixo:

Para visualizar o projeto você precisará extrair os arquivos através de um programa para arquivos compactados.

Recomendo Winrar, baixe a versão 32x ou 64x, de acordo com seu sistema.

Link para download: https://www.win-rar.com/download.html

### 2) IDE (Ambiente de Desenvolvimento Integrado)
Este será utilizado para executar a aplicação. Recomendo [STS](https://spring.io/tools) (Spring Tool Suit) ou [IntelliJ Community](https://www.jetbrains.com/idea/download/?section=windows)

### 3) Java JDK...
Caso você não tenha instalado e configurado em sua máquina, instale da seguinte maneira: [Instalar Java JDK 17](https://www.youtube.com/watch?v=QekeJBShCy4)

---
## 📦️ *Realizando teste localmente*
### 1) Clone (baixe) o repositório

Nesta página, clique no botão Code, depois em Download ZIP e salve o arquivo.

![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/193577b7-e1a8-4b2c-a80c-b6363a6bed12)

Extrair arquivos: Abra a pasta onde o arquivo foi salvo.

### 2) Extração
### 2.1) Extrair arquivos sem Winrar
Clique com o botão direito sobre o arquivo e selecione Extrair Tudo.
<br></br>

![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/03075095-3752-4ce1-83aa-dfda9e738466)

As informações foram extraídas para a pasta Mod8_SistemaDeEvento-main.

### 2.2) Extrair arquivos com Winrar
Clique com o botão direito sobre o arquivo e selecione Extrair Aqui (Extract Here).
<br></br>

![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/6331c260-b1a5-4fc6-84e8-a383a8dadcf3)

As informações foram extraídas para a pasta Mod8_SistemaDeEvento-main.

### 3) Abrir Projeto
### 3.1) Abrir projeto com STS
Clique em File, Import, Maven, Existing Maven Projects, Next...
<br></br>

![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/31ff2aae-32fb-44e2-944b-421516888f78)

Selecione a pasta onde você salvou o projeto, Finish
<br></br>
![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/94f03e9f-7468-432a-bfc4-c063ba5d2661)

Aguarde a importação do projeto (acompanhe a barra de carregamento no canto inferior direito).

### 3.2) Abrir projeto com IntelliJ Community
Clique em Open, selecione a pasta onde você salvou o projeto, Ok...
<br></br>

![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/42c768dd-e2d0-4b83-aeb2-9f0d1b74cf00)

Caso apareça a tela abaixo, selecione Maven Project...

![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/78d9394f-3a72-48db-bd6b-887931ee1537)

Aguarde a importação do projeto (acompanhe a barra de carregamento no canto inferior direito).

---
## ⚠️ *Erros comuns* ⚠️
### No passo Como Testar o Código>
Se não houver a opção *Extrair Tudo*, significa que não há programa instalado para manipulação de arquivos compactados.
Neste cado, seguir com o passo *Pré-requisitos para testes locais*.

### Abrir projeto com IntelliJ Community
Após o término da importação, pode ocorrer do IntelliJ não localizar o JDK, neste caso, vá em File, Settings, pesquise por JDK, selecione Importing e em JDK for importer selecione seu JDK. Aplique (Apply) e Ok.

![image](https://github.com/Tleofreitas/Mod8_SistemaDeEvento/assets/88738577/93b85b1c-8515-470f-bc40-b7ae460fbb24)

Caso você não tenha o JDK instalado, siga com o passo <i><b>Pré-requisitos para testes locais - Java JDK</b></i>.

### Abrir o projeto
Após os arquivos serem carregados, pode acontecer de aparecer um X ou um ! vermelho. Caso isso ocorra, tente as soluções deste
tutorial: https://www.youtube.com/watch?v=Je4JWWJcyo0

---
## *Contribuintes* 🔥👊
Este projeto foi desenvolvido durante o curso Formação Desenvolvedor Moderno da escola [@DevSuperior](https://devsuperior.com.br), sobe orientação do tutor [Nelio Alves](https://www.linkedin.com/in/nelio-alves/?originalSubdomain=br).
