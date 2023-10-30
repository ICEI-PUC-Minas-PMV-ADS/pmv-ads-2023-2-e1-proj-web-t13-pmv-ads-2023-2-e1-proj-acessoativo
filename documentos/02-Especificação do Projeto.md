# Especificação do Projeto

## Perfis de Usuários

<table>
<tbody>
<tr align=center>
<th colspan="2">Pefil de Usuário 1 - Iniciante Interessado </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">João é um jovem adulto que nunca praticou esportes regularmente, mas está preocupado com sua saúde e deseja iniciar uma atividade física. Ele não tem conhecimento sobre as diferentes modalidades e não sabe por onde começar.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>João precisa de uma plataforma que o ajude a descobrir e entender as várias modalidades esportivas disponíveis. Ele também quer informações sobre locais próximos que oferecem essas atividades, bem como detalhes sobre preços e estrutura.</td>
</tr>
</tbody>
</table>



<table>
<tbody>
<tr align=center>
<th colspan="2">Pefil de Usuário 2 - Buscando Conveniência </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Renata é uma profissional ocupada que quer melhorar sua saúde e aparência, mas tem pouco tempo livre. Ela busca uma solução que facilite a busca por aulas de atividade física perto de sua casa ou trabalho, para que possa encaixar na sua agenda apertada.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>Renata precisa de uma plataforma que permita a busca rápida e eficiente de aulas em locais próximos a ela. Ela também valoriza informações claras sobre preços e horários para que possa planejar sua participação.</td>
</tr>
</tbody>
</table>



<table>
<tbody>
<tr align=center>
<th colspan="2">Pefil de Usuário 3 - Buscando Motivação</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Carlos é um adulto que já tentou iniciar atividades físicas no passado, mas sempre desistiu devido à falta de motivação e orientação. Ele está interessado em tentar novamente, mas precisa de incentivos e recursos para se manter engajado.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>Carlos procura uma plataforma que não apenas liste aulas e locais, mas também ofereça conteúdo motivacional, como matérias e podcasts relacionados a cada modalidade. Ele deseja sentir-se apoiado e informado ao iniciar sua jornada de bem-estar.</td>
</tr>
</tbody>
</table>



<table>
<tbody>
<tr align=center>
<th colspan="2">Pefil de Usuário 4 - Interessado em Explorar </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Mariana é uma jovem universitária curiosa que gosta de experimentar coisas novas. Ela está interessada em explorar diferentes modalidades esportivas para encontrar algo que se adapte ao seu estilo e gostaria de conhecer as opções disponíveis em sua área.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>Mariana procura uma plataforma que apresenta uma variedade de opções de atividades físicas, com descrições detalhadas e fotos dos estabelecimentos. Ela também valoriza a facilidade de pré-cadastro para testar diferentes aulas.</td>
</tr>
</tbody>
</table>


## Histórias de Usuários

|EU COMO... `QUEM`   | QUERO/PRECISO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|---------------------------|----------------------------------|
|Como um iniciante interessado em atividades físicas                |desejo navegar pelas categorias de modalidades na aplicação                      | para descobrir quais tipos de exercícios estão disponíveis e aprender mais sobre eles.                              |
| Como um iniciante em busca de atividades físicas           | quero inserir minha localização ou usar a geolocalização                 | para encontrar estabelecimentos próximos que ofereçam aulas da modalidade que me interessa.
| Como uma pessoa ocupada               | desejo buscar aulas de atividades físicas com base nos horários disponíveis em minha agenda                     | para escolher opções que se encaixem nos meus compromissos.   
| Como uma pessoa que valoriza seu tempo                | quero acessar rapidamente informações detalhadas sobre os estabelecimentos, incluindo preços                       | para tomar decisões informadas sem gastar muito tempo navegando. 
| Como alguém em busca de motivação                | quero encontrar uma seção dedicada a artigos e podcasts inspiradores relacionados às modalidades esportivas                     | para me manter motivado e aprender mais sobre os benefícios.    
| Como alguém que busca apoio                | quero ter a opção de criar uma conta pessoal na aplicação, onde posso acompanhar meu progresso                       | para definir metas e receber lembretes para minhas aulas.    
| Como alguém curioso                | desejo navegar pelas diversas modalidades esportivas na aplicação                       | para explorar opções diferentes e descobrir atividades que nunca experimentei antes   
| Como alguém interessado em experimentar aulas                | desejo ter a opção de fazer um pré-cadastro rápido e flexível na aplicação                      | para testar diferentes aulas sem compromisso imediato.    

## Requisitos do Projeto

### Requisitos Funcionais

|ID    | Descrição                | Prioridade |
|-------|---------------------------------|----|
| RF-01 |  Os usuários devem poder criar contas pessoais na aplicação                    | ALTA   | 
| RF- 02 |  Os usuários podem fazer login e sair de suas contas                    | ALTA   |
|  RF- 03  |  Os usuários podem navegar pelas categorias de modalidades esportivas oferecidas                    | ALTA   |
|  RF- 04  |  Para cada categoria de modalidade esportiva, deve ser fornecida uma breve descrição que introduza os usuários às principais características e benefícios dessa modalidade                    | MÉDIA   |
|  RF- 05  |  Os usuários podem inserir sua localização ou usar a geolocalização para encontrar estabelecimentos próximos                    | ALTA   |
|  RF- 06  |  A aplicação deve apresentar os resultados das buscas de estabelecimentos em um formato que permita aos usuários escolher entre uma lista ou uma exibição em mapa                    | BAIXA   |
|  RF- 07  |  Os usuários podem clicar em um estabelecimento para ver informações detalhadas, incluindo descrição, fotos e preço                    | MÉDIA   |
|  RF- 08  |  Cada estabelecimento deve ter uma página própria                    | BAIXA   |
|  RF- 09  |  Os usuários podem filtrar os resultados por faixa de preço e modalidade esportiva                    | ALTA   |
|  RF- 10  |  Os usuários interessados em participar de aulas podem realizar o pré cadastro, onde vai fornecer informações básicas como nome, e-mail e telefone                    | ALTA   |
|  RF- 11  |  Os usuários podem acessar uma seção dedicada a matérias e podcasts motivacionais relacionados à modalidades esportivas                    | BAIXA   |
|  RF- 13  |  Os usuários registrados devem poder agendar aulas diretamente na plataforma, se os estabelecimentos permitirem                    | BAIXA   |
|  RF- 14  |  Os usuários podem receber confirmações e lembretes de agendamento                    | MÉDIA   |
|  RF- 15  |  Os usuários registrados podem acompanhar seu progresso, definir metas e receber recomendações personalizadas                    | ALTA   |
|  RF- 16  |  Os usuários podem registrar as aulas que participaram                    | MÉDIA   |
|  RF- 18  |  Os usuários podem fornecer feedback e avaliações para os estabelecimentos e personal trainers                    | ALTA   |
| RF-19 |  Os usuários devem poder entrar em contato com os donos do projeto                    | ALTA   | 
| RF-20 |  Os usuários devem poder visualizar e alterar suas informações pessoais                   | ALTA   | 


**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais

|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 |  O Software deve ser responsivo e adaptável em diferentes dispositivos                    | ALTA   | 
| RNF-02    |  Os dados pessoais dos usuários, como informações de login e informações de pré-cadastro, devem ser armazenados de forma segura                    | ALTA   | 
| RNF-03    |  Manutenção do software em dia                    | ALTA   | 
| RNF-04    |  A aplicação deve ser facilmente atualizável para adicionar novas funcionalidades ou corrigir problemas.                    | ALTA   | 
| RNF-05    |  O código-fonte deve ser bem documentado para facilitar a manutenção contínua.                    | ALTA   | 
| RNF-06    |  Capaz de rodar em qualquer sistema                    | ALTA   | 
| RNF-07    |  Cumprir todas as leis e regulamentos aplicáveis                    | ALTA   | 
| RNF-08    |  O sistema deverá ter alta disponibilidade                    | MÉDIA   | 
| RNF-09    |  O sistema deve ser capaz de lidar com picos de tráfego, especialmente em horários de pico.                    | ALTA   | 
| RNF-10    |  O sistema deve ser projetado para ser escalável, de modo que possa lidar com um aumento no número de usuários e estabelecimentos cadastrados.eracionais, incluindo Windows, macOS, iOS e Android.                    | MÉDIA   | 
| RNF-11    |  O tempo de resposta ao interagir com a aplicação, como fazer buscas ou abrir páginas de detalhes, deve ser rápido.                    | ALTA   | 
| RNF-12    |  A aplicação deve ser compatível com diferentes browsers e sistemas operacionais, incluindo Windows, macOS, iOS e Android.                    | ALTA   | 
| RNF-13    |  O sistema deverá proporcionar acessibilidade para deficientes visuais, auditivas e motoras, seguindo as diretrizes de acessibilidade                    | MÉDIA   | 
| RNF-14    |  A aplicação deve ser capaz de se integrar com serviços de terceiros, como serviços de mapas para exibir a localização dos estabelecimentos.                    | MÉDIA   | 
| RNF-15    |  A aplicação deve ter um sistema de backup regular para garantir a recuperação dos dados em caso de falhas ou perda de dados.                    | BAIXA   | 
| RNF-16    |  A interface da aplicação deve ser intuitiva e de fácil navegação, mesmo para usuários inexperientes                    | MÉDIA   | 
| RNF-17 |  A aplicação deve ser responsiva e funcionar bem em dispositivos móveis, tablets e desktops                    | ALTA   | 

**Prioridade: Alta / Média / Baixa. 

