cat > README.md << 'EOF'
# SocialConnect API

## 🤝 Working agreement (contrato de equipe)
- **Canal de comunicação:** [ex.: grupo no Teams/WhatsApp — respostas em até X h]
- **Encontros de trabalho:** [dias e horários fixos da semana]
- **Decisões técnicas:** discussão com prazo de [X] h; sem consenso → spike de 30 min + decisão registrada em ADR; professor como última instância
- **Code review:** todo PR precisa de **pelo menos 1 aprovação** antes do merge; prazo máximo de revisão: [24–48 h]; feedback sempre sobre o código, nunca sobre a pessoa
- **Commits:** pequenos, frequentes e com mensagem que explica o **porquê** (padrão: `tipo: descrição`, ex.: `feat:`, `fix:`, `docs:`, `test:`)
- **Definition of Done (inicial):** código implementado + validação + testes essenciais passando + PR revisado e aprovado + documentação atualizada + sem erros no pipeline

## 🤖 Uso responsável de IA generativa
Este projeto pode utilizar IA generativa **como apoio**, seguindo as regras da disciplina:
- Toda contribuição relevante de IA é **declarada** na descrição do PR;
- Prompts significativos são registrados em `docs/extensao/registro-ia.md` (data, ferramenta, prompt, como a saída foi validada);
- Saídas de IA **não são confiadas cegamente**: passam por revisão, testes e verificação de segurança antes do merge.

## 🧭 Sobre a solução
- **Problema que resolve:** [descrever em 1–2 frases; será refinado com o público externo na aula 15]
- **Público-alvo:** [quem se beneficia da solução]
- **Status:** 🚧 em construção — produto do semestre letivo
EOF