# Ferreira Páginas

Um manual para a sua IA (Claude Code, Codex, Cursor, Gemini ou outra) criar sites como um estúdio de design: identidade visual própria para cada cliente, boa usabilidade, animação só quando faz sentido, texto sem vícios de IA e projetos organizados de um jeito que qualquer IA consegue continuar.

Tudo está num arquivo só: [`AGENTS.md`](AGENTS.md).

## O que ele faz a IA fazer

- Entender o negócio antes de desenhar: briefing, pesquisa de concorrentes e referências.
- Criar uma identidade visual para cada cliente (conceito, paleta, tipografia, elemento de assinatura) e não repetir a de projetos anteriores.
- Pensar em UI e UX: clareza, ação principal visível, celular primeiro, acessibilidade.
- Animar com critério, quando o projeto pede.
- Escrever sem travessão, sem "não é sobre X, é sobre Y", sem frases de efeito e sem emoji.
- Melhorar sites que já existem, com diagnóstico e versão anterior guardada.
- Organizar cada projeto em sua pasta, com um `STATUS.md` que serve de memória para qualquer IA.
- Bloquear dados sensíveis no GitHub.
- Guardar o que você reclama e o que você elogia, para não repetir erros.

## Como usar

### Opção 1: baixar os arquivos

Copie `AGENTS.md` e `CLAUDE.md` para a pasta onde você vai criar os sites. Depois abra a IA nessa pasta e escreva:

```
Leia o AGENTS.md e prepare esta pasta.
```

O Codex lê o `AGENTS.md` sozinho. O Claude Code lê o `CLAUDE.md`, que só aponta para o `AGENTS.md`.

### Opção 2: colar um texto na IA

Abra a IA na pasta do seu projeto e cole este texto:

```
Baixe o arquivo https://raw.githubusercontent.com/rferreirast/ferreira-paginas/main/AGENTS.md e salve como AGENTS.md na raiz desta pasta, sem alterar nada. Crie também um CLAUDE.md contendo apenas a linha @AGENTS.md. Depois leia o AGENTS.md inteiro, siga a seção 2 para organizar esta pasta e me diga em poucas linhas o que fez.
```

Se a sua IA não tiver acesso à internet (acontece no Codex), abra o [`AGENTS.md`](AGENTS.md), clique em "Copy raw file" e cole o conteúdo inteiro na conversa. O próprio arquivo explica para a IA o que fazer com ele.

## Atualizar para a versão mais nova

O arquivo na sua pasta não se atualiza sozinho. Quando houver versão nova, peça à sua IA:

```
Atualize o manual: baixe https://raw.githubusercontent.com/rferreirast/ferreira-paginas/main/AGENTS.md e substitua o AGENTS.md desta pasta. Não mexa em framework/ nem em projetos/. Depois leia o manual novo e me diga em poucas linhas o que mudou.
```

## Qual modelo usar

Você escolhe. O manual funciona em qualquer modelo; para criar ou redesenhar um site inteiro, um modelo mais forte ou um nível de raciocínio maior costuma dar um resultado melhor.

## Depois de instalado

- **Site novo:** "Quero um site para a Dra. Paula, nutricionista esportiva em Campinas. Instagram: @..."
- **Melhorar um site:** "Melhora o site da Silva Advogados, achei o topo fraco."
- **Continuar:** "Continua o projeto da clínica de onde parou."
- **Reclamar:** "Não gostei das setas nos botões." A IA grava isso e não repete.

## Licença

MIT. Use, adapte e compartilhe.
