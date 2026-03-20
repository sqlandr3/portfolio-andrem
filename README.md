# Portfólio André Masoni Fraile

Este é um projeto React desenvolvido com Vite e Tailwind CSS, simulando uma IDE de desenvolvimento Backend.

## Como Executar Localmente

Para rodar este projeto em sua máquina, siga os passos abaixo:

1. **Instalar Dependências:**
   Abra o terminal na pasta do projeto e execute:
   ```bash
   npm install
   ```

2. **Iniciar o Servidor de Desenvolvimento:**
   Após a instalação, inicie o servidor com:
   ```bash
   npm run dev
   ```

3. **Acessar o Aplicativo:**
   O terminal informará uma URL (geralmente `http://localhost:3000` ou `http://localhost:5173`). Abra essa URL no seu navegador.

---

## Por que abrir o `index.html` diretamente não funciona?

Este é um aplicativo moderno baseado em módulos JavaScript (ESM). Navegadores modernos bloqueiam o carregamento de módulos via protocolo `file://` por motivos de segurança (CORS). Além disso, o código React precisa ser processado pelo Vite antes de ser exibido. É necessário usar um servidor local (como o comando `npm run dev` faz) para que o aplicativo funcione corretamente.

## Tecnologias Utilizadas

- **React 18**
- **Vite**
- **Tailwind CSS**
- **Lucide React** (Ícones)
- **Framer Motion** (Animações)
