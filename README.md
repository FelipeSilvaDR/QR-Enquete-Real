# 📊 Enquete estilo WhatsApp (Offline)

Esta versão **não usa Firebase**.  
Todos os votos ficam apenas na memória do navegador (somem ao atualizar a página).

---

## 🚀 Como usar
1. Edite o array `perguntas` no `index.html` para criar suas próprias enquetes.
2. Abra o arquivo `index.html` direto no navegador ou publique no GitHub Pages.
3. Cada resposta é armazenada localmente e os resultados são mostrados em tempo real.

---

## 📱 Exemplo de perguntas editáveis
```js
const perguntas = [
  { titulo: "Qual é sua comida favorita?", opcoes: ["Pizza", "Hambúrguer", "Sushi", "Salada"] },
  { titulo: "Você usa mais:", opcoes: ["Carro", "Moto", "Bicicleta", "A pé"] }
];
```
