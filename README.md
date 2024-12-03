# Projeto-sobre-o-simulador-ns-3
Utilização do Simulador de Redes NS-3
Sobre o Projeto
Este repositório contém o relatório e os resultados de experimentos realizados com o simulador de redes NS-3. O projeto explora desde a preparação do ambiente até a configuração e análise de redes complexas. As atividades envolvem prototipagem, análise de desempenho e adaptação dinâmica em redes Wi-Fi, com uso de ferramentas como GitHub, Jupyter Notebook e GNUPLOT.

Objetivos do Projeto
Preparação do Ambiente:
Configurar ferramentas como GitHub e Jupyter Notebook.
Prototipagem no NS-3:
Simular redes P2P, CSMA e Wi-Fi.
Realizar análises de desempenho, throughput e congestionamento.
Adaptação de Taxa:
Estudar algoritmos para redes Wi-Fi, considerando mobilidade e qualidade do canal.
Principais Atividades
Hands-on 01: Configuração no GitHub

Clone e gerenciamento de repositórios.
Resolução de problemas de autenticação com tokens.
Hands-on 02: Jupyter Notebook

Instalação, configuração e exportação de resultados em PDF.
Atividade 2.2: Comunicação Ponto a Ponto (P2P)

Envio e resposta de pacotes com diferentes taxas de transmissão.
Atividade 2.3: Rede CSMA

Configuração de redes com múltiplos nós e análise via tcpdump.
Atividade 2.4: Redes Wi-Fi e NetAnim

Estudo do impacto da distância e mobilidade no desempenho.
Atividade 2.8: Adaptação de Taxa em Redes Wi-Fi

Simulação de movimentação e ajustes dinâmicos na taxa com o algoritmo Minstrel.
Resultados
Sucesso na simulação de cenários complexos no NS-3.
Gráficos detalhados gerados com GNUPLOT para análise de throughput e congestionamento.
Aprendizado significativo no uso do NS-3 e ferramentas associadas, superando desafios técnicos como integração com VSCode e limitações no NetAnim.

Como Executar as Simulações
Clone este repositório:
bash
Copiar código
git clone <URL-do-repositório>
cd <nome-do-repositório>
Siga as instruções de cada atividade nos arquivos correspondentes.
Execute os códigos no NS-3 conforme os exemplos:
bash
Copiar código
./ns3 run "examples/tutorial/first.cc"
