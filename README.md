# Aplicacoes WWAN - Preparação para a demanda de IoT

Trabalho para Redes II


## RESUMO

Wireless Wide Area Network são redes sem-fio que abrangem geograficamente uma grande área como países e continentes. Sua aplicação mais comum é a rede de telefonia.

Com a popularização da internet, evolução dos celulares e demanda por dados, as redes sem-fio tornaram-se essenciais no cotidiano já que estamos sempre conectados. Neste trabalho falaremos sobre as gerações desta comunicação sem fio e abordaremos o que está sendo feito no 5G, que surgiu/surgirá especificamente por conta do IoT.

*Necessário abordar um pouqinho mais sobre o crescimento do IoT*

## WWAN 

WAN (Wide Area Network) é um tipo de rede que abrange uma grande área podendo atingir ou cobrir desde um estado ou até mesmo um país inteiro.
A história da WAN começa em 1965 quando Lawrence Roberts e Thomas Merril ligaram dois computadores, um TX-2 em Massachussets a um Q-32 na Califórnia, através de uma linha telefônica de baixa velocidade, criando a primeira rede de área alargada (WAN).[http://webeduc.mec.gov.br/linuxeducacional/manuais/Tecnologia%20Wireless.pdf]

Um dos principais motivos para a criação dessa rede é que era necessário um meio mais rápido, seguro e de maior alcance para que, principalmente as empresas, pudessem passar e trocar informações, pois a rede LAN 1 já não supria certas necessidades. 

Já a WWAN (Wireless Wide Area Network) são redes sem-fio que abrangem geograficamente uma grande área como países e continentes. Sua aplicação mais comum é a rede de telefonia.

Com a popularização da internet, evolução dos celulares e demanda por dados, as redes sem-fio tornaram-se essenciais no cotidiano já que estamos sempre conectados. Neste trabalho falaremos sobre as gerações desta comunicação sem fio e abordaremos o que está sendo feito no 5G, que surgiu/surgirá especificamente por conta do IoT.

### Vantagens 

* Fornece cobertura sem fio regional, nacional e global.
* Oferecer melhor segurança em relação à WLAN (Wireless Local Area Network), graças à criptografia de 128 bits.
* Utiliza tecnologia de rede para transferir os dados com segurança ou estabelecer conexão com a Internet.
* Quase todas as sub-redes são do tipo Store-and-Forward (armazena e encaminha). Essas redes realizam a tarefa de armazenar temporariamente as mensagens recebidas em buffers internas e uma vez completas essas mensagens são encaminhadas para o salto seguinte até chegar ao destino final.
* Ideal para usuários fora de casa que precisam se conectar em qualquer lugar dentro da própria área de cobertura. 

### Desvantagens

* Qualidade de serviço: menor que a das redes cabeadas. 
* Custo: o preço se comparado, supera as redes cabeadas.
* Segurança: os canais sem fio são mais suscetíveis a interceptores não desejados, as ondas de rádio na transmissão de dados podem interferir em equipamentos de alta tecnologia, como os utilizados em hospitais.
* Baixa transferência de dados: se novamente comparada com as redes cabeadas, ela ainda é muito baixa.

## Sistemas de celulares, a evolução do "G"

*Opcional. Pode-se colocar mais informações nos subtópicos*

Descreveremos neste tópico um pouco sobre cada geração do sistema de comunicação. Esse tipo de rede usa o padrão 802.20 e é qualificado como:

* 2G - GSM (Global System for Mobile Communications ou Sistema Global para Comunicações Móveis);
* 2.5G - GPRS (General Packet Radio Services ou Serviços de Rádio de Pacote Geral);
* 2.75G - EDGE (Enhanced Data GSM Environment ou Ambiente de Dados GSM Melhorado);
* 3G - UMTS (Universal Mobile Telecommunications Service ou Serviço Universal de Telecomunicações Móveis);
* 3.5G - HSPA (High Speed Packet Access).
* 4G - WiMAX e LTE (Long Term Evolution)

Abaixo algumas características das evoluções desta rede.

### 1G (AMPS)

O AMPS (Advanced Mobile Phone System) foi desenvolvido em 1979 nos Estados Unidos. Foi o principal sistema analógico utilizado no mundo, sendo adotado no Brasil em 1991 [https://www.gta.ufrj.br/grad/10_1/movel/evolucao.html]. Era um sistema analógico que permitia apenas a transmissão de voz. Apesar de ter sido o primeiro passo na comunicação via rede apresentava problemas graves de segurança, já que por ser uma transmissão analógica poderia ser facilmente decifrada com um sintetizador de rádio.

### 2G

Nesta geração o sistema de comunicação passou a ser digital, com técnicas como TDMA (Time Division Multiple Access), CDMA (Code Division Multiple Access) e tecnologia GSM (Global System for Mobile Communication) em que "seu diferencial é o uso de cartões de memória SIM (Subscriber Identity 
Module) nos aparelhos, o que possibilita mobilidade terminal, ou seja, levar as características do assinante para outro aparelho ou rede GSM." [https://www.gta.ufrj.br/grad/10_1/movel/evolucao.html].
Diversos serviços foram disponibilizados com a tecnologia GSM. Dentre eles: SMS para mensagens de texto, GPRS para transmissão de pacotes de dados, encaminhamento de chamadas, bloqueio de chamadas recebidas ou efetuadas, configuração sobre o ar (OAT – over the air, isto é, configuração remota do aparelho), broadcast de célula, localização do terminal, AoC (Advice of Charge) para controle pelo usuário do custo das chamadas, chamada em espera, teleconferência, restrição da identificação da chamada, CUGs (Closed User Groups ) e ECT (Explicit Call Transfer). [https://www.gta.ufrj.br/grad/10_1/movel/evolucao.html]

### 3G

Ainda muito difundida, "a 3ª Geração (3G) de redes celulares teve como objetivo oferecer serviços de dados com altas taxas de transmissão" [http://www.teleco.com.br/3g_tecnologia.asp]. Nesta geração já é possível utilizar serviços de dados multimídia, vídeo e acesso a internet, com taxas maiores que 256 kbps [http://repositorio.unicamp.br/jspui/handle/REPOSIP/258935].

O 3G veio para substituir o 2G, aumentando as taxas de transferência de dados, a qualidade da freqüência com menos ainda interferência e a área de alcance.

As melhores vantagens principalmente das tecnologias GSM, GPRS e UMTS são: depois de ter feito uma conexão o aparelho pode ser movimentado para diferentes áreas de cobertura sem que haja perda do sinal de transmissão entre as reconexões; a alta taxa de transmissão pode ser muito aproveitada para conferências e apresentações que necessitam de áudio e som, pois a rede WWAN oferece além de uma alta segurança, praticamente não há perigo de perda de sinal ou desconexão.

### 4G (Long Term Evolution)

Com a demanda por acesso a internet crescendo no mundo todo foi necessário melhorar a rede de comunicação reduzindo seu "custo por bit" e aumentando suas taxas de comunicação. A rede 4G é totalmente baseada no protocolo IP e é considerada (e vendida) como uma banda larga. Possui taxas nominais de 100 Mbps para DownLink e 50 Mbps para 50 Mbps [http://www.teleco.com.br/4g_tecnologia.asp]

### 5G

Com o crescimento de dispositivos conectados à rede, principalmente os IoT, a demanda por uma rede de comunicação melhor já é uma realidade. Quanto a isso, a 3GPP já iniciou o processo de estudo e implementanção da rede 5G. Atualmente estamos no release 15 de desenvolvimento conforme figura abaixo:

![http://www.3gpp.org/images/articleimages/ongoing_releases_900px.JPG]

A previsão de entrega desta nova tecnologia é para 2020.

Segundo o site Teleco[http://www.teleco.com.br/5g_tecnologia.asp], "O objetivo da 5G é viabilizar as seguintes aplicações: IoT Massivo,IoT (aplicações críticas), Acesso Banda Larga Wireless Fixo (1 Gbps), aumentar a capacidade de forma a baixar o custo por bit da banda larga móvel". O mesmo site apresenta uma comparação entre a rede 4G e a rede 5G

 
TABELA [http://www.teleco.com.br/5g_tecnologia.asp]


## Conclusão

## Referências

http://repositorio.unicamp.br/jspui/handle/REPOSIP/258935

https://app.uff.br/riuff/handle/1/4038

http://www.teleco.com.br/tecnocel.asp

https://www.gta.ufrj.br/grad/10_1/movel/evolucao.html

http://www.teleco.com.br/3g_tecnologia.asp

STORCK, Carlos Renato et al. PROPOSTA DE UM FRAMEWORK BASEADO EM MINERAÇÃO DE DADOS PARA REDES 5G. Revista Eletrônica de Sistemas de Informação, v. 16, n. 2, 2017.