# FastGen - Delivery de Alimentos Backend

<br />

<div align="center">
   <img src="https://ik.imagekit.io/smjiqpi9b/FastGen.png?updatedAt=1748529826241" title="source: imagekit.io" width="300" height="300" /> 
</div>



<br /><br />

## 1. Descrição

*O projeto FastGen é uma plataforma de delivery, onde facilitará para o estabelecimento o cadastro e gerenciamento do seu estoque de forma confiável.*

------

## 2. Sobre esta API

A API FastGen permite que o estabelecimento realize o cadastro e gerenciamento de seus produtos. Com endpoints seguros e intuitivos, a API facilita e trás segurança para nosso cliente.

### 2.1. Principais Funcionalidades

1. Listar todos os produtos
1. Buscar Produto por ID
1. Buscar Produto por nome
1. Cadastrar Produto
1. Atualizar Produto
1. Deletar Produto

------

## 3. Diagrama de Classes

```mermaid
classDiagram
direction TB
    class Produto {
	    -Long id
	    -String nome
	    -BigDecimal preco
	    -String imagem
	    -int quantidade
	    -LocalDateTime data
	    +getAll()
	    +getById(Long id)
	    +getAllByNome(String nome)
	    +post(Produto produto)
	    +put(Produto produto)
	    +delete(Long id)
    }
```

------

## 4. Diagrama Entidade-Relacionamento (DER)

<div align="center">
    <img src="https://ik.imagekit.io/smjiqpi9b/Capture.JPG?updatedAt=1748526406734" title="source: imagekit.io" />
</div>





------

## 5. Tecnologias utilizadas

| Item                          | Descrição           |
| ----------------------------- | ------------------- |
| **Servidor**                  | Servidor WEB / HTTP |
| **Linguagem de programação**  | Java                |
| **Framework**                 | Spring              |
| **ORM**                       | Hibernate           |
| **Banco de dados Relacional** | MySQL               |

------

## 6. Configuração e Execução

1. Clone o repositório do Projeto [Projeto_01_Backend](https://github.com/Cavaleiros-Templarios/Projeto_01_Backend) dentro da pasta do *Workspace* do Eclipse/STS

```bash
git clone https://github.com/Cavaleiros-Templarios/Projeto_01_Backend
```

2. **Abra o Eclipse/STS** e selecione a pasta do *Workspace* onde você clonou o repositório do projeto
3. No menu superior do Eclipse/STS, clique na opção: **File 🡲 Import...**
4. Na janela **Import**, selecione a opção: **General 🡲 Existing Projects into Workspace** e clique no botão **Next**
5. Na janela **Import Projects**, no item **Select root directory**, clique no botão **Browse...** e selecione a pasta do Workspace onde você clonou o repositório do projeto
6. O Eclipse/STS reconhecerá automaticamente o projeto
7. Marque o Projeto_01_Backend no item **Projects** e clique no botão **Finish** para concluir a importação
