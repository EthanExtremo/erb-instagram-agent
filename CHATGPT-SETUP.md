# Configurar no ChatGPT

## GPT personalizado
1. Abra a área de GPTs no ChatGPT e escolha criar um GPT.
2. Nome sugerido: **ERB Instagram Agent**.
3. Copie `INSTRUCTIONS.md` para o campo **Instruções**.
4. Envie `VOICE.md` e os arquivos de `skills/` como conhecimento, se o criador permitir.
5. Habilite pesquisa na web para tarefas que dependam de tendências, mudanças da plataforma ou referências atuais.
6. Habilite análise de dados se quiser trabalhar com planilhas, métricas ou arquivos.
7. Teste os módulos com exemplos reais e revise as respostas.

## Conversa normal
Cole `INSTRUCTIONS.md` no início de uma conversa e depois envie sua tarefa. O contexto pode não persistir em novas conversas.

## Importante
Os comandos `/ig-reel`, `/ig-caption` etc. são rótulos de instrução. Digite-os como texto; não são atalhos nativos nem instalam funcionalidades.

Arquivos `.py` adicionados como conhecimento não são executados automaticamente pelo GPT. Para executar scripts, use um ambiente Python separado ou uma ferramenta de análise de dados compatível. Esta versão inicial é um pacote de instruções, não um aplicativo autônomo.
