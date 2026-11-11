
ROTEIRO DE APRESENTAÇÃO DO PORTAL DO SERVIDOR

1. APRESENTAÇÃO DO PORTAL DO SERVIDOR

			Bom dia a todos! Meu nome é Bruno e hoje vou apresentar o sistema do Portal do Servidor do Governo de Rondônia, uma plataforma desenvolvida pela SETIC que tem como principal objetivo centralizar informações funcionais e facilitar o acesso dos servidores públicos estaduais aos serviços disponibilizados pela admnistração pública.
			Para que isso aconteça, o sistema funciona como um HUB central que utiliza a integração com diferentes sistemas governamentais, permitindo que plataformas com responsabilidades específicas se comuniquem e disponibilizem informações e serviços de forma centralizada.
			Essa integração contribui para simplificar o acesso dos servidores, melhorar a organização dos processos administrativos e facilitar a utilização dos serviços de Recursos Humanos.


2. SISTEMAS INTEGRADOS AO PORTAL DO SERVIDOR – [[DÚVIDAS]] -> Tópico 1

			Para compreender melhor o funcionamento do Portal, é importante conhecer os principais sistemas relacionados a ele e entender as responsabilidades de cada um.

	2.1. SAURON – Sistema de Autenticação

			O SAURON é responsável pela autenticação dos usuários e pelo controle de acesso ao Portal do Servidor. Sua principal finalidade é identificar e validar a identidade do servidor público antes de permitir o acesso aos recursos disponibilizados pela plataforma.
			Dessa forma, ele desempenha um papel fundamental na segurança do ambiente, permitindo estabelecer a identidade dos usuários que utilizam os serviços do Portal.

	2.2. e-Estado – Gestão de Pessoas

			O e-Estado é utilizado para centralizar e gerenciar informações cadastrais e funcionais dos servidores públicos estaduais.
			Essas informações são fundamentais para a admnistração dos registros funcionais e para os processos de gestão de pessoas, permitindo que os dados necessários às atividades administrativas sejam organizados e disponibilizados aos sistemas integrados.

	2.3. SIF – Sistema Integrado de Frequência

			O SIF é responsável pelo gerenciamento das informações relacionadas à frequência dos servidores públicos estaduais.
			Entre suas atribuições estão o acompanhamento da jornada de trabalho, o controle de faltas e a administração do banco de horas.
			Essas funcionalidades contribuem para o acompanhamento da frequência funcional e para a organização das informações relacionadas à rotina de trabalho dos servidores.


	2.4. SID – Sistema Integrado de Descanso

			O SID é responsável pelo gerenciamento das informações relacionadas às férias dos servidores públicos estaduais.
			Sua finalidade é administrar os períodos de descanso e os respectivos registros, contribuindo para a organização e o acompanhamento das informações relacionadas às férias dos servidores.


3. INTEGRAÇÃO ENTRE OS SISTEMAS

			Depois de conhecer os sistemas envolvidos, é importante entender como essas plataformas trabalham em conjunto dentro do Portal do Servidor.
			O Portal utiliza APIs para realizar consultas aos sistemas responsáveis por determinadas informações. Quando o servidor acessa uma funcionalidade integrada, o Portal solicita os dados necessários e apresenta o resultado diretamente em sua própria interface, dentro de contêineres.
			Isso significa que o servidor consegue consultar informações de diferentes sistemas sem precisar sair do ambiente principal do Portal.
			Por exemplo, ao acessar uma funcionalidade relacionada ao banco de horas, o Portal pode consultar as informações correspontes no SIF e apresentar o resultado na própria página.
			É importante destacar que cada sistema continua responsável por sua área de atuação. O Portal funciona como um ponto central de acesso e apresentação das informações, enquanto os sistemas integrados mantêm suas respectivas responsabilidades.

	3.1. Consultas X Redirecionamentos

			Embora a integração por APIs seja utilizada para apresentar informações dentro do próprio Portal, existem funcionalidades que trabalham de maneira diferente.
			No funcionamento atual do Portal, os casos de redirecionamento identificados estão relacionados à área de Meus Sistemas, à de Eventos e às opções disponíveis no menu de Ajuda.
			Nessas situações, ao selecionar determinada opção, o usuário é encaminhado para outro ambiente, em vez de visualizar o conteúdo dentro de um contêiner na interface principal;
			Portanto, podemos identificar duas formas de interação:
					- Integração por API: Permite consultar informações em outros sistemas e apresentar os resultados diretamente no Portal.
					- Redirecionamento: Encaminha o usuário para outro ambiente, onde a funcionalidade ou o conteúdo é disponibilizado.
				Essa diferença é importante ára compreender que o Portal não utiliza uma única forma de integração para todas as suas funcionalidades.


4. MENUS DO PORTAL DO SERVIDOR – [[DÚVIDAS]] ->Tópico 2

			Os menus do Portal do Servidor são responsáveis por organizar a navegação da plataforma, agrupando funcionalidades e recursos de acordo com suas finalidades.
			Por meio deles, o servidor consegue acessar suas informações pessoais e funcionais, consultar serviços, realizar solicitações e encontrar outros recursos disponibilizados pelo Portal.
			A estrutura principal de navegação é composta pelos menus Início, Minhas Informações, Serviços, Eventos e Ajuda.

	4.1. Início

			É a página inicial do Portal, utilizada como ponto de entrada para o servidor, responsável por apresentar campanhas institucionais e informativos, tendo como principal elemento um carrossel com os conteúdos em destaque.

![[home.png]]

	4.2. Minhas Informações

			É o menu que reúne os módulos destinados à consulta e ao gerenciamento de informações pessoais e funcionais do servidor, disponibilizando opções como Informações Cadastrais, Atualização de Cadastro, Ficha Funcional, Assentamentos, Pagamentos, Cautelas, Mapa de Férias, Frequências, Banco de Horas e Consignados.

![[menu_Minhas_Informações.png]]

	4.3. Serviços

			É o menu responsável por reunir as funcionalidades relacionadas à solicitação de serviços e ao acompanhamento das solicitações realizadas pelo servidor.

![[menu_Servicos.png]]

	4.4. Meus Sistemas

			É uma opção de navegação que permite ao servidor acessar outros sistemas disponibilizados pelo Governo.
			Diferentemente dos módulos apresentados dentro do Portal, essa opção realiza um redirecionamento para outro ambiente.

![[redirec_Meus_Sistemas.png]]

	4.5. Eventos

			É uma opção destinada ao acesso à área de eventos, onde ao ser selecionada, o servidor é redirecionado para outro ambiente, no qual o conteúdo relacionado aos eventos é disponibilizado.

_DEMONSTRAR REDIRECIONAMENTO_ – [[DÚVIDAS]] -> Tópico 3

	4.6. Ajuda

			É um menu que reúne recursos de suporte, orientação e informações relacionadas à utilização do Portal. Dentre as opções disponíveis encontram-se:
				- Sugerir Melhoria: Permite encaminhar sugestões para aprimoramento do Portal.
				- Reportar Bug: Opção destinada ao relato de problemas ou falhas identificadas.
				- Manual: Disponibiliza orientações sobre a utilização da plataforma.
				- Aviso de Privacidade: Apresenta informações sobre o tratamento de dados pessoais.
				- Política de Privacidade: Reúne as diretrizes relacionadas à privacidade e ao uso das informações;
			As opções desse menu encaminham o usuário para os respectivos ambientes ou conteúdos por meio de redirecionamentos.

![[menu_Ajuda.png]]


5. MÓDULOS MINHAS INFORMAÇÕES – [[DÚVIDAS]] -> Tópico 4

		O menu Minhas Informações reúne os módulos destinados à consulta e ao gerenciamento de informações pessoais, cadastrais, funcionais e financeiras dos servidores públicos estaduais.
		Por meio desses módulos, o servidor consegue acessar diferentes registros relacionados à sua vida funcional, acompanhar informações sobre sua jornada de trabalho e consultar dados financeiros.
		É importante destacar que nem todos os módulos funcionam da mesma maneira. Enquanto alguns apresentam informações diretamente na interface do Portal, outros realizam redirecionamentos para sistemas ou ambientes específicos.

	5.1. Informações Cadastrais

		Esse módulo não apresenta as informações diretamente dentro de um contêiner no Portal. Ao selecioná-lo, o servidor é encaminhado para outro ambiente.

	[[DÚVIDAS]] -> Tópicos 4 e 5

	5.2. Atualizar Cadastro

		Esse módulo redireciona o servidor para um sistema específico de atualização cadastral, desenvolvido pelo Governo do Estado de Rondônia, por meio da SETIC.
		Nesse ambiente, o servidor pode atualizar e visualizar seus dados pessoais, encaminhar documentos e acompanhar o andamento do processo por meio de um painel de status, que apresenta informações como data da atualização, data da homologação e situação cadastral.
		O sistema também utiliza informações previamente cadastradas no e-Estado (RH), recuperando esses dados para facilitar o preenchimento. A atualização cadastral é disponibilizada no mês de aniversário do servidor.

![[modulo_Redirec_Att_Cadastral.png]]

	5.3. Ficha Funcional

		O módulo de Ficha Funcional permite que o servidor consulte informações relacionadas ao seu cadastro pessoal e à sua vida funcional diretamente no Portal do Servidor.
		As informações são organizadas em quatro categorias: Pessoal, Documentos, Complementar e Concurso Público. Entre os dados disponibilizados estão informações de identificação, documentação, dados pessoais adicionais e registros relacionados ao concurso público.
		O módulo também orienta o servidor a verificar a correção de suas informações e procurar o setor de Recursos Humanos de sua unidade caso identifique algum dado incorreto ou incompleto.

![[Pasted image 20261111133915.png]]

![[Pasted image 20261111133931.png]]

![[Pasted image 20261111133940.png]]

![[Pasted image 20261111133951.png]]

	5.4. Assentamentos

		O módulo Meus Assentamentos permite consultar registros relacionados à vida funcional do servidor público.
		A tela apresenta a matrícula do servidor e disponibiliza uma área para visualização dos assentamentos existentes. Quando não há registros disponíveis, o sistema informa que não existem dados para serem visualizados.
		O módulo apresenta essas informações diretamente na interface do Portal do Servidor.

![[modulo_Assentamentos.png]]

	5.5. Pagamentos

		O módulo Pagamentos reúne opções relacionadas à consulta de documentos financeiros do servidor público, disponibilizando três funcionalidades: Contracheque, Cédula C e Ficha Anual.

![[modulo_Pagamento.png]]