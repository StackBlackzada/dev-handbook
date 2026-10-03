# 🤖 Uso de IA em código de produção

[← Voltar ao índice](../README.md)

1. **Revisão humana obrigatória.** Todo código gerado por agente passa por Pull Request revisado por uma pessoa antes de ir para `main`.
2. **Nunca cole secrets em prompts.** Chaves de API, tokens, senhas e dados de clientes ficam fora de qualquer agente ou chat de IA.
3. **Dados de clientes.** Só envie para um modelo dados do cliente se o contrato permitir. Na dúvida, anonimize.
4. **Teste antes de confiar.** Código gerado precisa de testes (novos ou existentes) passando no CI.
5. **Rode scripts com cuidado.** Leia scripts de instalação (`curl | bash`) e comandos destrutivos sugeridos por agentes antes de executar.
6. **Skills do Hermes.** Mantenha as Skills atualizadas com os padrões da empresa.
7. **Responsabilidade.** Quem abre o PR é responsável pelo código, tenha sido escrito por humano ou por IA.
