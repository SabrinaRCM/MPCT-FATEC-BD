## Abstract
Public safety is a hotly debated subject and new ways to help accomplish this task are always emerging, thanks to technology these options have expanded and become more accurate and reliable. One of these technologies is called the Internet of Things (IoT), it is a new concept of using the internet as a way of interconnecting physical objects of our daily lives in the virtual network. Thus, this work aimed to explore the current literature on the Internet of Things (IoT) with application in the security area.

## Resumo 
A segurança pública é um assunto extremamente debatido e sempre estão surgindo novas formas de ajudar a cumprir essa tarefa, graças a tecnologia essas opções se expandiram e se tornaram mais precisas e confiáveis. Uma dessas tecnologias é denominada como Internet da Coisas (IoT), é um novo conceito de utilização de internet sendo uma forma de interconexão dos objetos físicos do nosso cotidiano na rede virtual. Sendo assim, este trabalho teve como objetivo explorar a literatura atual sobre a Internet das Coisas(IoT) com aplicação na área de segurança.


## 1.	Introdução
Segundo dados do Ministério de Justiça e Secretaria Nacional de Segurança Pública, só nos anos de 2020 e 2021 foram registradas 187.033 ocorrências de furtos (sem violência ou grave ameaça ao condutor) de veículos no Brasil. Ainda segundo os dados tiveram 150.288 registros de roubo (com violência ou grave ameaça ao condutor) e 1.439 ocorrências de roubo seguido de latrocínio. Houve uma taxa menor se comparado aos anos anteriores como 2019 por exemplo onde houve 219.325 ocorrências de furto, 184.674 de roubo e 1.493 de roubo seguido de latrocínio. Dados coletados pelo Grupo Tracker, empresa de rastreamento e localização de veículos, a diminuição dos índices de roubos e furtos de veículos tem relação com o impacto da pandemia pois há um menor número de veículos circulando, com o afrouxamento das regras de quarentena, a frequência de veículos aumentou assim como o número de ocorrências.
	Com intuito de auxiliar na proteção do cidadão, surgem no mercado diversas tecnologias capazes de rastrear, emitir alertas e até fotografar o motorista caso seja realizado um roubo. Grande parte dos aplicativos existentes hoje tem como base a IOT (Internet of things) capaz de conectar um dispositivo na rede e trocar informações em tempos real. Este trabalho será baseado no desenvolvimento da IOT. A proposta deste trabalho é apresentar um dispositivo de alarme para veículos que além de disparar e dar um alerta sonoro no veículo, também envia informações através de um aplicativo próprio para o smartphone do proprietário avisando que houve um disparo e manda a localização para que ele possa ir até os órgãos competentes e recuperar seu veículo.

## 2.	Fundamentação Teórica

Nesta seção, aborda – se o conceito de IOT e explica – se brevemente as tecnologias empregadas.

## 2.1.	Conceito de IOT

A Internet das Coisas (IoT) refere – se ao conceito de conectar objetos do dia-a-dia na internet como eletrodomésticos, lâmpadas e outros dispositivos de diversas áreas. O termo foi cunhado pela primeira vez pelo pesquisador Kevin Asthon em 1999 em sua apresentação na P & G sobre a tecnologia RFID e sua aplicação na cadeia de valor e conectada à internet, porém o conceito de base da IoT foi utilizado a primeira vez, 8 anos antes de Asthon, por Mark Weiser em 1991 sob o termo Computação Ubíqua em seu artigo “O computador para o século XXI” para se referir a dispositivos conectados em todos os lugares de forma tão transparente para o ser humano que acabaremos por nem perceber que eles estão lá. “A maioria dos computadores que participam da virtualidade corporificada será invisível de fato, assim como na metáfora.  Já computadores em interruptores de luz, termostatos, aparelhos de som e fornos ajudam a ativar o mundo. Estas máquinas e mais serão interconectados em uma rede onipresente.” (O computador para o século XXI, Mark Weiser). 

## 2.2.	Tecnologias

As principais tecnologias incluídas da IoT são RFID, a tecnologia de sensores e a nanotecnologia. O RFID é a base e o núcleo de rede da construção da Internet das Coisas. 
Entre as tecnologias aplicadas ao mundo da IoT, podemos destacar:
RFID – Radio Frequency Identification – Esse dispositivo normalmente vem em formato de chip e está presente em vários dispositivos como o Sem Parar que é colocado no carro para que alguém entre em shoppings, passe em pedágios e outros acessos sem ter que parar o carro, outro uso para o RFID está sendo em aplicação para identificação de animais;
IP – Internet Protocol – é o principal protocolo de comunicação na Internet. Atualmente, temos dois protocolos IP – Protocolo IPv4 e IPv6.
EPC – Eletronic Product Code – trata-se de uma identificação única gravada em uma etiqueta de RFID, é coordenado pela EPCGlobal que tem o objetivo de padronizar o uso de códigos gravados nas etiquetas (tags) de RFID em esfera global.
Barcode (Código de Barra) – é uma forma de codificar números e letras usando uma combinação de espaços e barras e com isto automatizar o processo de identificação de um objeto. 
Wireless Fidelity (Wi-Fi) – é uma tecnologia de rede que permite a conexão de dispositivos à uma rede através de uma tecnologia sem fio. A padronização e adoção desta tecnologia nos dispositivos móveis (notebooks, telefones celulares, tablets e outros) fez com que se tornasse um padrão de comunicação para praticamente tudo que é conectado à Internet – principalmente os nossos dispositivos e sensores da IoT.
Bluetooth – é uma tecnologia de comunicação, também sem fio, que permite a conexão de dois ou mais dispositivos próximos e com ela é possível construir os conceitos de uma PAN – Personal Area Network, conectado assim o fone ao telefone celular, o mouse no notebook e muitos outros dispositivos entre si.
Wireless Sensor Networks – WSN (em português: RSSF – Rede de sensores sem fio) – que consistem em sensores sem fio para monitorar condições físicas de um ambiente, como por exemplo sensores de fumaça, humidade, temperatura, som, vibração, pressão, movimento e etc. Os sensores tem como objetivo monitorar o ambiente e enviar um sinal para outro dispositivo.
Inteligência Artificial –refere-se a ambientes eletrônicos sensíveis e responsivos à presença de pessoas. Em um mundo de inteligência ambiental, os dispositivos trabalham em conjunto para ajudar as pessoas a realizar suas atividades cotidianas de maneira fácil e natural, usando informações e inteligência ocultas nos dispositivos conectados à rede. 
Cloud Computing (Computação em Nuvem) – A computação em nuvem é a disponibilidade de um serviço de computação invés de um produto, onde recursos compartilhados, software e informações são fornecidas, permitindo o acesso e uso destes serviços através da Internet.
 

## 3.	Metodologia e métodos

Nesta seção, apresenta – se quais tecnologias serão empregadas na construção do projeto.

## 3.1.	Tecnologias empregadas

Para o desenvolvimento de um alarme que atendesse as propostas deste trabalho, temos como principal aplicação a tecnologia WSN (Wireless Sensor Networks) ou RSSF (Rede de sensores sem fio) em português que consiste em sensores capazes de detectar mudanças de variações no ambiente. Os sensores escolhidos foram os de movimento, presença, mecânico e um dispositivo GPS (Global Positioning System ou Sistema de Posicionamento Global em português). Também será desenvolvido um aplicativo para smartphone capaz de receber os sinais enviados por esses sensores e então emitir um alerta por meio de notificação, email ou mensagem.


 
## 4.	Conclusão

Neste trabalho, apresentou – se a proposta de um alarme para veículos que juntamente com um aplicativo para smartphone são capazes de detectar invasões a veículos, bem como, oferece a possibilidade de rastrear caso seja furtado ou o condutor seja abordado e consiga sair da situação com alguma violência leve ou ameaça leve ou grave. Para essa proposta foi apresentado tecnologias a serem utilizadas e explicado a forma de funcionamento. 
Esta proposta visa diminuir o risco para a vítima de roubo e dar segurança a uma vítima de furto, pois ao saber que terá como rastrear seu veículo roubado a tendência do condutor será de não reagir evitando assim que seja usado de violência contra ele. 
 


## Referências

Canaltech. O que é Computação Ubíqua?. Disponível em: https://canaltech.com.br/produtos/O-que-e-Computacao-Ubiqua/.
Costa, C. L., Oliveira, L. and Móta, L. M. S. (2018). Internet das coisas (IOT): um estudo exploratório em agronegócios. Disponível em: https://www.ufrgs.br/cienagro/wp-content/uploads/2018/10/Internet-das-coisas-IOT-um-estudo-explorat%C3%B3rio-em-agroneg%C3%B3cios.docx-Cain%C3%A3-Lima-Costa.pdf.
Dados.MJ. Ocorrências Criminais – Sinesp. Disponível em: http://dados.mj.gov.br/dataset/sistema-nacional-de-estatisticas-de-seguranca-publica.
Future (2020). IoT – Internet das Coisas, conceitos e desafios da segurança. Disponível em: https://www.future.com.br/iot-internet-das-coisas-conceitos-e-desafios-da-seguranca/.
Grupo Tracker (2020). Blog da tracker: Roubo e furto de veículos subiram 12,35% nas últimas duas semanas. Disponível em: https://www.grupotracker.com.br/blog/roubo-e-furto-de-veiculos-subiram-nas-ultimas-duas-semanas.
Junior, A. A. J. and Moreno, E. D. (2015). Segurança em Infraestrutura para Internet das Coisas. Disponível em: https://periodicos.ufpe.br/revistas/gestaoorg/article/viewFile/22122/18487.
Justiça e segurança pública. DADOS E INFORMAÇÕES NACIONAIS DE SEGURANÇA PÚBLICA. Disponível em: https://www.justica.gov.br/sua-seguranca/seguranca-publica/sinesp/1/bi/dados-seguranca-publica.
Lopez (2013). Uma introdução à Internet da Coisas (IoT). Disponível em: https://www.cisco.com/c/dam/global/pt_br/assets/brand/iot/iot/pdfs/lopez_research_an_introduction_to_iot_102413_final_portuguese.pdf.
Red Hat. A INTERNET DAS COISAS: O que é a Internet das Coisas (IoT)?. Disponível em: https://www.redhat.com/pt-br/topics/internet-of-things/what-is-iot.
Weiser, M. (1991). The Computer for the 21st Century Mark Weiser(TRADUÇÂO). Disponível em: https://www.passeidireto.com/arquivo/64603882/the-computer-for-the-21st-century-mark-weiser-traducao.



