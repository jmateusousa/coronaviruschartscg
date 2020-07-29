# Corona Vírus Charts CG
https://coronaviruschartscg.web.app/

Eu estava procurando alguma informação sobre o corona vírus em forma de gráficos aqui na minha cidade,  mas, não encontrei pelo menos de forma fácil. Então, em uma madrugada, resolvi criar uma plataforma pra gerar esse tipo de conteúdo com bases nas informações prestadas pela Prefeitura e Secretaria de Saúde de Campina Grande.  O intuito é informar a população da nossa cidade como está a curva de contágio. Acredito que fica mais claro sendo em  gráficos.

Update: a aplicação conta agora com um inteprete em libras, o intuito é que a informação chegue a todos!!

![gráficos](https://media-exp1.licdn.com/dms/image/C5622AQHQEqAWyZi1pg/feedshare-shrink_2048_1536/0?e=1599091200&v=beta&t=AjtSmPc3N3W7gXOfKbKqMISdIE_P9tBoKDRmrWtHhlI)


> Existe uma API que pode ser consultada e integrada a outros sistemas
> de campina grande:

https://coronaviruschartscg.firebaseio.com/covid19cg.json

Retorno GET:

    {
    "confirmados":1288,
    "data_atualizacao":"29/05/2020",
    "leitos_enfermaria":49,
    "leitos_uti":79,"obitos":29,
    "recuperados":627,
    "suspeitos":885
    }
