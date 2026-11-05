# 01 · Dev Environment

**Data:** 05/11/2026 · **Tempo gasto:** (preencher)

## A ideia em uma frase
(Por que montar o ambiente em camadas, de baixo para cima?)
Para ter um melhor entendimento como o sistema funciona.

## O que eu fiz
- Instalei o básico do sistema: `build-essential git curl wget unzip`
- Instalei o `uv` e o Python 3.12 com `uv python install 3.12`
- Criei o ambiente virtual do curso com `uv venv` e ativei com `source .venv/bin/activate`
- Instalei `numpy`, `matplotlib` e `jupyter` com `uv pip install`
- Rodei o script de verificação da rota iniciante

## Evidência

Comando (rodado na raiz de `ai-engineering-from-scratch/`, com o `.venv` ativo):

```bash
python3 phases/00-setup-and-tooling/01-dev-environment/code/verify.py --route beginner
```

Saída:

```text
=== AI Engineering from Scratch: Environment Check ===

Route: Beginner course (`--route beginner`)

  [PASS] Python 3.11+ (required now)
         Python 3.12.14 at /home/tiago/Estudos/IA/AI-Engineering/ai-engineering-from-scratch/.venv/bin/python3
  [PASS] Git (required now)
         git version 2.39.5 at /usr/bin/git

Later checks skipped: 9 tools are not needed to start. Add `--show-later` when you want to inspect them.

Result: 2/2 required checks passed
Ready to start Beginner course.
Next: python3 phases/01-math-foundations/01-linear-algebra-intuition/code/vectors.py
```

Ambiente instalado: Python 3.12.14 · NumPy 2.5.4 · Matplotlib 3.11.2 · Jupyter · Git 2.39.5

## Exercícios
- [x] 1. Rodar o script de verificação e corrigir falhas (2/2 passaram)
- [ ] 2. Instalar o PyTorch no ambiente do curso (adiado: será necessário na Fase 3)
- [ ] 3. "Hello world" em Python, TypeScript, Rust e Julia (adiado: Node, Rust e Julia entram quando as lições pedirem)

## Onde travei e como resolvi
(preencher)

## Dúvidas para revisar no domingo
(preencher)
