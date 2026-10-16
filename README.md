# Rafael Blachi

**Desenvolvedor de sistemas** — automação, integração de API, painéis e bots.
Acho o processo manual que custa dinheiro, especifico, **construo dirigindo agentes de IA**
e confiro contra a realidade.

<sub>*Systems developer — automation, API integration, dashboards and bots. I find the manual
process that costs money, spec it, build it by directing AI coding agents, and verify it
against reality. Based in Brazil (UTC−03). Open to remote work.*</sub>

---

## Em produção

### NanoQuant · sistema de decisão sob incerteza

Opera na Binance Futures com dinheiro real, sem supervisão, desde setembro de 2026.
Orquestração por Task Scheduler, proteção nativa na corretora, painéis web e comandos por Telegram.

| | |
|---|---|
| Módulos Python | 1.470 |
| Linhas no executor ao vivo | 7.479 |
| Arquivos de teste | 98 |
| Laboratórios de medição | 168 |
| Vereditos registrados no livro de provas | 727 |

**A regra que define o projeto:** nada é armado sem evidência. Sob ela, **97 estratégias foram
testadas e recusadas** — cada uma com o motivo escrito e datado, e três publicações minhas
retratadas no mesmo dia em que caíram.

É o oposto do que costuma aparecer num portfólio, e é de propósito. O valor do sistema não é
o que ele faz; é o que ele **se recusa** a fazer sem prova.

### Blachi Solutions · conferência de comissão para corretoras de consórcio

Produto para corretoras que vendem consórcio e recebem a comissão em parcelas da administradora,
segundo cronograma que muda por produto e por campanha. Hoje isso é planilha manual: 5 a 7 dias
de trabalho por fechamento, e o erro acontece nos dois sentidos.

Levantei a operação de uma corretora real (14 pessoas, ~1.000 cotas/mês), escrevi a especificação
funcional em quatro módulos, desenhei as telas e construí o analisador de assembleia.

**O diferencial:** os CRMs do setor *preveem* a comissão no momento da venda. Nenhum confere a
previsão contra o extrato que a administradora efetivamente pagou. A conferência é o produto.

---

## Como eu trabalho

**O sistema recusa em vez de adivinhar.** Quando a administradora trocou o formato do arquivo de
assembleia de PDF para xlsx entre um ano e outro, o leitor **recusou os arquivos** em vez de ler
errado e gerar número falso. Falha de leitura não é "zero" — é falha, e tem de aparecer.

**Erro silencioso é o que me preocupa.** Guarda que nunca dispara e guarda que sempre dispara são
o mesmo defeito. Aviso que falha é aviso invisível.

**Confiro contra a realidade, não contra o meu próprio arquivo.** Os três erros de preço que achei
no sistema saíram de pedir a conferência no portal da fonte — não de reler o que eu tinha gravado.
Arquivo de estado não é estado.

**Construo dirigindo agentes de IA — e o trabalho não é pedir, é especificar e conferir.** O código
sai rápido; o que decide é o que eu exijo dele. Teste que passa sempre não é teste: eu quebro a
função de propósito e exijo que o teste falhe. Resultado que me agrada é o que eu mando um segundo
agente tentar refutar — porque a vitória confortável é a que ninguém audita. O que o agente escreve
é proposta; o que entra em produção passou por medição.

---

## Trajetória

| | |
|---|---|
| **2026** | Software & Automation — sistemas próprios e para cliente |
| **2023–24** | Consultor de vendas, Porto Vale — **prêmio Melhores do Ano** |
| **2015–16** | Agente de viagens, Adardara |
| **2013–14** | Produção, Viapol |

Vim do lado de quem **usa** o processo manual e **vende** para quem decide. É por isso que eu começo
pelo levantamento da operação e não pela tecnologia.

---

## Stack

**Python** · integração de API REST · **PowerShell** e Task Scheduler (orquestração, watchdog,
keepalive) · Flask e painéis web · bots de Telegram · pandas e NumPy · HTML/CSS para interface e
documento · Git · SQLite e JSON Lines como loja de dados · Bash

---

## Contato

**blachisolutions@gmail.com** · [LinkedIn](https://www.linkedin.com/in/rafael-blachi-3625b5165)

<sub>Os repositórios dos sistemas são privados — operam com credencial e dado de cliente.
Posso abrir acesso de leitura para avaliação técnica, ou apresentar o funcionamento em chamada.</sub>
