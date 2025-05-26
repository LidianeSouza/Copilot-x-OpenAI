# 💻 Laboratório: Explorando o Copilot e as Ferramentas da OpenAI

Este repositório documenta testes práticos com o Copilot e ferramentas da OpenAI, com foco em:

- ✨ Criação assistida por IA (código, texto, imagem e ideias)
- 🛡️ Aplicação e teste de filtros de conteúdo
- 📘 Aprendizados adquiridos durante os experimentos e conclusão pessoal

---

# 📂 Estrutura do Repositório - Copilot-x-OpenAI  

## 📜 README.md  
Arquivo principal com introdução ao laboratório, objetivos e instruções de uso.   

## 🤖 Criação-Assistida  
Casos de uso explorando geração de texto, imagem e código.  Contém exemplos de prompts utilizados e os resultados obtidos.  
- `texto_criativo.md` – Teste com narrativa e escrita criativa.
- `codigo_python.md` – Teste de geração de código Python para calcular lucro.  
- `geracao_imagens.md` – Teste de prompt para criação de imagem com IA.
- `email_profissional.md` -  Teste para avaliar a capacidade da IA em produzir texto profissional e claro.
  
## 🔍 Filtros-de-Conteúdo  
Testes e explicações sobre como diferentes ferramentas lidam com restrições de conteúdo. Contém exemplos de prompts utilizados e os resultados obtidos. Implementar filtros de conteúdo para moderação automática de textos gerados por IA, garantindo que não sejam exibidos conteúdos ofensivos, inadequados ou fora do escopo permitido.
- `bloqueio_sensibilidade.md` – Restrições aplicadas a temas específicos.  
   
---

## 📋 Estrutura dos Testes Comparativos
Nas pastas **"Criação Assistida"** e **"Filtros de Conteúdo"** estão os testes comparativos realizados. Para cada funcionalidade, o mesmo prompt será testado em ambas as ferramentas, e as diferenças serão documentadas seguindo a estrutura abaixo:

- **📝 Objetivo:** Objetivo do teste, contexto e principais pontos que serão analisados.  
- **🖋️ Prompt Utilizado:** Texto exato do prompt aplicado no Copilot e no OpenAI para gerar as respostas.  
- **🎯 Resultado Obtido:** Saída ou resposta gerada pelas inteligências artificiais a partir do prompt fornecido.  
- **🔍 Análise Comparativa:** Avaliação detalhada da qualidade da escrita, pontos fracos, criatividade, melhor uso, limitações, pontos fortes e sugestões de melhoria. 
- **📚 Aprendizados:** Principais insights e lições extraídas do teste realizado.  
- **🧠 Conclusão Pessoal:** Reflexão final e opinião baseada nos resultados da análise.  

---

# Criação Assistida

## ✉️ `email_profisisonal.md`

Este comparativo mostra como duas IAs — **Copilot** e **OpenAI** — responderam à mesma tarefa de criação de um e-mail curto e formal para um cliente, explicando um atraso na entrega do produto.

### 📝 Objetivo

Analisar como as IAs geram um texto formal, claro e profissional para comunicar atrasos em entregas, verificando a adequação do tom, estrutura e informações oferecidas.

### 🖋️ Prompt Utilizado  
“Escreva um e-mail curto e formal para um cliente explicando um atraso na entrega do produto.”

### 🎯 Resultado Obtido

### 🔍 Análise Comparativa

| Critério                   | 🤖 **Copilot**                                                                                                  | 🚀 **OpenAI**                                                                                       |
|----------------------------|-----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| **📜 Estrutura**            | Completa e clara, com assunto, saudação, corpo detalhado e fechamento formal.                                    | Estrutura simples e objetiva, mantém formalidade, mas texto mais enxuto.                           |
| **📄 Conteúdo / Detalhes**  | Explica o motivo do atraso e informa a nova data prevista para entrega.                                         | Menciona "imprevistos" e atraso, sem detalhamento de causa ou previsão específica.                 |
| **🙏 Tom / Empatia**        | Expressa desculpas, agradecimento e disponibilidade para esclarecer dúvidas, mostrando cuidado com o cliente. | Também pede desculpas e agradece a compreensão, porém com menos oferta de contato ou suporte.     |
| **✍️ Formalidade**          | Formal e polido, adequado para comunicação empresarial.                                                         | Formal, porém com linguagem mais simples e direta.                                                |
| **⌛ Tamanho**              | Um pouco mais extenso, equilibrado para explicar a situação com clareza.                                         | Mais curto e direto ao ponto, ideal para leitores que preferem objetividade.                       |
| **💡 Sugestão de uso**      | Ideal para situações onde é importante manter o cliente bem informado e fortalecer a relação.                   | Útil para comunicações rápidas e menos detalhadas, onde o cliente não precisa de muitas informações.|

### 📚 Aprendizados

- **Copilot** aposta em uma comunicação mais detalhada, reforçando transparência e suporte ao cliente.
- **OpenAI** prioriza a brevidade e clareza, mantendo a formalidade essencial.
- Dependendo do perfil do cliente e da situação, ambos os estilos são válidos: alguns clientes preferem detalhes, outros preferem respostas rápidas.
- A linguagem formal e o pedido de desculpas são constantes, evidenciando a importância da empatia no atendimento.
- Oferecer canal aberto para dúvidas (Copilot) pode melhorar a percepção do cliente sobre o serviço.

### 🧠 Conclusão Pessoal

Ambos os e-mails cumprem o propósito de informar o atraso de forma educada e profissional.  
- Se você quer manter o cliente bem informado, com detalhes claros e demonstração de cuidado, **o modelo do Copilot** é mais completo e acolhedor.  
- Se a intenção é ser mais objetivo e direto, para uma comunicação rápida sem muitos detalhes, **o modelo OpenAI** funciona muito bem.  

No fim, a escolha depende do estilo da empresa e do perfil do cliente. Para situações mais sensíveis, o texto do Copilot tende a gerar mais confiança e tranquilidade.


