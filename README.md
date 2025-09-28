# n8n-ta-na-mao-culinaria
# 🍽️ Personalização Inteligente de Receitas (IA com Cache)

Um projeto que utiliza a IA para resolver um problema cotidiano: sugerir receitas criativas com base nos ingredientes que o usuário tem ou deseja usar. O foco está na eficiência do backend e na experiência de repetição do usuário.

## 🎯 Estratégia de Produto

* **Experiência Instantânea:** O feedback da receita é quase imediato, melhorando a satisfação do usuário.
* **Otimização de Custos/Performance (PO Mindset):** Implementação de uma camada de **Cache** na API de IA.
* **Reengajamento:** O uso de cache permite que o sistema "lembre" da seleção anterior do usuário, otimizando a experiência caso ele solicite variações de receita.

## ⚙️ Tecnologias e Ferramentas

| Categoria | Tecnologia | Uso e Função |
| :--- | :--- | :--- |
| **Frontend/UX** | Lovable | Interface intuitiva para seleção de ingredientes. |
| **Motor de Automação** | n8n (Low-Code) | Orquestra o Webhook de entrada e o nó de processamento de IA. |
| **Inteligência Artificial** | Nó de IA (Ex: Gemini) | Gera a sugestão de receita. |
| **Estratégia Backend** | WebHook, Nó de Cache | O WebHook recebe a lista de ingredientes, e o Cache armazena os ingredientes para que a IA saiba dar novas sugestões. |

## 🔗 Links

* **Demo Online:** https://ta-na-mao-culinaria.lovable.app/
* **Workflow N8N:** 
***
*Desenvolvido com 💛 por ebneto*
