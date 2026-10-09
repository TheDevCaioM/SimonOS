# Como contribuir com o Simon OS

Obrigado por querer ajudar! O Simon OS é um projeto de código aberto, criado por Caio Melo e gerido institucionalmente pelo Simon Group. Qualquer pessoa pode contribuir com código, correções, documentação, testes ou sugestões.

> O projeto ainda está em estágio inicial. Isso significa que a estrutura muda com frequência. Antes de começar uma mudança grande, abra uma *issue* para conversarmos.

## Como enviar uma contribuição

1. Faça um *fork* do repositório e crie uma branch para a sua mudança.
2. Faça commits pequenos, com mensagens claras.
3. **Assine cada commit** (veja a seção abaixo).
4. Abra um *pull request* explicando o que mudou e por quê.

## Assinatura dos commits (DCO)

O Simon OS usa o **Developer Certificate of Origin (DCO)**, o mesmo mecanismo do kernel Linux. Em vez de assinar um contrato, você declara em cada commit que tem o direito de enviar aquele código.

Para isso, adicione uma linha `Signed-off-by` ao final da mensagem do commit. O Git faz isso por você com a opção `-s`:

```bash
git commit -s -m "Descrição da mudança"
```

O resultado será algo como:

```
Signed-off-by: Seu Nome <seu-email@exemplo.com>
```

Use seu nome real e um e-mail válido. Commits sem essa assinatura não poderão ser aceitos.

### O texto do DCO

```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

## Licença e direitos autorais

- O código do Simon OS é distribuído sob a **GNU General Public License v3.0 ou posterior** (veja `LICENSE` e `NOTICE`).
- Ao contribuir, você concorda que sua contribuição seja licenciada sob essa mesma licença.
- **Você mantém os direitos autorais** sobre o que escreveu. O projeto não exige cessão de direitos.
- Novos arquivos de código devem começar com o aviso de copyright e licença indicado no arquivo `NOTICE`.

## Marca

A GPL licencia o código, mas não os nomes e logotipos "Simon OS" e "Simon Group". Versões modificadas não devem sugerir endosso ou origem oficial do Simon Group sem autorização.

## Conduta

Seja respeitoso e construtivo. Discriminação, assédio e ataques pessoais não serão tolerados, e quem os praticar poderá ser removido do projeto.

## Dúvidas

Abra uma *issue* ou escreva para contato@simongroup.com.br.
