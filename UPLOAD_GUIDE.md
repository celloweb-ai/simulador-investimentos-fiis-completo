# 📤 Guia de Upload do Arquivo Excel

## Opção 1: Upload via Interface Web do GitHub (Recomendado)

### Passo a Passo

1. **Acesse o repositório**
   - Abra [https://github.com/celloweb-ai/simulador-investimentos-fiis-completo](https://github.com/celloweb-ai/simulador-investimentos-fiis-completo)

2. **Inicie o upload**
   - Clique no botão **"Add file"** (Adicionar arquivo)
   - Selecione **"Upload files"** (Carregar arquivos)

3. **Selecione o arquivo**
   - Arraste o arquivo `Simulador_Investimentos_Fundos_Imobiliarios_Excel_Resolvido.xlsx`
   - Ou clique em **"choose your files"** e selecione o arquivo

4. **Adicione uma mensagem de commit**
   ```
   feat: Adiciona arquivo Excel do simulador de investimentos em FIIs
   ```

5. **Confirme o upload**
   - Clique em **"Commit changes"** (Confirmar alterações)

---

## Opção 2: Upload via Git Command Line

### Pré-requisitos
- Git instalado no seu computador
- Autenticação GitHub configurada (SSH ou HTTPS)

### Comandos

```bash
# 1. Clone o repositório
git clone https://github.com/celloweb-ai/simulador-investimentos-fiis-completo.git

# 2. Entre no diretório
cd simulador-investimentos-fiis-completo

# 3. Copie o arquivo Excel para o diretório
cp /caminho/para/Simulador_Investimentos_Fundos_Imobiliarios_Excel_Resolvido.xlsx .

# 4. Adicione o arquivo ao stage
git add Simulador_Investimentos_Fundos_Imobiliarios_Excel_Resolvido.xlsx

# 5. Faça o commit
git commit -m "feat: Adiciona arquivo Excel do simulador de investimentos em FIIs"

# 6. Envie para o GitHub
git push origin main
```

---

## Opção 3: Upload via GitHub Desktop

### Passo a Passo

1. **Abra o GitHub Desktop**

2. **Clone o repositório**
   - File > Clone Repository
   - Selecione `celloweb-ai/simulador-investimentos-fiis-completo`

3. **Adicione o arquivo**
   - Copie o arquivo Excel para a pasta do repositório
   - O GitHub Desktop detectará automaticamente

4. **Commit e Push**
   - Adicione uma mensagem: "feat: Adiciona arquivo Excel do simulador"
   - Clique em **"Commit to main"**
   - Clique em **"Push origin"**

---

## ✅ Verificação

Após o upload, verifique se:
- O arquivo aparece na página principal do repositório
- O tamanho do arquivo é aproximadamente 49 KB
- É possível fazer o download clicando no arquivo

---

## 🐛 Problemas Comuns

### Erro: "File size exceeds GitHub's file size limit"
**Solução**: Se o arquivo for maior que 100 MB, use Git LFS:
```bash
git lfs install
git lfs track "*.xlsx"
git add .gitattributes
```

### Erro: "Permission denied"
**Solução**: Verifique suas permissões de acesso ao repositório

### Arquivo não aparece após upload
**Solução**: Aguarde alguns segundos e atualize a página (F5)

---

## 📝 Notas

- O arquivo Excel tem aproximadamente **49 KB**, bem abaixo do limite do GitHub (100 MB)
- Não é necessário usar Git LFS para este arquivo
- Certifique-se de que o arquivo não está aberto no Excel durante o upload

---

**Depois do upload, não esqueça de atualizar o link no README.md!**
