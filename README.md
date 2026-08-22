# Exerc2_quinta

## Etapa 1 — Quem está envolvido no projeto
| Pessoa/Grupo | Como fazem parte |
|---|---|
| Secretaria de Educação | É quem pede e acompanha o trabalho, define o que precisa ser feito |
| Pais ou responsáveis pelos alunos | São quem vai pedir e receber a declaração para levar ao Bolsa Família |
| Funcionários da secretaria | São que vão usar o sistema no dia a dia para emitir os documentos |
| Equipe do Bolsa Família | Confere se a declaração está certa e aceita o pedido |
| Quem assina o documento | Assina e assume a responsabilidade pelas informações que estão dentro dele |

---

## Etapa 2 — Transformando o que é vago em algo que dá pra medir
| O que se queria dizer | Como escrever de forma clara e com meta definida | Quem diz qual deve ser o valor |
|---|---|---|
| "O sistema tem que ser fácil de usar" | Emitir as declarações inteiras em até 3 cliques e menos de 2 minutos, sem precisar ler manual | Os próprios funcionários que vão usar todo dia |
| "Os relatórios têm que ser rápidos" | Aparecer o documento na tela em menos de 5 segundos depois de pedir | A secretaria junto com quem vai programar |
| "O sistema não pode dar nenhum problema" | Funcionar 99,5% do tempo durante as aulas; errar os dados em menos de 1 a cada 500 declarações | A secretaria e também os pais que vão usar |
| "Tem que funcionar onde não tem internet" | Emitir e claro imprimir a declaração mesmo sem o sinal, e quando voltar a internet ele atualiza tudo sozinho | Quem faz o sistema e quem usa na zona rural |

---

## Etapa 3 — Termo de Abertura
Veja o arquivo `termo-de-abertura.md` na mesma pasta.

# TERMO DE ABERTURA — Módulo de Declarações para o Bolsa Família
---

## 1. Motivo da iniciativa
Atualmente, todas as declarações são feitas à mão, em papel: cada uma leva em média 15 minutos para ser concluída. Com aproximadamente 120 declarações mensais, isso consome cerca de 30 horas de trabalho dos colaboradores. Além disso, há erros ocasionais nos nomes ou endereços, resultando na devolução do documento pelo Bolsa Família. O sistema Rota Escolar já possui todos esses dados armazenados — assim, basta organizá-los para que o próprio sistema gere a declaração automaticamente, sem necessidade de escrita manual.

## 2. Objetivos a serem alcançados
Integrar ao sistema Rota Escolar uma funcionalidade para a geração automática da declaração de transporte do aluno, com todos os dados já preenchidos, pronta para impressão ou salvamento em PDF, no formato aceito pelo Bolsa Família.

## 3. Indicadores de sucesso
- Reduzir o tempo necessário para elaborar uma declaração: de 15 minutos para, no máximo, 2 minutos
- Eliminar erros de digitação nos dados do aluno
- Diminuir o tempo mensal gasto com esse processo: de 30 horas para, no máximo, 4 horas
- Garantir que o documento saia pronto em PDF, sem necessidade de ajustes posteriores

## 4. Inclusões e exclusões do projeto

### ✅ O que será realizado:
- Criação de uma nova tela dentro do sistema existente
- Nome, escola, rota, período e demais informações preenchidas automaticamente
- Opções para visualizar na tela, imprimir ou salvar em PDF
- Espaço reservado para a assinatura do responsável
- Armazenamento do registro de todas as declarações emitidas

### ❌ O que NÃO será implementado neste momento:
- Envio automático da declaração ao governo ou ao CadÚnico
- Consulta ou verificação da inscrição do aluno no CadÚnico
- Criação de outros documentos, como histórico escolar ou declaração de frequência
- Assinatura digital certificada — o documento será impresso com espaço para assinatura manual.
