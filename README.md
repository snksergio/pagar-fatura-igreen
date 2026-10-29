# Pagar fatura iGreen · protótipo navegável

Fluxo completo do pagar fatura do app iGreen: Home iGreen, Telecom e o pagamento da fatura com Pix, cartão salvo em 3x, cartão novo, boleto, saldo iGreen e cashback, até o comprovante e o compartilhar.

Abrir: https://snksergio.github.io/pagar-fatura-igreen/

- Esquerda: os fluxos. Meio: o celular e os botões de simular (fatura atrasada, Pix recebido, compensação do boleto...). Direita: as telas do fluxo escolhido.
- Cada fluxo tem link próprio, por exemplo `#boleto`, `#cb-pix`, `#seguro`.
- Tecla H esconde as colunas e os botões para gravar a tela.

## Faturas de energia · padrão do app (Figma V1)

Faturas de energia redesenhadas no padrão do app em produção: ver as faturas, pagar no Pix e no boleto, parcelar, agrupar num boleto único, boleto em emissão, consulta fora do ar, Pix expirado e troca de unidade.

Abrir: https://snksergio.github.io/pagar-fatura-igreen/faturas-energia.html

## Cashback, carteira de cashback e resgate via Pix

O resgate do cashback sem o web view: resgatar o cashback para a carteira de cashback, ver o saldo e o que vence, resgatar via Pix com a chave reconhecida sozinha, chave não encontrada, primeiro resgate sem chave, comprovante, extrato e dúvidas. No padrão do App V1 e da página Pay.

Abrir: https://snksergio.github.io/pagar-fatura-igreen/cashback-carteira.html

A ajuda que mostra que o cashback vira dinheiro: um balão no botão Resgatar, que leva aos três passos e, fechado, vira a linha "Como transformar em dinheiro?" (`#ajuda`).

## Negociar faturas · parcelar, agrupar e desmembrar

As faturas em aberto da Casa no padrão do app: parcelar (entrada e até 12x), agrupar num boleto único e desmembrar o boleto agrupado, que volta a ter um boleto por fatura enquanto não for pago. Traz também os ajustes do Calebe: sem cashback nos cards e no detalhe, a vencida no Pix da energia sem multa e juros, o valor cheio riscado para quem tem economia com desconto e sem o bloco "Consumo de energia".

Abrir: https://snksergio.github.io/pagar-fatura-igreen/faturas-negociar.html

- Embaixo do celular, escolha o cliente: economia com desconto ou normal, com ou sem desconto adicional.
- Links diretos: `#parcelar`, `#parcelar-regras`, `#agrupar`, `#desmembrar`, `#desmembrar-pago`.

## Faturas de energia · v2 com cashback

A versão de design próprio, mais moderna, das faturas de energia: ver as faturas da Casa, pagar a vencida no Pix e a aberta no boleto, boleto em emissão, "já paguei", consulta fora do ar, Pix expirado e saldo insuficiente, troca de unidade e cashback com saldo iGreen. Tem a tipografia, os espaços, as folhas e a animação dos selos de status do cashback v2, e mantém o laranja original.

Abrir: https://snksergio.github.io/pagar-fatura-igreen/faturas-energia-v2.html

- Na tela de pagar, embaixo do celular, escolha a versão do pagamento: Atual modificada, Proposta (sem pagar com o cashback) ou Com cashback.
- Links diretos: `#ver`, `#vencida-pix`, `#aberta-boleto`, `#emissao`, `#ja-paguei`, `#cashback-saldo`.
