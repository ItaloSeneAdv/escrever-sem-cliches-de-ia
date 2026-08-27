# Escrever sem clichês de IA

Uma skill em português brasileiro para revisar textos e remover estruturas previsíveis associadas à escrita gerada por IA. Ela preserva o conteúdo, a voz, o gênero e o grau de certeza do texto original.

[Leia a skill completa](./SKILL.md)

## O que ela corrige

| Padrão | Tratamento |
| --- | --- |
| Contrastes automáticos | Evita fórmulas como "não é X, é Y" quando não existe oposição lógica relevante. |
| Emojis usados como estrutura | Mantém emojis apenas quando o canal, o público ou o usuário os exigem. |
| Ritmo plano | Ajusta a extensão e a construção das frases conforme a função de cada ideia. |
| Listas forçadas de três | Usa a quantidade real de elementos, sem fabricar tríades. |
| Repetição da pergunta | Começa pela resposta ou pelo conteúdo útil. |
| Travessões dramáticos | Substitui U+2014 e U+2013 por pontuação adequada na prosa original. |
| Falso equilíbrio | Dá a cada posição o peso permitido pelas evidências. |
| Palavras de efeito | Troca abstrações e jargão por fatos, verbos e consequências concretas. |
| Transições empilhadas | Usa conectores somente quando a relação lógica precisa ser explicitada. |
| Aberturas e conclusões prontas | Remove aquecimentos genéricos, recapitulações e encerramentos automáticos. |

A revisão também procura excesso de títulos, listas desnecessárias, metacomentários, gerúndios causais, superlativos vazios, atribuições sem fonte, cordialidade automática e repetição estrutural.

## O que ela preserva

- fatos, números e referências;
- citações literais e transcrições;
- termos técnicos necessários;
- intenção, voz e registro do autor;
- cautela acadêmica, jurídica ou profissional;
- repetições que tenham função real.

## Instalação

Baixe este repositório e mantenha a seguinte estrutura no diretório de skills aceito pelo seu agente:

```text
escrever-sem-cliches-de-ia/
└── SKILL.md
```

Depois, inicie uma nova conversa ou recarregue as skills da ferramenta.

## Uso

Invoque a skill pelo nome ou peça uma revisão direta:

```text
Use a skill escrever-sem-cliches-de-ia para revisar este texto sem alterar os fatos nem a minha voz.
```

Ela pode ser usada em redação profissional, acadêmica, jurídica, comercial, institucional e editorial.

## Princípio central

A skill não acrescenta erros, gírias, histórias pessoais ou caracteres invisíveis para simular autoria humana. O objetivo é melhorar a escrita. Ela não promete enganar detectores de IA.

## Contribuições

Encontrou outro padrão recorrente? Abra uma issue ou envie um pull request com:

- o padrão observado;
- um exemplo curto;
- uma forma de corrigi-lo sem prejudicar textos legítimos.

