## 📱 Mobile — PizzaManager

Aplicativo desenvolvido com **React Native** usando **Expo**, pensado para facilitar a gestão de pedidos diretamente no celular. Ideal para garçons, atendentes ou para o próprio pizzaiolo acompanhar em tempo real os pedidos.

---

### 📦 Tecnologias Utilizadas

- **Expo**
- **React Native 0.76**
- **React Navigation (Stack + Native)**
- **Axios**
- **Async Storage** (persistência de sessão)

---

### 🚀 Como Rodar o Projeto

```bash
git clone https://github.com/seuusuario/pizzamanager.git
cd pizzamanager/mobile
npm install
```

Para iniciar o projeto com Expo:

```bash
npm start
```

Ou execute em um emulador/simulador:

```bash
npm run android
npm run ios
npm run web
```

> Obs: Certifique-se de que o back-end está rodando e acessível via rede local ou URL pública (ex: via [ngrok](https://ngrok.com/) ou deploy online).

---

### 📁 Estrutura de Pastas

```
src/
├── assets/         # Imagens, ícones, fontes
├── components/     # Componentes reutilizáveis
├── contexts/       # Context API para autenticação, etc.
├── pages/          # Telas (Pedidos, Login, Detalhes, etc.)
├── routes/         # Rotas com React Navigation
└── services/       # API (Axios configs e chamadas)
```

---

### ✅ Funcionalidades

- Login com persistência de sessão
- Listagem de pedidos ativos
- Detalhes de pedidos
- Marcar pedidos como entregues
- Navegação fluida entre telas

---


Se você quiser, posso montar um GIF demonstrando a navegação do app (com base num vídeo ou prints) e também adicionar isso no README. Deseja algo assim?

Ou prefere um README separado só para o app mobile com foco exclusivo nessa parte?
