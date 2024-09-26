---
slug: "informacoes"
title: "Informações"
description: "Informações sobre o provedor."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
weight: 410
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---
* Padrão exige que o prestador solicite autorização para emitir via WebService. A Solicitação deve ser feita na prefeitura do prestador.
* Caso o tomador for um consumidor não identificado informar no campo CPFCNPJTomador o valor ‘77777777777’, no campo RazaoSocialTomador informar ‘Consumidor’ e nos campos TipoLogradouroTomador, LogradouroTomador, TipoBairroTomador, BairroTomador e EmailTomador informar o valor ‘-’, quando não possuir essa informação, e no campo NumeroEnderecoTomador informar valor zero e no campo CEPTomador informar ‘00000000’.
* Caso o tomador for estrangeiro informar no campo CidadeTomador o valor ‘9999’ e no
  campo CidadeTomadorDescricao informar o nome do país, no campo CepTomador informar ‘00000000’.
* Caso o município de prestação for no exterior informar no campo MunicipioPrestacao o valor ‘9999’ e no campo MunicipioPrestacaoDescricao informar o nome do país.
* Quando a situação do RPS for cancelada, deve se informar o motivo do cancelamento no campo MotCancelamento.
