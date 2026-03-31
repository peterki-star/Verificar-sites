## 🔗 Verificador de Links com Screenshot

Projeto desenvolvido para automatizar a validação de links em larga escala, especialmente em cenários com grande volume de campanhas.

A ferramenta utiliza um arquivo Excel como entrada, onde são lidos:
- o nome da campanha
- o link associado

Para cada link, o sistema:
- acessa a página automaticamente
- captura um screenshot da tela
- verifica o status da requisição (HTTP)
- gera um relatório em Excel com o resultado

## ✅ Resultados possíveis

- ✅ Link funcionando normalmente (status 200)
- ❌ Link fora do ar (status 404)
- ❗ Necessita verificação (outros status)

## ⚠️ Observação importante

Mesmo com a automação, recomenda-se validação manual em alguns casos, pois:
- alguns links podem retornar erro momentâneo
- redirecionamentos ou scripts podem afetar a análise automática

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Requests
- Playwright
- OpenPyXL

## 📂 Entrada

Arquivo Excel contendo:
- coluna "nome" (campanha)
- coluna "url de origem" (link)

## 📊 Saída

Um novo arquivo Excel contendo:
- identificação da linha
- nome da campanha
- link original
- status HTTP
- resultado da verificação
- screenshot da página

## 🚀 Objetivo

Reduzir o tempo de validação manual de links e gerar evidências visuais para análise e apresentação.
## 🔗 Verificador de Links com Screenshot

Projeto desenvolvido para automatizar a validação de links em larga escala, especialmente em cenários com grande volume de campanhas.

A ferramenta utiliza um arquivo Excel como entrada, onde são lidos:
- o nome da campanha
- o link associado

Para cada link, o sistema:
- acessa a página automaticamente
- captura um screenshot da tela
- verifica o status da requisição (HTTP)
- gera um relatório em Excel com o resultado

## ✅ Resultados possíveis

- ✅ Link funcionando normalmente (status 200)
- ❌ Link fora do ar (status 404)
- ❗ Necessita verificação (outros status)

## ⚠️ Observação importante

Mesmo com a automação, recomenda-se validação manual em alguns casos, pois:
- alguns links podem retornar erro momentâneo
- redirecionamentos ou scripts podem afetar a análise automática

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Requests
- Playwright
- OpenPyXL

## 📂 Entrada

Arquivo Excel contendo:
- coluna "nome" (campanha)
- coluna "url de origem" (link)

## 📊 Saída

Um novo arquivo Excel contendo:
- identificação da linha
- nome da campanha
- link original
- status HTTP
- resultado da verificação
- screenshot da página

## 🚀 Objetivo

Reduzir o tempo de validação manual de links e gerar evidências visuais para análise e apresentação.
