# Guia das novidades do Technos

Oct 19, 2026 · @Arthur Rodrigues

Guia rápido das contas bancárias e das demais novidades do sistema. Leia **Como funciona**, faça a **virada** uma vez só, seguindo o passo a passo, e depois use **No dia a dia**.

## Como funciona

- **O dinheiro fica na conta onde caiu.** Pix → Nubank, cartão → conta da máquina (Ton ou PagBank), dinheiro → caixa físico.
- **Só o custo de cada venda é transferido** para o PagBank (Caixa operacional). O sistema mostra quanto.
- **O lucro é dividido só no papel** entre as destinações: Despesas 55%, Caixa operacional 30%, Reserva de emergência 10% e Investimentos 5%.
- **Cada parte entra 80% no disponível e 20% na segurança** da destinação.
- **Contas pagas saem do disponível** da destinação escolhida (Despesas já vem marcada). A segurança só é usada quando o disponível acaba.

&#91;embedded content: caminho do dinheiro · onde cai, a quem pertence, saídas e repasses\]

**Exemplo:** venda de R$ 100 no Pix com R$ 40 de custo. Os R$ 100 caem no Nubank e você transfere R$ 40 para o PagBank. Os R$ 60 de lucro ficam no Nubank, mas pertencem às quatro destinações:

| Destinação | Pertence a ela | Disponível | Segurança |
| --- | --- | --- | --- |
| Caixa operacional | R$ 40 de custo + R$ 18 = R$ 58 | R$ 46,40 | R$ 11,60 |
| Despesas | R$ 33 | R$ 26,40 | R$ 6,60 |
| Reserva de emergência | R$ 6 | R$ 4,80 | R$ 1,20 |
| Investimentos | R$ 3 | R$ 2,40 | R$ 0,60 |

Venda com prejuízo: tudo vai para o Caixa operacional. Pagamento parcial ou fiado: cada pagamento é dividido na hora, com o custo proporcional.

## A virada: o que separar antes

A virada é o dia em que o sistema passa a controlar as contas. Ela é feita uma vez só, de preferência antes de abrir a loja ou num dia fechado. Leva uns 20 minutos. Separe:

1. **A data de corte** (explicada logo abaixo). Exemplo: 01/11/2026.
2. **O saldo de cada conta** (PagBank, Nubank e Ton) no fim do dia anterior à data de corte, como aparece no app do banco.
3. **O "a receber" de cada máquina de cartão**: vendas já feitas que a operadora ainda não depositou, pelo valor líquido (já sem a taxa). Aparece no app da máquina.
4. **O dinheiro em mãos**: o da gaveta, contado no fechamento do caixa, e o do cofre (o dinheiro guardado fora da gaveta), contado também.

## A data de corte

A data de corte é o campo **Data do saldo inicial** das contas. Ela precisa ser **a mesma em todas as contas**, inclusive no caixa físico.

- O **Saldo inicial** é quanto a conta tem no **começo** desse dia. Por isso se usa o saldo do fim do dia anterior.
- Tudo que acontece **a partir** dessa data entra nos saldos e nos potes: vendas, contas pagas, transferências.
- O que aconteceu **antes** continua no histórico e nos relatórios, mas não mexe em saldo, pote ou repasse. Esse dinheiro já está dentro do saldo inicial.
- Prefira o **dia 1º de um mês**: assim o primeiro mês dos avisos de 50% e 90% fica completo.

| Situação | O que acontece |
| --- | --- |
| Venda feita antes da data de corte | Fica no histórico. Não entra em saldo, pote nem repasse: já está no saldo inicial |
| Venda no cartão antes da data, depositada depois | O sistema não vê esse depósito. Por isso o "a receber" da máquina entra no saldo inicial da conta dela |
| Venda a partir da data de corte | Entra no saldo da conta e é dividida entre as destinações |
| Fiado ou conta a receber de antes, paga depois | Entra quando for paga, como uma venda nova, com o custo proporcional |
| Conta paga antes da data | Já saiu do banco antes do saldo inicial. Não faça nada |
| Conta a pagar ainda em aberto | Pague normalmente, escolhendo a conta e a destinação |
| Transferência feita no banco e ainda não registrada | Registre com a data certa no campo **Data** |

## Passo a passo da virada

Faça nesta ordem. Tudo fica em **Financeiro → Contas bancárias**.

### Passo 1: Destinações

Em **Destinações**, clique em **Editar** em cada uma e confira:

| Destinação | % do lucro | Recebe o custo das vendas | Meta (R$) |
| --- | --- | --- | --- |
| Despesas | 55 | Não | Em branco |
| Caixa operacional | 30 | Sim | Em branco |
| Reserva de emergência | 10 | Não | O valor para 6 meses (a tela sugere um) |
| Investimentos | 5 | Não | Em branco |

A soma precisa dar 100%. Só uma destinação recebe o custo.

### Passo 2: Divisão disponível/segurança

Em **Divisão disponível/segurança**, confira **80%**: de cada entrada, 80% vai para o disponível e 20% para a segurança.

### Passo 3: Contas bancárias

Em **Nova conta**, cadastre cada conta:

| Nome | Destinação | Saldo inicial | Data do saldo inicial |
| --- | --- | --- | --- |
| PagBank | Caixa operacional | Saldo do app + "a receber" da máquina PagBank | Data de corte |
| Nubank | Reserva de emergência | Saldo do app | Data de corte |
| Ton | Investimentos | Saldo do app + "a receber" da máquina Ton | Data de corte |

- **Banco, Agência e Número** são opcionais. O **Tipo** é só informativo.
- Deixe **Saldo disponível para uso (%)** em branco: vale o 80% do passo 2.
- O saldo inicial pertence à destinação da conta e entra 80/20 nos potes dela.

### Passo 4: Caixa físico

O caixa físico já existe e é de Despesas.

1. No último dia antes da data de corte, **feche o caixa** contando o dinheiro da gaveta. Conte também o dinheiro do cofre.
2. No dia de corte, **abra o caixa** com o valor contado na gaveta. Esse valor vira a **gaveta** no sistema.
3. Em **Contas bancárias**, clique em **Editar** no caixa físico. Preencha **Saldo inicial** com todo o dinheiro em mãos (gaveta + cofre) e **Data do saldo inicial** com a data de corte. Exemplo: R$ 150 na gaveta e R$ 1.402,05 no cofre dão R$ 1.552,05.

O saldo inicial não deve ser menor que a gaveta: o sistema aceita, mas o cofre fica negativo (em vermelho). A sobra ou a quebra do fechamento do passo 1 não conta, porque é de antes da data de corte.

O saldo do caixa físico é todo o dinheiro em mãos: o saldo inicial mais as vendas em dinheiro com o caixa aberto, as contas pagas pelo cofre ou pela gaveta e as transferências desde a data de corte. Ele pertence a Despesas e fica dividido em duas partes, que aparecem em **Contas bancárias** e em **Caixa físico**:

- **Gaveta:** o dinheiro do caixa aberto, para troco. Com o caixa fechado, é o valor contado no último fechamento.
- **Cofre:** o resto do dinheiro em mãos (em mãos menos a gaveta).

Abrir o caixa, sangrias e suprimentos feitos direto no caixa só passam dinheiro entre a gaveta e o cofre: abrir o caixa com mais do que foi contado no último fechamento tira a diferença do cofre; um suprimento tira do cofre e uma sangria devolve ao cofre. A sobra ou a quebra do fechamento entra no dinheiro em mãos. Para o dinheiro sair do caixa físico, lance uma conta paga (pelo cofre ou pela gaveta) ou uma transferência (sai da gaveta, com o caixa aberto).

### Passo 5: Destino dos recebimentos

Em **Destino dos recebimentos**, escolha a conta de cada forma e de cada máquina:

| Na tela | Escolha |
| --- | --- |
| Pix | Nubank |
| Máquina PagBank | PagBank |
| Máquina Ton | Ton |
| Cartão de Crédito e Cartão de Débito | PagBank. Vale só para cartão registrado sem máquina (veja as dúvidas) |
| Transferência | A conta onde você recebe transferências |
| Outro | A conta onde esse dinheiro cai, ou Sem conta |
| Crediário | Sem conta: o dinheiro entra quando o fiado for pago |
| Dinheiro | Automático: caixa físico, com o caixa aberto |

Clique em **Salvar destinos**.

### Passo 6: Vendas desde a data de corte

Só é preciso se já houve vendas ou contas pagas a partir da data de corte antes de terminar os passos 1 a 5.

Em **Destino dos recebimentos → Recebimentos anteriores**, coloque a data de corte em **A partir de**, clique em **Aplicar aos recebimentos sem conta** e confirme. Aparecem mensagens como "3 recebimentos foram divididos entre as destinações". Pode clicar de novo sem problema: o que já foi feito não se repete.

Esse passo vem depois do passo 5 porque usa as regras de destino.

### Passo 7: Conferir

- **Contas bancárias:** cada conta mostra o saldo inicial que você informou, mais o que aconteceu desde a data de corte. O caixa físico também, com a gaveta igual ao valor de abertura do caixa e o cofre com o resto.
- **Repasses entre contas:** "Está nas contas" igual a "Pertence às destinações", sem aviso amarelo.
- **Destinações:** cada uma com 80% e 20% do saldo inicial da conta dela.

### Exemplo de virada

Valores de exemplo, com data de corte 01/11 e saldos anotados no fim do dia 31/10:

| Conta | No app | A receber da máquina | Saldo inicial | Pertence a | Disponível | Segurança |
| --- | --- | --- | --- | --- | --- | --- |
| PagBank | R$ 1.000 | R$ 200 | R$ 1.200 | Caixa operacional | R$ 960 | R$ 240 |
| Nubank | R$ 3.000 | — | R$ 3.000 | Reserva de emergência | R$ 2.400 | R$ 600 |
| Ton | R$ 500 | R$ 300 | R$ 800 | Investimentos | R$ 640 | R$ 160 |
| Caixa físico | R$ 150 contados na gaveta, nada no cofre | — | R$ 150 | Despesas | R$ 120 | R$ 30 |

No dia 01/11, o caixa é aberto com R$ 150, e o painel de Repasses mostra R$ 5.150 nas contas e R$ 5.150 pertencendo às destinações.

### Dúvidas da virada

**Todo o saldo do Nubank vira Reserva de emergência?** Sim: o saldo inicial de cada conta pertence à destinação dela. Se parte desse dinheiro for de outra destinação, use **Remanejar** logo depois da virada.

**Posso fazer a virada alguns dias depois da data de corte?** Pode. Anote os saldos e o "a receber" do fim do dia anterior à data de corte e faça o passo 6. Contas pagas nesses dias como "Fora das contas cadastradas" não saem de nenhuma conta: cancele o lançamento e lance de novo, escolhendo a conta de onde o dinheiro saiu. O melhor é fazer a virada antes de pagar qualquer conta.

**E o custo das vendas de antes da data de corte?** Não gera repasse. Se quiser esse custo no PagBank, transfira antes de anotar os saldos.

**Errei um saldo inicial. E agora?** Em **Editar** da conta, corrija o valor. Os saldos e os potes se ajustam na hora.

**Por que o cartão da OS ou da conta a receber cai no PagBank?** Ao registrar o pagamento pelo Financeiro, o sistema não pergunta a máquina nem a taxa: entra o valor cheio na conta de Cartão de Crédito/Débito. Para cair na conta certa, já sem a taxa, cobre OS e vendas no cartão pelo **PDV**, escolhendo a máquina.

**Cancelei uma venda de antes da data de corte e devolvi o dinheiro.** O cancelamento não mexe nos saldos, porque a venda era de antes. Lance a devolução como conta a pagar e pague pela conta de onde o dinheiro saiu.

**Repasses mostra uma diferença entre o que está nas contas e o que pertence.** Se a tela avisar de pagamentos ainda não divididos, faça o passo 6.

## No dia a dia

### Repassar o custo

1. Em **Contas bancárias**, clique em **Repasses entre contas**.
2. Em **Repasses do custo pendentes**, faça cada transferência no banco. Dá para juntar tudo uma vez por dia.
3. Clique em **Registrar repasse**: o formulário já vem preenchido, com o tipo **Repasse do custo**. Confirme, e a tela volta para os repasses.

Quando estiver tudo em dia, aparece "Nenhum repasse pendente". Vendas na máquina PagBank não geram repasse, porque o dinheiro já está lá. Nas vendas na Ton, o repasse diz "se o dinheiro do cartão já caiu na conta": faça só depois que a operadora depositar. Valores abaixo de R$ 1 não aparecem.

**Atenção:** só transferências do tipo **Repasse do custo** abatem do painel. Uma transferência comum não abate.

### Pagar uma conta

Em **A pagar**, abra a conta e use **Registrar pagamento**:

- **De qual conta saiu o dinheiro:** cada opção mostra o saldo. O caixa físico aparece duas vezes, aceita só dinheiro e mostra quanto há em cada parte:
  - **Cofre:** para contas pagas com o dinheiro guardado. Vale com o caixa aberto ou fechado, até o valor do cofre.
  - **Gaveta:** só com o caixa aberto, até o dinheiro da gaveta.

  Se a conta for maior que o cofre, use duas linhas de pagamento: uma saindo do cofre e outra da gaveta. Juntas, vão até o dinheiro em mãos. "Fora das contas cadastradas" não mexe em saldo nenhum.
- **De qual destinação saiu o dinheiro:** já vem **Despesas**. Troque quando o gasto for de outra destinação. Cada opção mostra o disponível e a segurança.

O valor sai do disponível da destinação; o que faltar sai da segurança, com um aviso. O pagamento nunca é bloqueado por isso (só o caixa físico, pelo dinheiro do cofre ou da gaveta). No detalhe aparece, por exemplo, "Saiu de PagBank · da destinação Despesas" ou "Saiu de Conta 4 / Caixa físico (cofre)".

**Avisos do mês:** quando uma destinação passa de **50%** e depois de **90%** do disponível do mês, aparece um aviso, por exemplo "Caixa operacional já usou 56% do disponível do mês (R$ 450,00 de R$ 800,00)". Acima de 100%, aparece "passou do disponível do mês". O disponível do mês é o que ela tinha no dia 1º mais o que entrou no mês. Contas pagas e remanejamentos contam como uso; o que sai da segurança não conta. Os avisos não bloqueiam nada e ficam na tela, em amarelo, até você clicar no X.

### Transferir entre contas

Em **Nova transferência**, escolha **De**, **Para**, **Valor**, **Data** e o **Tipo**:

- **Transferência:** só move o dinheiro, por exemplo para abastecer o caixa. Não muda a quem ele pertence.
- **Repasse do custo:** o envio do custo para o PagBank. O botão **Registrar repasse** já preenche.

Com o caixa físico, o caixa precisa estar aberto: tirar dele vira sangria, colocar vira suprimento. Para desfazer, em **Transferências** clique em **Cancelar transferência** e escreva o motivo.

### Remanejar entre destinações

Muda a quem o dinheiro pertence, sem mexer nas contas (nenhuma transferência é feita). Exemplo: a Reserva passa R$ 500 para Despesas.

1. Em **Destinações**, clique em **Remanejar**.
2. Escolha **De**, **Para**, **Valor**, **Data** e o **Motivo** e confirme.

O valor sai do disponível de quem passa e, se não bastar, da segurança, com um aviso. Entra todo no disponível de quem recebe. Se a destinação não tiver o bastante, o remanejamento é feito mesmo assim: o disponível dela fica negativo (em vermelho) e aparece um aviso. Para desfazer, em **Remanejamentos** clique em **Cancelar remanejamento** e escreva o motivo.

**Remanejar ou escolher no pagamento?** Para pagar uma conta com o dinheiro da Reserva, basta escolher **Reserva de emergência** em "De qual destinação saiu o dinheiro". Não precisa remanejar antes.

## Onde ver

| Tela | O que mostra |
| --- | --- |
| Destinações | O que pertence a cada uma: disponível, segurança, a barra da meta e o "Usado no mês" (amarelo a partir de 50%, vermelho a partir de 90%). Disponível negativo fica em vermelho |
| Remanejamentos | Os remanejamentos feitos, com o motivo, e o botão para cancelar |
| Contas bancárias | O dinheiro que está em cada conta e o **Extrato** por período |
| Repasses entre contas | O custo a repassar, a quem o dinheiro pertence, onde ele está e a diferença entre os dois totais |
| Painel do financeiro | O que pertence a cada destinação e quantos repasses estão pendentes |
| Fluxo de caixa | Filtro **Conta**; "Sem conta" mostra o que ainda não caiu em nenhuma |
| Detalhe do lançamento | Taxa, custo, lucro e a divisão por destinação |

## Outras novidades

### PDV

- **Cadastro rápido de cliente:** clique em **+ Novo cliente**, preencha nome e telefone (CPF é opcional) e clique em **Cadastrar**. O cliente já fica selecionado na venda. O botão fica desativado quando a venda tem uma OS, porque a OS já tem cliente.
- **Troco:** ao escolher **Dinheiro**, aparece o campo **Valor entregue**. Digite quanto o cliente entregou e o sistema mostra o troco, ou quanto falta. Esse valor serve só para a conta na tela e não é gravado.
- **Taxa do cartão:** agora vem marcada como **Assumir**. Para cobrar a taxa do cliente, clique em **Repassar**.

### Clientes

- **Histórico do cliente:** clique no nome do cliente na lista, no ícone de relógio, em **Ver histórico** na edição ou no nome do cliente nos detalhes da OS. A página mostra o total gasto, as ordens de serviço, as compras e as contas a receber.
- **Contato de recado:** quando o cliente tem telefone de recado, aparecem **WhatsApp recado** e **Ligar recado** no histórico, um ícone de balão na lista de clientes e o bloco "Contato de recado" nos detalhes da OS, com o nome de quem atende.
- Clientes sem CPF aparecem como "Não informado", e a impressão da OS não mostra mais "None" nos campos vazios.

### Contas a pagar e a receber

- **Pagamento não sai mais do caixa sozinho:** pagar uma conta com o caixa aberto não desconta do caixa, a menos que você escolha o cofre ou a gaveta do "Conta 4 / Caixa físico" (veja Pagar uma conta).
- **Filtro de vencimento:** nas listas A receber e A pagar, escolha Hoje, Esta semana, Este mês, Próximo mês, Mês anterior ou Personalizado. Funciona junto com o filtro de status.
- **Datas personalizadas:** ao digitar uma data em qualquer filtro de período, o período muda sozinho para "Personalizado" e a data fica guardada depois de filtrar.
- **Valor da despesa recorrente:** ao pagar uma parcela de despesa recorrente, o campo **Valor desta conta** permite mudar o valor daquele mês (por exemplo, a conta de luz). Marque **Usar este valor também nas próximas parcelas em aberto** para repetir o valor nos meses seguintes.

### Mensagens

- A mensagem de aniversário agora diz que o benefício vale por 7 dias.

## Dúvidas frequentes

**O saldo de uma conta não bate com o banco. O que conferir?** Veja, nesta ordem: o saldo inicial e a data dele (nas contas de máquina, se somou o "a receber"); se há recebimentos "Sem conta" no fluxo de caixa; se algum pagamento ficou como "Fora das contas cadastradas"; se algum cartão foi registrado pelo Financeiro em vez do PDV; e se alguma transferência feita no banco não foi registrada. O extrato da conta mostra cada movimento.

**O cartão entra no saldo no dia da venda?** Sim. O valor entra no dia da venda, já sem a taxa, mesmo que a operadora deposite depois. A previsão de quando o dinheiro do cartão cai na conta fica para uma próxima etapa.

**O disponível de uma destinação ficou negativo. Fiz algo errado?** Não. Os gastos ou remanejamentos passaram do que ela tinha; o sistema registra e avisa. O disponível volta a subir com as próximas vendas. Também acontece quando uma venda é cancelada depois de o dinheiro dela já ter sido gasto.

**Recebi em dinheiro com o caixa fechado. E agora?** Esse valor não entrou em nenhuma conta. Some o valor ao **Saldo inicial** do caixa físico: ele entra no cofre. Se o dinheiro foi para a gaveta, abra o caixa e registre um suprimento com o mesmo valor, que passa o dinheiro do cofre para a gaveta.

**Um pagamento antigo saiu do caixa sem eu querer.** Antes desta versão, pagar uma conta com o caixa aberto descontava do caixa automaticamente. Se o caixa físico em Contas bancárias ficou menor, some o valor ao **Saldo inicial** dele. Depois, para a gaveta bater, registre um suprimento no caixa com o mesmo valor.

**O Nubank tem mais dinheiro do que pertence à Reserva. Está errado?** Não. O Nubank guarda o lucro das vendas no Pix de todas as destinações. A lista de contas mostra o dinheiro; **Destinações** mostra a quem ele pertence.

**Registrei o repasse e ele continua pendente.** Confira se o tipo da transferência é **Repasse do custo**. Se não for, cancele a transferência e registre de novo pelo botão **Registrar repasse**.

**A Reserva alcançou a meta. E agora?** Nada muda: ela continua recebendo os 10% do lucro, e a barra mostra "Meta alcançada".

**Posso mudar as porcentagens depois?** Pode, em Destinações (% do lucro) e em Divisão disponível/segurança (80/20). A mudança vale para as próximas entradas; o que já foi dividido fica como estava.
