## 📝 Atividade 1 — Prefixos e Sufixos

Considere a palavra:

```text
ab
```

### Pergunta

Liste os prefixos e sufixos.

**Prefixos:**

Prefixo é uma parte que começa no início da palavra.
(ab) = {ε, a, ab}

**Sufixos:**

Sufixo é uma parte que termina no final da palavra.
(ab) = {ε, b, ab}

---

## 📝 Atividade 2 — Gramática

Considere:

```text
G = ({S}, {a}, {S → aS | ε}, S)
```

### Pergunta

Liste 3 palavras geradas.

S → ε
S → aS → aε
S → aS → aaS → aaε

às 3 palavras são: ε, a, aa
também pode gerar: aaa, aaaa, aaaaa, ...
