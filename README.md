# 🔁 Lista Circular em Java

Este projeto implementa uma **Lista Circular genérica** em Java, desenvolvida para praticar **estruturas de dados**, lógica de ponteiros e programação orientada a objetos.

Na lista circular, o último nó aponta para o primeiro, formando um ciclo contínuo, o que exige cuidados especiais para evitar loops infinitos.

---

## 🚀 Funcionalidades

* ➕ Adicionar elementos à lista circular
* ❌ Remover elementos por índice
* 🔍 Buscar elemento por índice
* 📏 Retornar o tamanho da lista
* 🖨️ Exibir a lista de forma encadeada e circular

---

## 🧠 Conceitos Aplicados

* Estruturas de Dados
* Lista Circular
* Nós e referências
* Programação Orientada a Objetos (POO)
* Generics em Java
* Controle de loops em estruturas circulares

---

## 🛠️ Tecnologias Utilizadas

* Java
* IDE de sua preferência (IntelliJ IDEA, Eclipse, VS Code)

---

## 📂 Estrutura do Projeto

```
📁 dio.me
 ┣ 📄 ListaCircula.java
 ┗ 📄 No.java
```

---

## ✍️ Exemplo de Uso

```java
ListaCircula<String> lista = new ListaCircula<>();

lista.add("A");
lista.add("B");
lista.add("C");

System.out.println(lista);
```

**Saída esperada:**

```
[No{conteudo=A}] ---> [No{conteudo=B}] ---> [No{conteudo=C}] ---> (Retorna ao início)
```

---

## ⚠️ Observações Importantes

* A lista não possui ponteiros nulos entre os nós
* O método `toString()` percorre a lista usando o tamanho para evitar loop infinito
* A remoção de elementos exige atenção para manter o ciclo correto

---

## 📚 Objetivo do Projeto

Este projeto foi criado com o objetivo de **aprimorar o entendimento sobre listas circulares**, reforçando conceitos fundamentais de estruturas de dados muito utilizados em sistemas, filas circulares e algoritmos.

---

## 👨‍💻 Autor

**Luiz Filipe Ferreira Gonçalves**
📍 Goiânia - GO
🔗 GitHub: [https://github.com/Filipe062](https://github.com/Filipe062)
🔗 LinkedIn: [https://www.linkedin.com/in/luiz-filipe-ferreira-gon%C3%A7alves-083b85334](https://www.linkedin.com/in/luiz-filipe-ferreira-gon%C3%A7alves-083b85334)

---

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!
