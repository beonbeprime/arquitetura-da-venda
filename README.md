# A Arquitetura Invisível da Venda

Um squad de funil para o Claude Code. Ele te ajuda a parar de falar a coisa certa
para a pessoa errada.

A maioria das vendas não se perde por falta de oferta boa. Se perde por falar com a
pessoa no momento mental errado. Quem não vê valor não compra. Quem não sente
necessidade não compra. Quem não entende o problema ignora. Este squad descobre em
qual parte do funil cada pessoa está e te entrega a mensagem certa para o momento dela.

Funciona para conteúdo, stories, anúncios, e-mail, WhatsApp, recuperação de lead e
reunião de venda. Tudo tem funil.

## O que ele faz

- Faz perguntas para descobrir o nível de consciência do seu lead (os 5 níveis de Eugene Schwartz).
- Classifica a pessoa em topo, meio ou fundo do funil.
- Gera a comunicação certa para aquele nível, no canal que você pedir.
- Audita uma copy que você já tem e diz se ela está falando para o público certo.
- Aplica BANT e SPIN para qualificar antes de você investir tempo num lead.

## Como usar

1. Tenha o [Claude Code](https://claude.com/claude-code) instalado.
2. Clone este repositório:

```
git clone https://github.com/beonbeprime/arquitetura-da-venda.git
```

3. Entre na pasta e abra o Claude Code:

```
cd arquitetura-da-venda
claude
```

4. O Claude Code lê o arquivo `CLAUDE.md` automaticamente e já vira o seu squad de funil.
   Diga o que você quer comunicar e para quem. Se você não souber o nível da pessoa,
   ele te faz as perguntas e descobre.

## Exemplo de uso

```
Você: quero um story para vender minha mentoria
Squad: para quem? tráfego frio, seguidor, lead ou cliente? essa pessoa já sabe que
       tem o problema que você resolve?
Você: seguidor que ainda acha que o problema dele é falta de tempo
Squad: então ela está no nível 2, topo do funil. nesse momento você não vende, você
       mostra que o problema real é outro. segue o story...
```

## O que tem dentro

- `CLAUDE.md` — o cérebro do squad, carregado automaticamente pelo Claude Code.
- `biblioteca/01-niveis-de-consciencia.md` — os 5 níveis em detalhe, com temperatura de audiência.
- `biblioteca/02-diagnostico-perguntas.md` — as perguntas de diagnóstico, SPIN e BANT.
- `biblioteca/03-matriz-canais.md` — a mensagem certa para cada nível em cada canal.
- `exemplos/exemplos-prontos.md` — exemplos reais por nível: dentista, advogado, mentoria.

## A ideia em uma frase

Quem aprende a pensar funil para de tentar convencer todo mundo e começa a conduzir
cada pessoa para o próximo passo.

---

Feito na Fábrica de Mentores. Use, adapte, compartilhe.
