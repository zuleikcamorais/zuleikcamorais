# Criação audiovisual com IA generativa
## Engenharia de prompts e reconstrução de um workflow

**Autora:** Zuleica Morais Firmino  
**Tipo:** projeto experimental de criação audiovisual com IA e edição  
**Status:** três vídeos produzidos e publicados no Instagram; arquivos de vídeo serão anexados posteriormente a este README.

## Contexto e objetivo

O experimento começou com um vídeo viral de referência em que Snoop Dogg aparecia em versões visuais associadas a diferentes países. Analisei seu formato e desenvolvi uma interpretação com minha própria imagem, incluindo identificações dos países na tela.

O objetivo foi percorrer o processo de criação: compreender a referência, elaborar possíveis prompts, gerar e refinar imagens, animá-las e montar o material para publicação.

Neste estudo, **engenharia reversa criativa** significa analisar o resultado visível e reconstruir um processo plausível para criar uma interpretação própria. Essa análise não revela os prompts, modelos ou configurações utilizados pelo autor do vídeo original.

## Demonstrações

| Resultado | Acesso |
| --- | --- |
| Vídeo 1 | [Assistir ao Reel 1 no Instagram](https://www.instagram.com/reel/DU7C4X7iXGa/?obrf=ODJsZG8zcmdkNGZ5) |
| Vídeo 2 | [Assistir ao Reel 2 no Instagram](https://www.instagram.com/reel/DU7I6Z1jbu0/?cplk=dGdpbDF3N2ljYmk=) |
| Vídeo 3 | [Assistir ao Reel 3 no Instagram](https://www.instagram.com/reel/DU9fd2ZiVH4/?vrfl=MXdnOWxvN3MydzhlNg==) |

Os links direcionam às publicações externas. A visualização depende da disponibilidade das publicações e das condições de acesso do Instagram. Esta documentação reconstrói o processo a partir do relato da autora; não constitui uma avaliação técnica dos arquivos audiovisuais.

### Vídeos diretamente neste README

**Próxima atualização:** anexar os três arquivos de vídeo nesta seção, mantendo os links do Instagram como alternativa de acesso.

Para incluir a reprodução, editar este README pela interface web do GitHub, anexar cada vídeo, aguardar a geração da URL do anexo e salvar a alteração. O GitHub oferece uploads em arquivos Markdown, inclusive READMEs. MP4, MOV e WEBM são formatos suportados; H.264 é recomendado para maior compatibilidade. O limite de anexo de vídeo é de 10 MB em plano gratuito e 100 MB em plano pago, sujeito às condições da plataforma.

<!-- Inserir aqui o anexo do vídeo 1 após o upload no GitHub. -->
<!-- Inserir aqui o anexo do vídeo 2 após o upload no GitHub. -->
<!-- Inserir aqui o anexo do vídeo 3 após o upload no GitHub. -->

## Workflow de produção

O fluxo compreendeu **cinco etapas em quatro plataformas**, com o Gemini utilizado em duas etapas. A passagem entre ferramentas foi conduzida manualmente pelas interfaces. Não há execução automatizada ou integração por API documentada.

| Etapa | Ferramenta | Entrada | Atividade | Saída |
| --- | --- | --- | --- | --- |
| 1. Análise da referência | Gemini | Vídeo de referência | Análise do formato e dedução de possíveis prompts | Instruções candidatas |
| 2. Geração e refinamento | Gemini | Minha imagem e instruções | Criação e ajustes das versões visuais inspiradas em países | Imagens selecionadas |
| 3. Animação | Meta AI | Imagens geradas | Transformação de imagens estáticas em vídeo | Clipes animados |
| 4. Edição | CapCut | Clipes animados | Montagem e edição da sequência | Vídeo editado |
| 5. Finalização | Instagram | Vídeo editado | Inclusão de trilha e finalização | Reels publicados |

Gemini e Meta AI foram utilizados nas etapas generativas. CapCut e Instagram compõem a edição e a publicação; o relato não especifica o uso de recursos de IA nessas duas plataformas.

O papel específico do ChatGPT na execução original e uma eventual participação do Grok não foram confirmados na reconstrução final do fluxo. Por isso, não são atribuídas etapas de produção a essas ferramentas. A ferramenta exata em que cada identificação de país foi inserida também não foi recuperada.

## Minha contribuição

- Análise da referência e definição da proposta criativa.
- Elaboração e refinamento das instruções utilizadas nas ferramentas.
- Geração das versões visuais com minha própria imagem.
- Seleção de imagens e condução da etapa de animação.
- Montagem, edição e finalização para publicação.

As decisões humanas conectaram as etapas: definir o que gerar, avaliar o material recebido, decidir o que refinar e selecionar o que entraria na edição.

## Engenharia de prompts

O desafio foi converter uma intenção visual em instruções utilizáveis em diferentes ferramentas. Para documentar esse raciocínio, a estrutura de um prompt pode separar:

| Componente | Finalidade |
| --- | --- |
| Identidade de referência | Orientar o reconhecimento da pessoa a partir da fotografia |
| Cenário e elementos visuais | Especificar a interpretação artística desejada para cada país |
| Enquadramento e iluminação | Orientar composição e apresentação |
| Restrições | Solicitar preservação dos traços e evitar elementos indesejados |
| Movimento | Orientar a animação a partir da imagem selecionada |
| Refinamento | Descrever o aspecto específico a ajustar na próxima tentativa |

**Os exemplos abaixo são reconstruções didáticas para esta documentação. Não são transcrições dos prompts originais nem comprovam parâmetros efetivamente utilizados.**

### Exemplo de instrução para imagem

> Use minha fotografia como referência de identidade. Crie uma interpretação visual em um cenário inspirado em [PAÍS], com [ELEMENTOS ESPECÍFICOS]. Preserve os traços reconhecíveis do meu rosto. Utilize [ENQUADRAMENTO] e [ILUMINAÇÃO]. Evite deformações faciais. Gere uma composição que possa ser utilizada posteriormente em uma animação.

### Exemplo de instrução para animação

> Anime esta imagem com [MOVIMENTO DESEJADO], preservando a identidade facial e os principais elementos da composição. Evite alterações abruptas no rosto, objetos surgindo sem contexto e mudanças inconsistentes de iluminação.

## Critérios para revisão e futuras reproduções

A matriz abaixo propõe uma avaliação qualitativa para futuras revisões. Não representa medições já realizadas ou uma pontuação dos três vídeos.

| Dimensão | Pergunta de verificação |
| --- | --- |
| Identidade facial | A pessoa permanece reconhecível nas diferentes imagens? |
| Integridade visual | Há deformações, sobreposições ou objetos incoerentes? |
| Coerência temporal | O rosto e o cenário se mantêm consistentes durante o movimento? |
| Identificações | Os nomes dos países estão corretos, legíveis e associados ao trecho adequado? |
| Continuidade | A sequência permite compreender a proposta com clareza? |
| Áudio e apresentação | A trilha e o ritmo apoiam a experiência de visualização? |
| Representação cultural | Os cenários são apresentados como interpretações artísticas, sem equiparar aparência e nacionalidade? |

## Resultados e aprendizados

**Resultado registrado:** três links de vídeos publicados no Instagram, apresentados pela autora como demonstrações do experimento.

O principal aprendizado foi coordenar saídas e entradas entre ferramentas, formular instruções e revisar o material antes de avançar. A escolha de uma plataforma deve estar ligada à função que ela desempenha no fluxo. O projeto aproxima experimentação criativa, curadoria humana e organização de um processo de produção.

Os prompts originais, versões dos modelos, configurações de geração, número de tentativas, tempos de produção e custos não foram recuperados. Não há medição de produtividade ou comparação controlada entre ferramentas. A viralização mencionada refere-se ao vídeo de referência, sem alegação de viralização dos vídeos da autora.

O projeto demonstra aplicação de ferramentas existentes. Não envolve treinamento de modelo próprio nem desenvolvimento de integração de software.

## Evolução do projeto

- [ ] Anexar os três vídeos diretamente ao README.
- [ ] Recuperar os prompts originais, se disponíveis.
- [ ] Acrescentar exemplos de imagem inicial e versão refinada.
- [ ] Registrar configurações e decisões em futuras reproduções.
- [ ] Aplicar os critérios de revisão e documentar os ajustes observados.

## Competências mobilizadas

IA generativa · engenharia de prompts · análise de referências · criação de workflows · curadoria visual · animação de imagens · edição audiovisual · documentação técnica.

## Referências de publicação

- [GitHub — Video uploads now generally available](https://github.blog/changelog/2021-05-13-video-uploads-now-generally-available/)
- [GitHub Docs — Anexando arquivos](https://docs.github.com/pt/get-started/writing-on-github/working-with-advanced-formatting/attaching-files)

[Voltar ao portfólio](../../README.md) · [LinkedIn da autora](https://www.linkedin.com/in/zuleica-morais-firmino-117b3319/)

Documentação atualizada em 9 de novembro de 2026.
