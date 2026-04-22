# 🧮 SmartCalc · CMV Fácil

**SmartCalc** é uma aplicação web simples e prática para calcular o custo de produtos (receitas) baseado no custo dos ingredientes (itens de estoque). Ideal para pequenos negócios como lanchonetes, restaurantes, confeitarias e food trucks.

---

## ✨ Funcionalidades

- 📋 **Cadastro de itens de estoque** (matéria-prima) com nome e custo unitário.
- 🍔 **Criação de produtos** compostos por múltiplos ingredientes e quantidades.
- 💰 **Cálculo automático** do custo total de cada produto (CMV direto).
- 💾 **Persistência local** – os dados ficam salvos no `localStorage` do navegador.
- 🧽 **Edição e exclusão** de itens e produtos, com atualização automática das referências.
- 🖼️ **Background xadrez branco e verde claro** – estilo toalha de mesa, agradável para cozinhas.
- 📱 **Responsivo** – funciona bem em desktop, tablet e celular.

---

## 🖥️ Tecnologias utilizadas

- HTML5 semântico
- CSS3 com layout grid e flexbox
- JavaScript puro (Vanilla JS) – sem dependências externas
- `localStorage` para armazenamento local
- Design system próprio, leve e moderno

---

## 🚀 Como usar

1. **Baixe o arquivo** `index.html` (ou abra diretamente no navegador).
2. A aplicação já carrega com dados de exemplo (pão, hambúrguer, queijo, etc.).
3. **Na coluna da esquerda (Itens do Estoque):**
   - Adicione novos ingredientes com nome e custo unitário.
   - Edite ou exclua itens existentes.
4. **Na coluna da direita (Produtos & Composição):**
   - Crie um novo produto informando o nome.
   - Adicione ingredientes (selecione o item e a quantidade usada na receita).
   - O custo total é atualizado automaticamente.
   - Salve o produto para vê-lo na lista acima.
5. Todos os dados são salvos automaticamente – ao recarregar a página, suas informações continuam lá.

---

## 🧪 Exemplo prático

**Item:** Queijo mussarela – R$ 0,65 por fatia  
**Item:** Pão de hambúrguer – R$ 0,85  
**Produto:** X-Burger → 1 pão + 1 queijo  
**Custo total do produto:** R$ 1,50 (antes de adicionar carne, alface, etc.)

---

## 📁 Estrutura do código

- `index.html` – único arquivo, contém toda a estrutura, estilos e lógica.
- `style` – define o layout, cards, tabelas e o fundo xadrez.
- `script` – gerencia estados, renderização, cálculo de custos e persistência.

---

## ⚙️ Personalização

- Para alterar o padrão do fundo quadriculado, modifique as propriedades `background-image` no `body` (CSS).
- As cores principais podem ser ajustadas nas variáveis dos botões e cards.
- É fácil adicionar novas funcionalidades como margem de lucro, preço de venda ou relatórios.

---

## 🔒 Limitações atuais

- O custo unitário dos itens é fixo (sem considerar variação de preço).
- Não há suporte para unidades compostas (ex: “2 kg” vs “500 g”) – a quantidade é um número decimal livre.
- Os dados ficam apenas no navegador do usuário (não há nuvem nem exportação).

---

## 📄 Licença

Este projeto é de uso livre para fins educacionais e comerciais. Sinta-se à vontade para modificar e distribuir.

---

## 📬 Contato / Sugestões

Desenvolvido para simplificar o cálculo de custos na cozinha.  
Para dúvidas ou melhorias, basta editar o código – é todo aberto e comentado.

---

**SmartCalc – Calcule o custo real do seu cardápio com estilo e simplicidade! 🧾🍽️**
