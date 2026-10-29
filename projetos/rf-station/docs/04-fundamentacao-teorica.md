# Fundamentação e roteiro de modelagem
**Fórmulas previstas para estudos futuros; nenhum cálculo do projeto foi executado.**

## Tópicos
- RF: espectro, frequência, amplitude, fase, potência, AM/FM e modos aplicáveis, largura de banda, SNR e sensibilidade.
- Antenas: monopolo, dipolo, verticais e móveis; impedância, polarização, ganho em dBi/dBd, diagrama, ROE/SWR, casamento e altura.
- Linhas: coaxiais, conectores, atenuação dependente de frequência e comprimento.
- Propagação: espaço livre, terrestre, obstáculos, difração, reflexão, multipercurso, visada, Fresnel, relevo, vegetação e ambiente urbano; ionosfera apenas quando pertinente.
- Sistemas: HF/VHF/UHF como faixas, PX/Radioamador como serviços distintos, simplex, repetidoras, analógico e digital.

## Comprimento de onda e aproximação de antena
λ = c/f, com λ em m, f em Hz e c ≈ 3 × 10^8 m/s.
L ≈ λ/4 é apenas uma aproximação geométrica inicial. Construção, diâmetro, materiais, ambiente, plano de terra e ajuste alteram o dimensionamento; não equivale a uma antena projetada ou validada.

## Potência e perdas
P_dBm = 10 log10(P_mW), para potência positiva.
P_dBW = 10 log10(P_W); P_dBm = P_dBW + 30; P_mW = 1000 P_W.

Perda simplificada de cabo: L_cabo_dB = α_dB_por_m × comprimento_m, usando atenuação de fabricante na frequência de interesse. Somar perdas documentadas de conectores e outros elementos; não atribuir valores arbitrários a hardware real.

Potência entregue à antena, no modelo de perdas: P_ant_dBm = Pt_dBm − Lt_dB.
EIRP_dBm = Pt_dBm − Lt_dB + Gt_dBi.
ERP usa ganho referenciado ao dipolo; manter a referência explícita. Ganhos em dBd e dBi não devem ser misturados sem conversão.

## Espaço livre
FSPL_dB = 32,44 + 20 log10(d_km) + 20 log10(f_MHz), com entradas positivas.
Referência inicial: UIT-R P.525-5, listada em 08-referencias.md.
O modelo pressupõe condições de espaço livre e região de campo distante adequadas. Não incorpora por si só obstáculos, relevo, vegetação, multipercurso ou ionosfera; não fornece garantia de alcance em cenário urbano ou móvel.

## Orçamento de enlace
Pr_dBm = Pt_dBm + Gt_dBi + Gr_dBi − Lt_dB − Lr_dB − Lp_dB.
Lp é a perda do modelo de propagação adotado; outras perdas devem ser explicitadas e contabilizadas uma única vez.
M_dB = Pr_dBm − Srx_dBm, se Pr e sensibilidade Srx forem referidos ao mesmo ponto e às condições compatíveis de modo, largura de banda e qualidade.
Margem positiva isolada não comprova comunicação. Disponibilidade, ruído, interferência, desvanecimento e critério de qualidade devem ser considerados.
Para comunicação bidirecional, avaliar separadamente os dois sentidos.

## Modelos adicionais a pesquisar
Horizonte rádio com hipóteses de refração e alturas; Fresnel com unidades e geometria explícitas; conversão dBd/dBi; SNR e sensibilidade; difração e modelos terrestres adequados ao cenário.
Não adotar um único modelo para todas as faixas e rotas.

## Protocolo futuro
Registrar fonte da fórmula, domínio de validade, unidades, entradas, natureza dos dados, hipóteses, saída, versão e limitações. Cenários hipotéticos e dados medidos terão registros distintos.
