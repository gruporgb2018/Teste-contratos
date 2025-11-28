# 🚀 Guia Rápido - Sistema de Geração de Orçamentos

Bem-vindo ao **Sistema de Geração de Orçamentos**! Este guia rápido ajudará você a começar em minutos.

---

## ⚡ Início Rápido (5 minutos)

### 1️⃣ Primeira Vez? Configure a Empresa

1. Clique em **"Cadastros"** na página inicial
2. Vá para a aba **"Dados da Empresa"**
3. Preencha:
   - Nome da empresa
   - Endereço, telefone e email
   - Observações para o rodapé (opcional)
4. Clique em **"Salvar Dados da Empresa"**

### 2️⃣ Adicione Alguns Itens

1. Na aba **"Itens do Orçamento"**, selecione uma categoria
2. Preencha:
   - Nome do item (ex: "Entrada de Camarão")
   - Custo unitário (ex: 50.00)
3. Clique em **"Adicionar Item"**
4. Repita para outras categorias

### 3️⃣ Configure o Lucro

1. Vá para a aba **"Lucro"**
2. Digite a porcentagem (ex: 30)
3. Clique em **"Salvar Configuração de Lucro"**

### 4️⃣ Crie Seu Primeiro Orçamento

1. Clique em **"Novo Orçamento"**
2. Preencha os dados do cliente:
   - Nome
   - Tipo de evento
   - Data
   - Número de convidados
   - Local
3. Selecione itens das categorias
4. Revise o total
5. Clique em **"Salvar Orçamento"**

### 5️⃣ Visualize e Exporte

1. Clique em **"Consultar Orçamentos"**
2. Encontre seu orçamento
3. Clique em **"Visualizar"**
4. Para salvar em PDF: clique em **"Salvar PDF"** → "Salvar como PDF"

---

## 📊 Exemplo Prático

### Cenário: Casamento com 100 convidados

**Dados do Cliente:**
- Nome: Maria Silva
- Tipo: Casamento
- Data: 15/12/2024
- Convidados: 100
- Local: Salão de Festas XYZ

**Itens Selecionados:**
- Entrada de Camarão: R$ 50,00 × 100 = R$ 5.000,00
- Prato Principal (Filet): R$ 80,00 × 100 = R$ 8.000,00
- Sobremesa (Brigadeiro): R$ 20,00 × 100 = R$ 2.000,00
- Bebidas (Refrigerante): R$ 10,00 × 100 = R$ 1.000,00

**Cálculo:**
- Subtotal: R$ 16.000,00
- Lucro (30%): R$ 4.800,00
- **Total: R$ 20.800,00**

---

## 🎯 Tarefas Comuns

### ✏️ Editar um Orçamento Existente

1. Clique em **"Gerenciar Orçamentos"**
2. Encontre o orçamento
3. Clique em **"Editar"**
4. Modifique os dados
5. Clique em **"Salvar Alterações"**

### 🔍 Buscar um Orçamento

1. Clique em **"Consultar Orçamentos"**
2. Digite o nome do cliente na barra de busca
3. Resultados aparecem automaticamente

### 🗑️ Deletar um Orçamento

1. Clique em **"Gerenciar Orçamentos"**
2. Encontre o orçamento
3. Clique em **"Excluir"**
4. Confirme a exclusão

### 📝 Editar um Item do Catálogo

1. Clique em **"Cadastros"**
2. Vá para **"Itens do Orçamento"**
3. Encontre o item na sua categoria
4. Clique em **"Editar"**
5. Modifique nome ou custo
6. Clique em **"Salvar"**

---

## 💡 Dicas Úteis

### ✅ Melhores Práticas

- **Organize por categoria:** Mantenha itens bem categorizados para fácil busca
- **Nomes descritivos:** Use nomes claros (ex: "Entrada de Camarão com Alho" em vez de "Entrada")
- **Atualize preços regularmente:** Revise custos mensalmente
- **Teste antes de usar:** Crie um orçamento de teste antes de usar com clientes
- **Faça backup:** Anote seus dados importantes (não há sincronização em nuvem)

### 🎨 Personalizações

- **Mudar logo:** Edite o arquivo `Home.tsx` (requer conhecimento técnico)
- **Mudar cores:** Edite `index.css` (requer conhecimento técnico)
- **Adicionar categorias:** Edite `types.ts` (requer conhecimento técnico)

### 🖨️ Impressão

- **Melhor navegador:** Use Chrome ou Edge
- **Papel recomendado:** A4 (210 × 297 mm)
- **Margens:** Deixe as margens padrão do navegador
- **Cores:** Ative "Gráficos de fundo" para melhor resultado

---

## ⚠️ Importante

### 📱 Dados Locais

- Todos os dados são salvos **no seu navegador** (LocalStorage)
- **Não sincronizam** entre dispositivos
- **Não são enviados** para nenhum servidor
- Se limpar o cache do navegador, os dados serão perdidos

### 🔒 Segurança

- Nenhuma senha é necessária
- Dados não são criptografados (use em ambiente seguro)
- Não compartilhe o navegador com outras pessoas se tiver dados sensíveis

### 💾 Backup

Para fazer backup dos seus dados:
1. Abra o Console (F12)
2. Digite: `copy(JSON.stringify(localStorage))`
3. Cole em um arquivo de texto
4. Guarde em local seguro

---

## 🆘 Solução de Problemas

### ❓ Pergunta: Os dados desapareceram!

**Resposta:** Verifique se:
- O navegador não foi atualizado (limpar cache)
- O LocalStorage está habilitado
- Você está usando o mesmo navegador/dispositivo

### ❓ Pergunta: Como faço para usar em outro computador?

**Resposta:** 
- Exporte seus dados (veja Backup acima)
- Importe em outro navegador (requer código customizado)
- Ou use a versão hospedada em um servidor

### ❓ Pergunta: Posso usar em mobile?

**Resposta:** Sim! O sistema é totalmente responsivo e funciona em:
- iPhone/iPad
- Android
- Tablets
- Desktops

### ❓ Pergunta: Como integro com meu site Wix?

**Resposta:** Veja a seção "Integração com Wix" na documentação completa (DOCUMENTACAO.md)

---

## 📞 Próximos Passos

1. **Configurar a empresa** → Cadastros
2. **Adicionar itens** → Cadastros → Itens
3. **Criar primeiro orçamento** → Novo Orçamento
4. **Testar exportação** → Consultar → Visualizar → Salvar PDF
5. **Integrar com Wix** (opcional) → Veja DOCUMENTACAO.md

---

## 📖 Documentação Completa

Para informações detalhadas, consulte:
- **DOCUMENTACAO.md** - Documentação técnica completa
- **README.md** - Informações do projeto

---

**Dúvidas?** Consulte a documentação ou entre em contato com o suporte.

**Versão:** 1.0.0  
**Última atualização:** Novembro de 2024
