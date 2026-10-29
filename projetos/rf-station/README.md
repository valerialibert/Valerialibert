# 📡 RF STATION
## Estação Experimental de Radiocomunicação Residencial

<p align="center">
  <img src="../../assets/Imagem%20do%20ChatGPT%2029%20de%20out.%20de%202026%2C%2015_39_25.png" alt="Arte conceitual RF STATION: viajante espacial em uma bancada de rádio retrô, com estética anime e planetas ao fundo" width="100%" />
</p>

> **Arte conceitual:** equipamentos e sinais ilustrados não representam montagem ou medições reais.

**Status: Concepção e planejamento — sem implementação física.**  
**Fase do projeto: Ideia inicial.**

Proposta pessoal e acadêmica de Valéria Libert, estudante de Tecnologia em Sistemas de Telecomunicações da UTFPR, para estudar a viabilidade de uma estação residencial em Curitiba (PR) destinada à comunicação com uma estação móvel instalada em um caminhão.

O serviço de radiocomunicação, o equipamento móvel, as frequências, a modulação, as distâncias e os requisitos de operação ainda estão a definir. Não há garantia de comunicação direta em todas as rotas.

## Motivação
Aplicar conhecimentos da graduação em telecomunicações, eletrônica, antenas, linhas de transmissão, propagação e programação. A identidade visual combina rádios antigos, anime e turismo interplanetário.

## Situação atual
- Nenhum equipamento foi comprado ou antena instalada.
- Nenhum circuito ou estação foi construído.
- Nenhum cálculo, simulação, transmissão, teste ou medição foi realizado para o projeto.
- Não há orçamento definitivo ou seleção aprovada de equipamentos.
- A proposta ainda não foi apresentada ou aprovada por professores.
- Não há orientação, vínculo institucional ou enquadramento acadêmico formal aprovado.

A documentação inicial registra intenções e informações fornecidas pela autora. Não constitui evidência de execução técnica.

## Objetivo geral
Estudar a viabilidade técnica, operacional, financeira e regulatória de uma estação experimental de radiocomunicação residencial destinada à comunicação com uma estação móvel instalada em um caminhão.

## Objetivos específicos
- Identificar o rádio móvel, o serviço e as necessidades de comunicação.
- Investigar separadamente Rádio do Cidadão (PX) e Serviço Radioamador.
- Estudar modulações, antenas, linhas de transmissão e propagação aplicáveis.
- Planejar cálculos, simulações Python e análise de orçamento de enlace.
- Avaliar locais, equipamentos, custos, segurança e requisitos regulatórios.
- Preparar metodologia para eventual implementação e validação.
- Documentar hipóteses, decisões, fontes e limitações.

## Questão de pesquisa
É tecnicamente viável estabelecer comunicação entre uma residência em Curitiba e uma estação móvel em um caminhão, considerando equipamento, distâncias, propagação, limitações físicas, custos e regulamentação?

## Arquitetura conceitual
Estação A — residencial proposta ↔ enlace de RF em estudo ↔ Estação B — rádio existente no caminhão, conforme relato da autora.

Na residência, serão estudados transceptor, fonte, antena, cabo coaxial, conectores, proteções e instrumentos. Nenhum componente foi selecionado. A arquitetura poderá mudar após o levantamento de requisitos; infraestrutura intermediária dependerá de viabilidade e condições de uso.

## Áreas técnicas e ferramentas previstas
RF, AM/FM e outros modos aplicáveis, antenas, propagação, linhas de transmissão, eletrônica e análise de sinais. Python é previsto para cálculos e simulações; NumPy, Matplotlib e pandas serão avaliados conforme a necessidade.

Arduino e tela permanecem como frente educacional futura, sujeita a requisitos próprios. Simulações visuais serão diferenciadas de medições reais. Um protótipo educacional de satélite em solo permanece como perspectiva futura, sem previsão de lançamento.

## Etapas previstas
1. Levantamento de requisitos.
2. Pesquisa bibliográfica e regulatória.
3. Modelagem matemática.
4. Simulação computacional.
5. Seleção técnica e financeira de equipamentos.
6. Planejamento da implementação e dos ensaios.
7. Implementação futura, condicionada à viabilidade, segurança e regularidade.
8. Validação experimental futura.

As etapas técnicas não foram executadas. O escopo atual limita-se à organização documental e ao planejamento.

## Organização
- [Visão geral](docs/01-visao-geral.md)
- [Objetivos, justificativa e questões de pesquisa](docs/02-objetivos.md)
- [Requisitos e informações desconhecidas](docs/03-requisitos.md)
- [Fundamentação e fórmulas previstas](docs/04-fundamentacao-teorica.md)
- [Arquitetura conceitual](docs/05-arquitetura-conceitual.md)
- [Pesquisa regulatória](docs/06-regulamentacao.md)
- [Plano de estudos e desenvolvimento](docs/07-plano-de-estudos.md)
- [Referências iniciais](docs/08-referencias.md)
- [Registro de decisões](docs/09-decisoes.md)
- [Cálculos](calculos/README.md), [simulações](simulacoes/README.md) e [software](software/README.md)
- [Equipamentos](hardware/equipamentos-em-estudo.md) e [antenas em estudo](hardware/antenas-em-estudo.md)
- [Planejamento de experimentos](experimentos/planejamento.md)
- [Imagens](imagens/README.md) e [resultados futuros](resultados/README.md)
- [Histórico documental](CHANGELOG.md)

## Considerações regulatórias
PX e Radioamador serão analisados separadamente. Não foram definidos canais, potências ou condições de transmissão autorizadas. A existência do rádio no caminhão não comprova regularidade nem autoriza a operação de outra estação. A verificação será baseada em fontes oficiais vigentes na data de cada análise.

## Próximos passos
- [ ] Identificar fabricante, modelo e documentação do rádio móvel.
- [ ] Registrar necessidades de comunicação e cenários aproximados de distância.
- [ ] Levantar as condições físicas do local residencial.
- [ ] Confrontar os requisitos com fontes técnicas e regulatórias.
- [ ] Delimitar o primeiro cenário teórico antes de selecionar equipamentos.
- [ ] Avaliar uma futura conversa com professores sobre orientação e enquadramento acadêmico.

Não há compras, instalação, transmissão, implementação ou ensaios autorizados nesta etapa.
