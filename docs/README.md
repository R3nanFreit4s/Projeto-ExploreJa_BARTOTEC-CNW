# 🧭 Explore Já

*Explore Já* é um aplicativo que ajuda você a explorar novos destinos, encontrar os melhores pontos turísticos e compartilhar suas experiências com outros viajantes. Com o Explore Já, planejar sua próxima aventura ficou mais fácil e divertido.

---

## ✨ Recursos Principais

* *Pesquisa por Localização:* Encontre pontos turísticos nas cinco principais cidades de São Paulo:
    * Campinas;
    * Ribeirão Preto;
    * São Paulo;
    * Sorocaba;
    * Santos.
* *Filtros por Categoria:* Refine sua busca por categorias de entretenimento como Museus, Parques, Teatros e muito mais.
* *Avaliações e Feedbacks:* É possível favoritar e escrever feedbacks detalhados sobre os locais que visitou ou têm interesse em visitar.
* *Informações do Ponto Turístico:* Cada ponto turístico tem uma página completa com nome, horário, atrações, preços, endereço, formas de acesso, avaliações, mapa com a localização e comentários de outros usuários.
* *Perfil do Usuário:* Todos os pontos turísticos favoritados por você ficarão visíveis nesta seção.

---

## 📦 Conteinerização com Docker

Como parte dos requisitos da disciplina de CNW, este projeto foi configurado para rodar em um ambiente *Docker*. A conteinerização garante que o site possa rodar em qualquer máquina de forma padronizada para fins de desenvolvimento.

* *Dockerfile:* O repositório possui um arquivo Dockerfile que configura o ambiente necessário para rodar o aplicativo PHP.

### 🛠 Como Rodar o Projeto Localmente (via Docker)

1.  *Baixar a Imagem:*
    Fazer o pull da imagem oficial. rnthefirst/exploreja:v1.0, a tag da imagem que você usou:**

    bash
    docker pull rnthefirst/exploreja:v1.0
    

2.  *Rodar o Container:*
    Após o download, execute mapeando a porta local para a porta do container: == Coloca a porta usada e a Tag, igual em cima
    bash
    docker run -d -p 8080:80 rnthefirst/exploreja:v1.0
    

3.  *Acessar o Site:*
    Abra no navegador: 8080
    
    http://localhost:8080
    

---

## 🛠 Tecnologias Utilizadas

| Categoria | Tecnologias |
| :--- | :--- |
| *Front-end* | HTML, CSS, Bootstrap, JavaScript |
| *Back-end* | PHP |
| *Banco de Dados* | MySQL |
| *Conteinerização* | Docker |

---

## 🧑‍💻 Desenvolvedores

* *Antonella Cobianchi Prucoli*
* *Heloisa Fernandes de Oliveira*
* *Matheus Cornélio Amorim*
* *Renan Leme de Freitas*
