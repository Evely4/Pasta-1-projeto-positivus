# Pasta-1-projeto-positivus


**Ferramentas de IA utilizadas:**
Utilizei o Gemini (Google) para a estruturação do grid via Bootstrap 5, lógica de estilização dos 6 cards de serviços e suporte na depuração de erros de renderização.

**Etapas com maior auxílio da IA:**
- **Estruturação de Grid:** Organização da seção de serviços com 6 cards responsivos.
- **Resolução de Bugs (Mobile):** Identificação de conflitos em classes utilitárias do Bootstrap (`d-none`) que impediam a visualização de ilustrações em dispositivos móveis.
- **Otimização de Assets:** Padronização de nomenclatura de arquivos para garantir compatibilidade com ambientes de deploy Linux (Netlify/GitHub Pages).

**Ajustes manuais e justificativas:**
- **Refatoração de Código:** Realizei a limpeza manual de todos os caminhos de imagens, removendo extensões duplicadas e espaços vazios que causavam erros de carregamento (404) no servidor de produção.
- **Fidelidade ao Design:** Ajuste manual de cores e contraste nas setas dos cards pretos (Social Media e Analytics) para garantir acessibilidade e fidelidade ao projeto original no Figma.
- **Responsividade:** Ajuste na ordem das colunas (`order-lg`) para que o layout se comporte corretamente em telas menores, mantendo a hierarquia visual.
