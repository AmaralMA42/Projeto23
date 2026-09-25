# Fluxo Eduardo ↔ IA ↔ Marco

Este arquivo resume o fluxo de informação do Projeto 23.

## Fluxo normal

```
GitHub compartilhado
        ↓
IA do Eduardo lê estado atual
        ↓
Eduardo conversa normalmente
        ↓
artigo / ideia / dado / análise
        ↓
IA verifica impacto no estado
        ↓
sem mudança material ──→ continua a conversa
        ↓
com mudança material
        ↓
SYNC DELTA
        ↓
GitHub / Marco
        ↓
IA de Marco incorpora somente o delta
```

## O que fica onde

### GitHub

Use para:

- código;
- modelos;
- testes;
- estado científico resumido;
- autoboots;
- pequenos dados derivados redistribuíveis;
- SYNC DELTAs;
- documentação necessária para reproduzir decisões/resultados.

### Fora do GitHub

Por padrão:

- PDFs protegidos;
- datasets brutos grandes;
- arquivos de terceiros sem licença clara;
- credenciais;
- materiais pessoais;
- outputs descartáveis.

Esses materiais podem ser usados durante a análise sem necessariamente serem copiados para o repositório.

## Três situações comuns

### 1. Eduardo tem uma ideia

Converse primeiro.

A IA compara a ideia com o estado atual e ajuda a transformá-la em hipótese/teste.

Só vira atualização quando houver consequência científica real ou decisão humana.

### 2. Eduardo encontra um artigo

Entregue o artigo ou link para a IA e peça:

> “Veja se isto muda algo no Projeto 23.”

A IA deve separar:

- o que o artigo realmente demonstra;
- o que é relevante para ZA/ZG;
- se há mudança de estado;
- se basta registrar referência ou se é necessário sync.

### 3. Eduardo obtém um resultado

Peça:

> “Faça o red-team deste resultado e diga se ele muda nosso estado.”

Se sobreviver à análise e tiver consequência material, a IA prepara o sync.

## Regra de simplicidade

O sistema deve tornar a colaboração mais fácil, não criar mais trabalho.

Se uma informação não muda pergunta, modelo, evidência, interpretação, gate ou próximo passo, provavelmente não precisa de um novo documento.
