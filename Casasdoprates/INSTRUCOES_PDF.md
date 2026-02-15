# 📄 Instruções para Gerar o PDF da Proposta

## Como Usar

### Opção 1: Abrir no Navegador (Recomendado)

1. **Abra o arquivo** `proposta-pdf.html` no seu navegador
   - Clique duas vezes no arquivo, ou
   - Arraste o arquivo para o navegador, ou
   - Clique com botão direito > Abrir com > Navegador

2. **Clique no botão "Download PDF"** no canto superior direito

3. **Aguarde** a geração do PDF (pode levar alguns segundos)

4. **O PDF será baixado automaticamente** com o nome `Proposta_Site_Imobiliaria.pdf`

### Opção 2: Usar um Servidor Local (Se necessário)

Se o botão não funcionar (por questões de segurança do navegador), você pode usar um servidor local:

1. **Instale o Python** (se ainda não tiver)

2. **Abra o terminal na pasta Orçamento**

3. **Execute um dos seguintes comandos:**

   **Python 3:**
   ```bash
   python -m http.server 8000
   ```

   **Python 2:**
   ```bash
   python -m SimpleHTTPServer 8000
   ```

4. **Abra o navegador** e acesse: `http://localhost:8000/proposta-pdf.html`

5. **Clique no botão "Download PDF"**

### Opção 3: Usar Extensão do Navegador

Você pode usar extensões do navegador para gerar PDF:

1. **Chrome/Edge:** Use a extensão "Print Friendly & PDF"
2. **Firefox:** Use a extensão "Save as PDF"
3. **Ou simplesmente:** Pressione `Ctrl+P` (Windows) ou `Cmd+P` (Mac) e escolha "Salvar como PDF"

## Personalização

### Editar Informações do Cliente

Abra o arquivo `proposta-pdf.html` e edite:

1. **Nome do Cliente:** Procure por `[Nome do Cliente]` e substitua
2. **Email:** Procure por `[Seu Email]` e substitua
3. **Telefone:** Procure por `[Seu Telefone]` e substitua
4. **Horários:** Procure por `[Seus Horários]` e substitua

### Editar Valores

Se precisar alterar valores:

1. **Valor Total:** Procure por `700€` e substitua
2. **Valor do Pagamento:** Procure por `350€` e substitua
3. **Data:** Procure por `27 de Janeiro de 2025` e substitua

### Editar Conteúdo

Todo o conteúdo está no arquivo HTML. Você pode editar qualquer seção conforme necessário.

## Requisitos

- **Navegador moderno:** Chrome, Firefox, Edge, Safari
- **Conexão com internet:** Necessária apenas na primeira vez (para carregar a biblioteca)
- **JavaScript habilitado:** Necessário para gerar o PDF

## Solução de Problemas

### O botão não funciona

1. **Verifique se o JavaScript está habilitado** no navegador
2. **Tente usar um servidor local** (Opção 2 acima)
3. **Tente usar outro navegador**
4. **Verifique o console do navegador** (F12) para erros

### O PDF não é gerado

1. **Verifique sua conexão com internet** (necessária na primeira vez)
2. **Aguarde alguns segundos** - a geração pode demorar
3. **Tente novamente** - às vezes há problemas temporários
4. **Use a opção de impressão do navegador** (Ctrl+P) como alternativa

### O PDF não está formatado corretamente

1. **Verifique se está usando um navegador moderno**
2. **Tente aumentar a escala** no código (procure por `scale: 2` e aumente para `scale: 3`)
3. **Verifique se as fontes estão carregadas corretamente**

## Notas

- O PDF é gerado no formato A4
- A qualidade do PDF é alta (escala 2x)
- O botão de download não aparece no PDF gerado
- O PDF mantém a formatação e cores do HTML

## Estrutura do Arquivo

- `proposta-pdf.html` - Arquivo principal com a proposta
- `INSTRUCOES_PDF.md` - Este arquivo com as instruções

## Suporte

Se tiver problemas, verifique:
1. Console do navegador (F12) para erros
2. Se a biblioteca html2pdf.js está carregando
3. Se há bloqueadores de pop-up ativos
4. Se o navegador está atualizado

---

**Última Atualização:** 27 de Janeiro de 2025

