# 🔄 Conversor Word para PDF

Um aplicativo web moderno e eficiente para converter arquivos Word (.doc/.docx) em PDF. Desenvolvido com Node.js e tecnologias web modernas.

![Preview do Aplicativo](preview.png)

## ✨ Funcionalidades

- ✅ Conversão múltipla de arquivos Word para PDF
- 📱 Interface responsiva e moderna
- 🖱️ Suporte para drag and drop
- 📊 Feedback visual em tempo real
- 🎯 Seleção múltipla de arquivos
- 🚀 Processamento em lote
- 💫 Animações suaves
- 🎨 Design moderno e intuitivo

## 🛠️ Tecnologias Utilizadas

- **Frontend:**
  - HTML5
  - CSS3
  - JavaScript (ES6+)
  - Font Awesome Icons
  - Google Fonts (Poppins)

- **Backend:**
  - Node.js
  - Express
  - Multer
  - docx-pdf

## ⚙️ Pré-requisitos

- Node.js (versão 12 ou superior)
- NPM (Node Package Manager)

## 📥 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/conversor-word-pdf.git
cd conversor-word-pdf
```

2. Instale as dependências do backend:
```bash
cd backend
npm install
```

3. Instale as dependências necessárias:
```bash
npm install express cors multer docx-pdf
```

4. Inicie o servidor:
```bash
node server.js
```

5. Acesse a aplicação:
- Abra `http://localhost:3000` no seu navegador
- Se a porta 3000 estiver em uso, o servidor automaticamente escolherá outra porta disponível

## 📝 Estrutura do Projeto
conversor-word-pdf/
├── frontend/
│ ├── index.html
│ ├── style.css
│ └── script.js
└── backend/
├── server.js
├── package.json
├── uploads/
└── output/

## 🚀 Como Usar

1. Inicie o servidor backend:
```bash
cd backend
node server.js
```

2. Acesse a aplicação no navegador usando a URL mostrada no console

3. Para converter arquivos:
   - Arraste e solte arquivos Word na área indicada
   - Ou clique para selecionar arquivos
   - Selecione um ou mais arquivos .doc ou .docx
   - Clique em "Converter para PDF"
   - Os arquivos PDF serão baixados automaticamente

## 🔧 Solução de Problemas

Se encontrar o erro "address already in use":

1. Encontre o processo usando a porta:
```bash
netstat -ano | findstr :3000
```

2. Encerre o processo:
```bash
taskkill /PID <número_do_processo> /F
```

Ou simplesmente aguarde o servidor escolher automaticamente outra porta disponível.

## 📱 Responsividade

A aplicação é totalmente responsiva e funciona em:
- 💻 Desktops
- 📱 Smartphones
- 📟 Tablets
- 🖥️ Diferentes tamanhos de tela

## 🤝 Contribuindo

1. Faça um Fork do projeto
2. Crie sua Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🐛 Problemas Conhecidos

- A conversão requer uma conexão estável com a internet
- Arquivos muito grandes podem levar mais tempo para processar
- Em alguns sistemas, pode ser necessário instalar o LibreOffice

## 💡 Dicas

- Para melhor performance, mantenha os arquivos Word abaixo de 50MB
- Certifique-se de que os arquivos não estão corrompidos
- Mantenha seu navegador atualizado para melhor experiência

## 🔒 Segurança

- Os arquivos são processados localmente
- Arquivos temporários são automaticamente deletados após a conversão
- Não há armazenamento permanente de dados

## 📞 Suporte

Se encontrar algum problema ou tiver sugestões:
1. Verifique se já não existe uma [issue](https://github.com/seu-usuario/conversor-word-pdf/issues) relacionada
2. Abra uma nova issue com uma descrição detalhada do problema

## ✨ Agradecimentos

- [Font Awesome](https://fontawesome.com/) pelos ícones
- [Google Fonts](https://fonts.google.com/) pela fonte Poppins
- Comunidade open source pelas bibliotecas utilizadas

---
Desenvolvido com ❤️ por [Seu Nome](https://github.com/seu-usuario)
