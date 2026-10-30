---
layout: babykick
title: "Baby Kick — Política de Privacidade"
lang: pt-BR
---

[English](https://ventskus-roman.github.io/policy/babykick-privacy) · [Русский](https://ventskus-roman.github.io/policy/babykick-privacy-ru) · [Português (Brasil)](https://ventskus-roman.github.io/policy/babykick-privacy-pt-br)

# Baby Kick — Política de Privacidade

Atualizada em: 30 de outubro de 2026

O Baby Kick é desenvolvido por Roman Ventskus, vendedor informado na App Store. Para privacidade ou suporte: [scofield665@gmail.com](mailto:scofield665@gmail.com?subject=Baby%20Kick%20Privacy).

## Registros, iCloud e relatórios

O Baby Kick armazena sessões, contagens e horários dos movimentos, metas, anotações e início/fim das contrações no armazenamento local. Ele está configurado para sincronizar esses registros pelo iCloud/CloudKit da Apple quando disponível. Data prevista do parto, lembretes, idioma e outras preferências ficam no dispositivo. Widgets usam um resumo local compartilhado da sessão e da semana de gestação; uma fila permite salvar depois movimentos registrados fora da tela principal. Essas funções continuam disponíveis com as análises de uso desativadas.

Relatórios são gerados a partir dos registros selecionados. Compartilhar cria um PDF temporário. Serviços e destinatários escolhidos por você podem guardar cópias; excluir uma sessão não revoga um relatório já compartilhado.

## Compras e configuração do app

A Apple processa pagamentos. A RevenueCat valida compras, fornece o status Premium/assinatura, busca opções de compra e restaura o acesso. Ela usa um ID de usuário gerado para o app e informações de compras/transações. Esse ID é pseudônimo e pode estar vinculado ao histórico de compras; não é descrito como anônimo. As compras funcionam independentemente da configuração de análises de uso. O Baby Kick não pede conta no app, nome ou e-mail nesse fluxo.

O app pode guardar localmente a atribuição de um experimento para manter a experiência consistente. Buscar opções atuais de compra/configuração pode enviar o ID à RevenueCat mesmo com análises de uso desativadas. As análises de experimentos são descritas abaixo. Consulte [RevenueCat](https://www.revenuecat.com/privacy) e a [política da Apple](https://www.apple.com/legal/privacy/).

## Análises de uso e sua escolha

Na versão 1.1.1, as análises de uso ficam ativadas por padrão, sem uma solicitação de aprovação na abertura. Uma escolha explícita anterior de desativá-las é preservada. Você pode desativar ou ativar **Share usage analytics** nos Ajustes. Os registros distinguem a configuração padrão das alterações feitas por você. Com a coleta ativada, o cliente envia eventos de uso ao PostHog. Os eventos descrevem abertura, apresentação inicial, ações em recursos, tela de compra/planos, resultados de compras, restauração/cobrança e exposição a experimentos. Incluem ID pseudônimo limitado ao app, derivado do ID RevenueCat, versão/build, ambiente, idioma da interface, país da App Store, primeiro uso/tipo de instalação e atribuição/exposição a experimentos. O SDK pode adicionar modelo/tipo do dispositivo, sistema/versão, idioma do sistema/fuso horário, dimensões da tela, tipo de rede e IDs do SDK/sessão.

Os campos personalizados não incluem contagens ou horários individuais dos movimentos, durações médicas, datas da gestação, respostas, anotações ou conteúdo dos relatórios. Os eventos ainda podem indicar uso de um app de gestação. A configuração do app desativa coleta automática de telas/interações, gravação da tela, captura automática de erros e pesquisas. O projeto PostHog usa US Cloud. O SDK também armazena um UUID aleatório da instalação e usa esse identificador persistente em requisições de configuração e flags de recursos; essas requisições podem incluir o ID de usuário limitado ao app e outros identificadores do SDK.

O enriquecimento GeoIP está desativado para eventos capturados. Requisições de configuração e flags de recursos ainda podem usar uma localização aproximada derivada do IP ao avaliar a requisição; essa avaliação é separada da gravação de geolocalização em eventos de análise ou perfis de usuários. Requisições de rede expõem endereços IP aos provedores. A configuração para descartar IP no projeto compartilhado do PostHog está desativada, e IPs originais e identificadores de requisição podem ser retidos em logs de diagnóstico do provedor. Desativar GeoIP dos eventos não remove IPs nem desativa todo processamento de localização durante requisições.

Com as análises de uso ativadas, a RevenueCat também recebe atributos de app/idioma/país, configuração da coleta e experimento para relacionar compras ao uso. Ao desativar nos Ajustes, o app interrompe novas capturas do cliente e solicita a limpeza dos atributos de análise e da vinculação do ID PostHog, preservando a indicação de que a configuração foi desativada. A sincronização é assíncrona. Ao desativar, o app limpa a fila de análises salva e tenta concluir uma limpeza pendente antes de iniciar o SDK novamente. Se a limpeza falhar, o envio permanece desativado. Requisições já enviadas ou em trânsito não podem ser recolhidas; desativar a coleta não apaga registros já armazenados nos servidores.

A RevenueCat também encaminha eventos de assinaturas ao PostHog para relatórios financeiros. Eventos financeiros antigos sem uma escolha de análise registrada podem ser incluídos. Esse fluxo de servidor é separado dos eventos do cliente; os dados da configuração de coleta e a filtragem do servidor são atualizados de forma assíncrona. O processamento essencial de compras Apple/RevenueCat continua com análises desativadas.

## Retenção e suas escolhas

A janela atual de eventos do PostHog é de **12 meses**; eventos mais antigos são removidos na próxima limpeza mensal. É uma configuração de eventos, não uma promessa de apagar todos os perfis, mensagens ou backups exatamente em 12 meses. Contate-nos para acesso ou exclusão desses registros.

O app não aplica expiração automática ao histórico ou às preferências locais. Sessões individuais podem ser excluídas no Histórico; contrações recentes podem ser limpas no cronômetro. A exibição gratuita de três dias não é um prazo de exclusão. Cópias no iCloud/outros dispositivos, arquivos temporários, backups do sistema e PDFs compartilhados precisam ser tratados separadamente. A versão descrita aqui não oferece uma ação para apagar todo o histórico de uma vez.

O app não define expiração automática para registros de clientes na RevenueCat. Registros de compras dão suporte à validação/restauração e também podem estar sujeitos às obrigações dos provedores. Excluir um cliente na RevenueCat não cancela uma assinatura Apple; restaurar compras pode sincronizar novamente transações. Gerencie ou cancele nos [ajustes de assinaturas Apple](https://apps.apple.com/account/subscriptions).

## Suporte e solicitações sobre dados

Envie e-mail com Baby Kick no assunto. Seu endereço e o conteúdo enviado são processados para responder. Evite enviar anotações/relatórios de saúde, senhas, credenciais Apple ou recibos completos sem um procedimento seguro e necessário acordado. O site antigo de suporte usa Formspree e Google Fonts; a página dedicada do Baby Kick usa links diretos de e-mail, sem formulário ou fontes remotas. A hospedagem pode processar dados técnicos de requisições.

Retemos a correspondência de suporte, dados de contato e identificadores fornecidos pelo tempo necessário para resolver a solicitação, tratar acompanhamentos relacionados, cumprir obrigações legais aplicáveis ou estabelecer, exercer ou defender direitos em processos. Quando essas finalidades deixam de exigir as informações, nós as excluímos ou removemos os detalhes de identificação. Você pode solicitar a exclusão de uma conversa por e-mail. Analisamos a solicitação e explicamos quais informações precisam ser mantidas e por quê. Não prometemos expiração automática da caixa de e-mail nem um prazo fixo de retenção; a janela de 12 meses dos eventos PostHog não se aplica ao e-mail de suporte.

Para acesso, correção ou exclusão, informe quais registros: histórico local/iCloud, análises de uso/financeiras ou conversa de suporte. Nas versões com **Copy support ID** nos Ajustes, você pode copiar o identificador limitado ao app e incluí-lo na solicitação. Ele não contém registros de saúde. Copiar não envia nada nem muda sua configuração de análises; o item da área de transferência é configurado para permanecer neste dispositivo e expirar após cinco minutos. Versões anteriores podem não oferecer o controle; avise se não encontrar o ID. Uma verificação mínima pode ser necessária. E-mail sozinho não identifica com segurança registros pseudônimos. Não solicitamos nem acessamos suas credenciais Apple para remover dados privados do iCloud.

Desativar análises, remover o app, excluir dados anteriores e cancelar assinatura são ações separadas. Conforme a lei aplicável, você também pode solicitar restrição, opor-se ao tratamento, retirar consentimento ou reclamar à autoridade competente. Explicamos o escopo concluído e eventuais limitações técnicas ou legais aplicáveis.

## Alterações e contato

Atualizamos a página e a data quando o tratamento muda. Privacidade/suporte: [scofield665@gmail.com](mailto:scofield665@gmail.com?subject=Baby%20Kick%20Privacy).


[Privacy](https://ventskus-roman.github.io/policy/babykick-privacy-pt-br) · [Support](https://ventskus-roman.github.io/policy/babykick-support-pt-br) · [Terms](https://ventskus-roman.github.io/policy/babykick-terms-pt-br)
