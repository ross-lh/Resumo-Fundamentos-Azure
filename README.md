# Azure (Cloud Computing)

## Tipos de cloud:
> prós/contras em blockquote

 	-> Privado (<i>on premise</i>) > modelo no qual todo o hardware está situado na própria empresa para a qual a nuvem funcionará exclusivamente.
> prós: ambiente particular, seguro e sob controle total do usuário

> contras: alto custo de manutenção e escalabilidade, espaço físico e demais variáveis de total responsabilidade do usuário

 	-> Pública > provedor (<i>provider</i>) externo contratado, totalmente externo à empresa contratante
> prós: custo reduzido para implementar/escalar, facilidade, elasticidade, disponibilidade, responsabilidade compartilhada, customização e múltiplos serviços

> contras: envolve estratégias específicas e muito conhecimento sobre toda a cadeia de contratação e fornecimento (vide respectivo SLA)

 	-> Híbrida > ambas trabalhando em conjunto, até mesmo distribuindo entre serviços externos diversos. P. ex.: a empresa utiliza serviços em nuvem da Amazon (AWS), Microsoft (Azure) e Google (Google Cloud Platform)
> prós: agrega os benefícios de ambos os modelos, somados à personalização e combinações conforme estratégia e planejamento do usuário

> contras: pode se tornar excessivamente custoso e duplamente honeroso em relação aos outros modelos

## Recursos disponíveis:

* Data Storage, Bastions (Jump Servers), Virtual Machines (VMs), dentre diversos recursos disponibilizados por plataformas como a Azure de serviços em nuvem, vale ressaltar que:
-       Recursos em prévia (preview) não devem ser implementados oficialmente e/ou em soluções e projetos finais, devendo ser experimentados separadamente, por se tratarem de funções não garantidas, ou seja, de alta volatilidade, tanto em estabilidade, quanto em disponibilidade. 

* Calculadora de custos: esta página traz todos os recursos oferecidos em seus valores finais para o consumidor, seja empresa ou pessoa física, para um planejamento estratégico e preciso também em relação ao custos das ferramentas disponíveis na plataforma.

## Caractéristicas da nuvem pública

* Alta disponibilidade
* Gerenciabilidade
* Elasticidade e Escalabilidade
* Governança e Confiabilidade
* Segurança

## -- Modelos de operação -- ##

### IaaS (Interface as a Service)
As instalações físicas são a única parte alheia ao cliente, neste modelo, no qual o contratante dos serviços é responsável por todo o restante da operação.
> Responsabilidades do usuário:
> * Personalização da infraestrutura utilizada
> * Configuração completa
> * Backup
> * Modelo de acesso
> * Redes
> * Gerenciamento e monitoramento manuais
> entre outros

### PaaS (Platform as a Service)
Aqui a infraestrutura e suas variáveis não fazem mais parte do pacote, centralizando os serviços e aplicações em si para focalizar apenas na performance e necessidades específicas.
> Responsabilidades do usuário:
> * Aplicações / Serviços
> * Foco em performance
> * Configurações menos abrangentes

### SaaS (Software as a Service)
Aplicativos prontos para uso, geralmente com GUI amigável e voltados ao público geral, focando em configurações locais e internas à organização.
> Exemplos:
> * MS Office 365
> * MS Teams
> * MS Outlook, Calendários etc

-- ## --

- A cada nível, o grau de configuração, responsabilidades, manutenção e detalhamento de cada <strong>Serviço</strong> diminui, como em linguagens de programação, nas quais, quanto maior o nível, menor fica a verbosidade, complexidade para codar.

![modelo gráfico de responsabilidade compartilhada detalhado por nível de atuação](shared-responsibility.svg)