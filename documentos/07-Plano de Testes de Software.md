# Plano de Testes de Software

Os testes funcionais a serem realizados na aplicação são descritos a seguir.
<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td> CT-01: Cadastro e Autenticação </td>
  <td>
   <ul>
      <li>RF-01: Os usuários devem poder criar contas pessoas na aplicação;</li>
      <li>RF-02: Os usuários devem poder fazer login e sair de suas contas.</li>
   </ul>
  </td>
  <td>Verificar se os usuários podem criar contas pessoais, e confirmar que podem fazer login e logout em suas contas</td>
  <td>
   <ol>
    <li>Acessar a página de cadastro;</li>
    <li>Preencher os campos obrigatórios;</li>
    <li>Clicar no botão de cadastro;</li>
    <li>Verificar se foi redireionado corretamente;</li>
    <li>Acessar a página de login;</li>
    <li>Inserir credenciais válidas;</li>
    <li>Clicar no botão de login;</li>
    <li>Verificar se está logado;</li>
    <li>Clicar no botão de logout;</li>
    <li>Verificar se está deslogado;</li>
   </ol>
   </td>
  <td>O usuário consegue criar uma conta e é redirecionado para a página principal, e realizar login e logout com sucesso.</td>
  <td>Ana Luiza</td>
 </tr>
</table>




<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td> CT-02: Navegação e Busca</td>
  <td>
   <ul>
      <li>RF-03: Os usuários podem navegar pelas categorias de modalidades esportivas oferecidas;</li>
      <li>RF-04: Para cada categoria de modalidade esportiva, deve ser fornecida uma breve descrição que introduza os usuários às principais características e benefícios dessa modalidade;</li>
      <li>RF-05: Os usuários podem inserir sua localização ou usar a geolocalização para encontrar estabelecimentos próximos;</li>
      <li>RF-06: A aplicação deve apresentar os resultados das buscas de estabelecimentos em um formato que permita aos usuários escolher entre uma lista ou uma exibição em mapa;</li>
      <li>RF-07: Os usuários podem clicar em um estabelecimento para ver informações detalhadas, incluindo descrição, fotos e preço;</li>
      <li>RF-08: Cada estabelecimento deve ter uma página própria;</li>
      <li>RF-09: Os usuários podem filtrar os resultados por faixa de preço e modalidade esportiva.</li>
   </ul>
  </td>
  <td>Certificar-se de que os usuários podem navegar pelas categorias de modalidades esportivas;
      Garantir que a descrição de cada categoria seja exibida corretamente;
      Verificar se os usuários podem inserir sua localização ou usar geolocalização para encontrar estabelecimentos próximos;
      Confirmar que os resultados da busca são exibidos em um formato que permite escolher entre lista ou mapa;
      Testar se os usuários podem visualizar informações detalhadas de um estabelecimento ao clicar sobre ele;
      Assegurar que cada estabelecimento tenha uma página própria;
      Verificar se os usuários podem filtrar os resultados por faixa de preço e modalidade esportiva;</td>
  <td>
   <ol>
    <li>Acessar a página de categorias;</li>
    <li>Verificar se as categorias são exibidas;</li>
    <li>Clicar em uma categoria;</li>
    <li>Verificar se a descrição é exibida;</li>
    <li>Inserir uma localização;</li>
    <li>Executar a busca;</li>
    <li>Verificar se os resultados são relevantes à localização;</li>
    <li>Executar uma busca;</li>
    <li>Escolher entre lista e mapa;</li>
    <li>Verificar se os resultados são exibidos no formato escolhido;</li>
    <li>Clicar em um estabelecimento;</li>
    <li>Verificar se as informações detalhadas são exibidas;</li>
    <li>Clicar em um estabelecimento;/li>
    <li>Verificar se está na página do estabelecimento;</li>
    <li>Executar uma busca;</li>
    <li>Aplicar filtros;</li>
    <li>Verificar se os resultados são filtrados.</li>
   </ol>
   </td>
  <td>O sistema apresenta uma navegação eficiente, garantindo que as categorias sejam claramente exibidas e acessíveis, proporcionando aos usuários a facilidade de explorar diferentes modalidades. Além disso, as descrições das categorias são apresentadas de forma precisa, fornecendo informações relevantes para uma escolha informada. A funcionalidade de busca demonstra eficácia ao produzir resultados que correspondem à localização inserida, promovendo uma experiência personalizada. A flexibilidade do sistema é evidente na exibição dos resultados, permitindo aos usuários escolher entre lista e mapa de acordo com suas preferências. As informações detalhadas de cada estabelecimento são apresentadas de maneira clara, proporcionando uma visão abrangente, e cada estabelecimento possui sua própria página, contribuindo para uma experiência mais detalhada e personalizada. Além disso, a capacidade de filtrar os resultados conforme as preferências do usuário adiciona uma camada adicional de personalização, aprimorando ainda mais a usabilidade do sistema.</td>
  <td>Alana</td>
 </tr>
</table>




<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-03: Interação do Usuário</td>
  <td>
   <ul>
      <li>RF-10: Os usuários interessados em participar de aulas podem realizar o pré cadastro, onde vai fornecer informações básicas como nome, e-mail e telefone;</li>
      <li>RF-11: Os usuários podem acessar uma seção dedicada a matérias e podcasts motivacionais relacionados à modalidades esportivas;</li>
      <li>RF-13: Os usuários registrados devem poder agendar aulas diretamente na plataforma, se os estabelecimentos permitirem;</li>
      <li>RF-14: Os usuários podem receber confirmações e lembretes de agendamento;</li>
      <li>RF-15: Os usuários registrados podem acompanhar seu progresso, definir metas e receber recomendações personalizadas;</li>
      <li>RF-16: Os usuários podem registrar as aulas que participaram;</li>
      <li>RF-18: Os usuários podem fornecer feedback e avaliações para os estabelecimentos e personal trainers;</li>
      <li>RF-19: Os usuários devem poder entrar em contato com os donos do projeto;</li>
      <li>RF-20: Os usuários devem poder visualizar e alterar suas informações pessoais;</li>
      <li>RF-21: Os usuários devem poder visualizar informações sobre o site Acesso Ativo.</li>
   </ul>
  </td>
  <td>Testar se os usuários interessados podem realizar o pré-cadastro fornecendo informações básicas;
      Confirmar que os usuários podem acessar a seção dedicada a matérias e podcasts motivacionais;
      Verificar se os usuários registrados podem agendar aulas diretamente na plataforma;
      Testar se os usuários recebem confirmações e lembretes de agendamento;
      Assegurar que os usuários registrados podem acompanhar seu progresso, definir metas e receber recomendações personalizadas;
      Confirmar que os usuários podem registrar as aulas que participaram;
      Verificar se os usuários podem fornecer feedback e avaliações para estabelecimentos e personal trainers;
      Testar se os usuários podem entrar em contato com os donos do projeto;
      Garantir que os usuários possam visualizar e alterar suas informações pessoais;
      Confirmar se os usuários podem visualizar informações sobre o site.</td>
  <td>
   <ol>
    <li>Executar o pré-cadastro;</li>
    <li>Preencher as informações;</li>
    <li>Verificar se o pré-cadastro foi concluído;</li>
    <li>Acessar a seção de matérias e podcasts;</li>
    <li>Verificar se o conteúdo é acessível;</li>
    <li>Clicar em um conteúdo;</li>
    <li>Verificar se o conteúdo é exibido corretamente;</li>
    <li>Fazer o login;</li>
    <li>Escolher um estabelecimento;</li>
    <li>Agendar uma aula;</li>
    <li>Verificar se o agendamento foi registrado;</li>
    <li>Agendar uma aula;</li>
    <li>Verificar se recebe confirmação e lembrete;</li>
    <li>Fazer o login;</li>
    <li>Acessar a seção de acompanhamento de progresso;</li>
    <li>Verificar se as informações são exibidas corretamente;</li>
    <li>Clicar no botão de retorno;</li>
    <li>Fazer o login;</li>
    <li>Acessar a seção de registro de aula;</li>
    <li>Registrar uma aula participada;</li>
    <li>Verificar se o registro é concluído;</li>
    <li>Fazer o login;</li>
    <li>Acessar a seção de feedback e avaliações;</li>
    <li>Forneçer feedback e avaliação para um estabelecimento;</li>
    <li>Verificar se o feedback e a avaliação são registrados;</li>
    <li>Acessar a seção de contato;</li>
    <li>Preencher o formulário de contato;</li>
    <li>Verificar se a mensagem é enviada com sucesso;</li>
    <li>Fazer o login;</li>
    <li>Acessar a seção de informações pessoais;</li>
    <li>Verificar se as informações são exibidas corretamente;</li>
    <li>Editar as informações;</li>
    <li>Verificar se as alterações são salvas;</li>
    <li>Acessar a seção de informações sobre o site;</li>
    <li>Verificar se as informações são exibidas corretamente.</li>
   </ol>
   </td>
  <td>O pré-cadastro é concluído com sucesso,e os usuários conseguem acessar matérias e podcasts, o agendamento é realizado com sucesso; o usuário recebe confirmações e lembretes, e consegue acompanhar seu progresso; o usuário consegue registrar as aulas participadas e pode fornecer feedback e avaliações e entrar em contato com os estabelecimentos; o usuário pode visualizar e alterar suas informações pessoais e visualizar informações sobre o site.</td>
  <td>Natan</td>
 </tr>
</table>




<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-04: Responsividade e Adaptabilidade</td>
  <td>
   <ul>
      <li>RNF-01: O Software deve ser responsivo e adaptável em diferentes dispositivos.</li>
   </ul>
  </td>
  <td>Verificar se o software é responsivo e adaptável em diferentes dispositivos.</td>
  <td>
   <ol>
    <li>Acessar a aplicação em um desktop e verificar a formatação;</li>
    <li>Acessar a aplicação em um tablet e avaliar a adaptação da interface;</li>
    <li>Acessar a aplicação em um smartphone e confirmar a responsividade.</li>
   </ol>
   </td>
  <td>A aplicação se adapta corretamente a diferentes dispositivos, como desktops, tablets e smartphones.</td>
  <td>Walter</td>
 </tr>
</table>




<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>









