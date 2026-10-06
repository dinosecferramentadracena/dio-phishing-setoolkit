Phishing com SEToolkit
Sobre o projeto
Este projeto foi desenvolvido como parte de um desafio da DIO na área de Cibersegurança.

O objetivo foi estudar, em um ambiente controlado, o funcionamento de uma simulação de phishing utilizando o Social-Engineer Toolkit (SEToolkit).

O laboratório foi realizado utilizando máquinas virtuais e uma rede isolada, evitando o uso de contas ou informações reais.

Objetivo
Durante o laboratório foram estudados:

Conceitos de phishing;
Engenharia social;
Utilização do SEToolkit;
Funcionamento de páginas falsas;
Identificação de possíveis indicadores de phishing;
Medidas de prevenção e conscientização.
Ambiente utilizado
Kali Linux
SEToolkit
Máquina virtual para testes
Navegador Web
Rede isolada para laboratório
Instalação
No Kali Linux, o SEToolkit pode ser instalado com:

sudo apt update
sudo apt install set -y
Para iniciar:

sudo setoolkit
Laboratório
O laboratório foi realizado utilizando uma máquina Kali Linux e uma segunda máquina virtual para representar o usuário.

A comunicação entre as máquinas foi realizada através de uma rede isolada.

A ideia foi reproduzir um cenário controlado para entender como uma página de phishing pode tentar induzir um usuário a fornecer informações.

Todos os dados utilizados no laboratório são fictícios. Não foram utilizadas credenciais reais.

Análise
Durante o laboratório foi possível observar alguns pontos que podem ser utilizados para identificar uma tentativa de phishing.

Entre eles:

URL diferente do domínio legítimo;
solicitação inesperada de credenciais;
aparência semelhante a um serviço conhecido;
mensagens que tentam criar urgência;
links recebidos de fontes desconhecidas.
O HTTPS, por si só, não garante que um site seja legítimo. É necessário verificar o domínio e o contexto da solicitação.

Como se proteger
Algumas medidas importantes contra phishing são:

Verificar o endereço do site antes de inserir informações;
Evitar clicar em links suspeitos;
Desconfiar de mensagens inesperadas;
Utilizar autenticação multifator (MFA);
Utilizar senhas diferentes para cada serviço;
Manter sistemas e navegadores atualizados;
Utilizar ferramentas de proteção de e-mail e endpoint.
Visão defensiva
Além de entender como o phishing funciona, também é importante saber como uma equipe de segurança poderia detectar esse tipo de atividade.

Algumas fontes de informação podem ser:

Logs de DNS;
Firewall;
Proxy;
E-mail Gateway;
EDR;
SIEM;
Logs de autenticação.
Esses dados podem ser utilizados para identificar acessos suspeitos, domínios maliciosos e possíveis tentativas de comprometimento.

MITRE ATT&CK
O phishing está relacionado à técnica T1566 — Phishing do MITRE ATT&CK.

https://attack.mitre.org/techniques/T1566/

Aprendizados
Com este laboratório pude praticar conceitos de:

Phishing;
Engenharia Social;
Segurança da Informação;
Segurança Web;
Análise de URLs;
Conscientização de usuários;
Blue Team;
Documentação técnica.
Estrutura do projeto
.
├── README.md
└── images
    ├── 01-laboratorio.png
    ├── 02-setoolkit.png
    ├── 03-pagina-teste.png
    └── 04-maquina-teste.png
Aviso
Este projeto foi desenvolvido exclusivamente para fins educacionais.

Os testes devem ser realizados somente em ambientes próprios, controlados ou com autorização.

Não devem ser utilizadas credenciais, contas, tokens ou informações reais de terceiros.

Autor
**Raphael **

GitHub:
https://github.com/dinosecferramentadracena
