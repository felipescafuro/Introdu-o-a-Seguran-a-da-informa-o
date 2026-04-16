# Introdução a Segurança da Informação
Um notebookLM voltado para o entendimento e nivelamento para a base da segurança da informação

Esse conteudo foi extraido a partir de um curso com muitas referencias

Ele te ajuda com dicas, questionarios, resumos e é excelente para os nossos estudos!

Realizei alguns questionamentos e até solicitei que criasse algumas perguntas para testar meu conhecimento e o que essa IA faz é extremamente incrivel para os nossos estudos, consigo tirar minhas duvidas em determinados assuntos que tenho dificuldade de entender, por exemplo:

Me excplique o que é a camada OSI

E retornou: 

O Modelo OSI é um modelo teórico que divide a comunicação de dados em redes de computadores em 7 camadas, onde cada uma é responsável por uma tarefa específica. Ele serve como uma importante ferramenta de troubleshooting (resolução de problemas), permitindo que profissionais de segurança estruturem o pensamento para identificar falhas.
Abaixo estão explicadas cada uma das camadas, do nível físico até a aplicação:
1. Camada Física (Physical)

    Função: Trata da transmissão de sinais brutos através de meios físicos.
    Dados: Bits.
    Dispositivos: Componentes de hardware como cabos e conectores. O Hub é o dispositivo clássico que opera nesta camada, apenas replicando sinais elétricos.
    Conceitos chave: Taxa de transferência, largura de banda e latência.

2. Camada de Enlace (Data Link)

    Função: Atua na comunicação entre nós da rede e faz a interação entre a camada de rede e a física. É responsável pela detecção e correção de erros de transmissão.
    Dados: Quadros ou Frames.
    Endereçamento: Utiliza o Endereço MAC (endereço físico exclusivo do dispositivo).
    Dispositivos: O Switch opera nesta camada, pois possui "inteligência" para encaminhar o tráfego apenas para o destino correto via MAC.
    Padrões: O padrão Ethernet define como os dados são agrupados em frames e transmitidos pelo cabo.

3. Camada de Rede (Network)

    Função: Responsável pelo roteamento de dados entre diferentes redes lógicas.
    Dados: Pacotes.
    Endereçamento: Utiliza o Endereço IP (origem e destino) para identificar os dispositivos na rede.
    Dispositivos: O Roteador é o equipamento principal, funcionando como uma "ponte" entre diferentes redes.
    Protocolos: IPv4, IPv6 e OSPF.

4. Camada de Transporte (Transport)

    Função: Mantém e monitora as comunicações entre as aplicações, segmentando os dados e remontando-os no destino. Ela permite a multiplexação, ou seja, vários aplicativos usando a rede ao mesmo tempo.
    Dados: Segmentos.
    Endereçamento: Identifica as aplicações através de Portas (ex: Porta 80 para HTTP, 443 para HTTPS).
    Protocolos: TCP (focado em confiabilidade, como e-mail) e UDP (focado em velocidade, como telefonia VoIP).

5. Camada de Sessão (Session)

    Função: Inicia, gerencia e encerra as sessões de comunicação entre as aplicações.
    Dados: Dados.

6. Camada de Apresentação (Presentation)

    Função: Atua na formatação e tradução dos dados para que a camada de aplicação possa compreendê-los.
    Dados: Dados.

7. Camada de Aplicação (Application)

    Função: É a camada mais próxima do usuário final, onde os serviços de rede interagem com os softwares.
    Dados: Dados.
    Protocolos: HTTP, DNS, SNMP, FTP e SMTP.
    Dispositivos: Servidores e Firewalls avançados que analisam o conteúdo das aplicações operam neste nível.

Fique com esse notebookLM que é excelente para testar seus conhecimentos, tirar duvidas, realizar testes:

https://notebooklm.google.com/notebook/3970e82b-4ee3-4ee7-91f9-71ac4f456ec2
