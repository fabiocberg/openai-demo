# SNOMED and Artificial Intelligence Demo

## Descrição

Esta aplicação demonstra potenciais usos da inteligência artificial (IA) na implementação do SNOMED CT, utilizando as APIs da OpenAI. O projeto visa explorar como modelos de linguagem podem apoiar análises clínicas, mapeamento de termos e outras funcionalidades em saúde digital.

> **Atenção:**  
> Este projeto é apenas para fins de demonstração e não deve ser utilizado com dados reais de pacientes ou informações identificáveis. Todas as informações inseridas nesta demo podem ser enviadas para a OpenAI, conforme a política da API.

## Tecnologias Utilizadas

- **Angular**: Framework principal para front-end
- **TypeScript**: Tipagem estática para JavaScript
- **OpenAI API**: Integração com modelos de linguagem (ChatGPT)
- **SNOMED CT**: Terminologia clínica estruturada
- **Node.js**: Utilizado em scripts e/ou backend (se aplicável)

## Funcionalidades

- Interface para interação direta com modelos de IA (ChatGPT/OpenAI)
- Exemplos de aplicação de IA na manipulação e análise de conceitos SNOMED CT
- Demonstração de geração de texto, compreensão de linguagem natural e sugestões clínicas (apenas exemplo)
- Site demo público para experimentação

## Avisos Importantes

- O conteúdo gerado por modelos de linguagem pode não ser confiável ou preciso.
- Revise sempre as saídas da IA, considerando contexto e fonte.
- Não utilize para decisões clínicas reais.

## Demo Online

Acesse a demonstração em:  
[https://ihtsdo.github.io/openai-demo/](https://ihtsdo.github.io/openai-demo/)

## Como Rodar Localmente

1. **Pré-requisitos**
    - Node.js (recomendado v18+)
    - npm ou yarn

2. **Instalação**
    ```bash
    git clone https://github.com/fabiocberg/openai-demo.git
    cd openai-demo
    npm install
    # ou
    yarn install
    ```

3. **Execução**
    ```bash
    ng serve
    ```
    Acesse `http://localhost:4200/` no navegador. O aplicativo recarrega automaticamente ao alterar arquivos fonte.

4. **Configuração de API**
    - Para uso completo, pode ser necessário configurar uma chave de API da OpenAI. Consulte a documentação interna ou variáveis de ambiente, se aplicável.

## Estrutura de Pastas Sugerida

```
src/
├── app/           # Componentes Angular principais
├── assets/        # Arquivos estáticos
├── environments/  # Configurações de ambiente
├── index.html     # HTML principal
└── main.ts        # Bootstrap da aplicação
```

## Suporte e Contato

Para dúvidas ou sugestões sobre esta demo, envie um e-mail para:  
**info@snomed.org**

## Licença

Este projeto é distribuído sob a licença MIT.

---

> Para contribuir, abra issues ou pull requests!  
> **Use sempre responsabilidade ao trabalhar com dados de saúde e IA.**