# 🧠 Laboratório Azure AI Language Studio

## 📋 Objetivo
Explorar os recursos do **Language Studio** no Microsoft Azure, com foco na análise de sentimentos e opiniões, conforme o vídeo de referência **“03 Laboratório 03 – Prática 02”**.

---

## ⚙️ Procedimentos Executados

### 1. Acesso ao Portal Azure
- Portal acessado: [https://portal.azure.com/#home](https://portal.azure.com/#home)
- Seguidas as instruções do vídeo **“03 Laboratório 03 – Prática 02”**
- Identificada a ausência de assinatura ativa
- **Ação corretiva:** criação de uma **assinatura gratuita** para continuar o laboratório

---

### 2. Criação do Grupo de Recursos
- Nome do Grupo de Recursos: **Aprendizado-DIO**

---

### 3. Acesso ao Language Studio
- URL: [https://language.cognitive.azure.com](https://language.cognitive.azure.com)
- Aba selecionada: **Analyze Sentiment and Opinions**
- Idioma selecionado: **Português (Brasil)**

---

### 4. Texto Utilizado para Análise

> "Data da experiência: 05/10/2024.  
> Surpreendente, tudo muito bem feito, com tempero bem dosado, temperatura ótima. Carne no ponto certo, saborosa, pão fresquinho, salada idem.  
> Eu e meu esposo não somos apreciadores de queijo cheddar, mesmo assim gostamos muito do x-salada. Maionese verde deliciosa, batatas-fritas e batatas chips perfeitas e crocantes.  
> Meu esposo experimentou uma bebida 'romulana' (gasosa sabor blueberry) e eu um chá de cranberry. A bebida de blueberry não é doce, e a de cranberry é doce na medida certa.  
> Agora planejamos voltar pra provar o milkshake com ovomaltine.  
> Estão de parabéns. Recomendo.  
>
> 08/07/2025 - Comida já foi muito boa, gostava muito daqui. Entretanto, na data de hoje me senti ludibriada e vim aqui dar um alerta para outros consumidores: comprei um combo e paguei à parte R$ 4,98 pela maionese verde. Quando veio, fiquei chocada — mandaram um potinho pequeno de 30g que nem estava cheio. A carioca trouxa aqui caiu direitinho. A maionese é boa, mas não vale. Também não se parece com a foto do totem. A atendente informou que o potinho onde costumava vir a maionese verde agora é exclusivo para cheddar. Mudou o pote e a quantidade, mas o preço não mudou.  
> E a batata chips, fria e gordurosa, muito diferente da chips sequinha e crocante feita na hora que comi das outras vezes aqui. Parece outra hamburgueria. Não recomendo e não voltarei tão cedo. Minha avaliação 5 estrelas caiu para 2 estrelas. Tentei dar 3, mas hoje não consigo, decaiu muito mesmo. Serviço e ambiente ok, bebidas ok, comidas não valem a pena."

📌 **Observação:** Foi utilizado um texto mais extenso do que o exemplo do vídeo, com o objetivo de avaliar o desempenho do Azure em uma análise de contexto mais complexa.

---

### 5. Resultado da Análise
- O texto foi dividido automaticamente em **24 sentenças**
- A análise apresentou **sentimentos mistos**, representando com precisão os dois momentos distintos da experiência do cliente (positivo e negativo)

---

### 6. Teste com o Serviço de Fala
- Portal acessado: [https://speech.microsoft.com/portal](https://speech.microsoft.com/portal)
- Redirecionamento automático para: [https://ai.azure.com](https://ai.azure.com)
- Observação: o **layout atual** difere do mostrado no vídeo *“Conhecendo o Estúdio de Fala”*, mas foi possível localizar facilmente a funcionalidade de **Transcrição em Tempo Real**

---

## ✅ Conclusão
A prática demonstrou o potencial das ferramentas cognitivas do Azure.  
O **Language Studio** apresentou desempenho eficiente ao analisar textos longos e detectar múltiplos sentimentos, enquanto o **Speech Studio** forneceu uma interface intuitiva para transcrição de fala em tempo real.

---

## 🧩 Tecnologias Utilizadas
- [Microsoft Azure](https://azure.microsoft.com/)
- **Azure Language Studio**
- **Azure Speech Studio**

---

## 🧑‍💻 Autor
**Marcos — Estudante de Engenharia da Computação**  
Documentação elaborada para fins de aprendizado e prática em **Inteligência Artificial no Azure**.
