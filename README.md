# Sistema TimeMaster

- Tipo de Sistema: Agenda de serviços (RedeSocial).
- STACK: VILT (Vue, Inertia, Laravel e TailwindCss)
- Template: Está em votação

## Features

### Global

- Suporte (Contato com a plataforma)

- Bloqueio / Desbloqueio (Entre usuários)

- Selo de reconhecimento
	- Documento verificado
	- Nível de prestador (Iniciante, Profissional e Especialista) (Vai subir nível de acordo as avaliações)
		- Você resolveu seu problema ? (1-10)
		- Você foi bem atendido ? (1-10)
		- Voltaria a fazer negócios ? (1-10)
	- Nível do cliente (Bronze, Prata e Ouro) (Vai subir nível de acordo os serviços finalizados)
		- O contrante foi cortez ? (1-10)

### Nível Suporte

- Dashboard
	- Cards (Quantidade de tickets em aberto, respondido e fechado)
	- Gráfico (Quantidade de tickets fechados em cada mês) 
	
- Tickets
	- Filtro (Tipo e Assunto)
	
- Denúncias
	- Filtro (Tipo)
	- Banir
- Posts
	- Pedido de serviço

### Nível Admin

- Dashboard
	- Cards (Quantidade de usuários ativos, Quantidade de serviços postados, Quantidade de clientes e Quantidade de Prestadores)
	- Gráfico (De serviços fechados em cada mês, Registro de novos usuários em cada mês e De denuncias em cada mês)
	
- Usuários (Acessos administrativos)

- Prestadores
	- Banir

- Clientes
	- Banir
	
- Denuncias
	- Filtro (Tipo)
	- Encaminhar decisão

- Tipos de serviços (Sempre que o prestador registrar o próprio tipo de serviço, notifica os moderadores para analisar a ortografia)

- Posts
 - Pedido de serviço
 - Posts do prestador

- Relatórios
	- Posts
	- Serviços fechados
	- Usuários (Prestador e Cliente)

- Configuração
	- Permissões

	
### Nível Prestador

- Suporte (Contato com a plataforma via ticket)

- Posts
	- Pedidos de serviço
		- Definir filtros (Tipo de serviço e Geolocalização)
 	- Apresentação de serviço
  	 	- Comentários
   		- Curtidas
   		- Compartilhar
   		- Favoritar

- Denuncia (Cliente e serviços)

- Perfil
  - Seguidores
  - Anúncio para clientes (Dispara via chat)
  - Clientes (Quando finalizar um serviço, converter em cliente, Somente o prestador vê)
  - Serviços prestados (Quantidade)
  - Avaliações (Quem avaliou, comentário e nota)
  - Configurações
	  - Se vai usar agenda,
	  - Semanas do expediente
	  - Data do inicio e fim de expediente,
	  - Horário de almoço, 
	  - intervalos para descanso, 
	  - Tipos de serviços (Cores, Duração (Opcional))
	  - Se vai tirar horário após ocupar horário

- Ranking (Por nota do cliente)

- Chat (Com o Contratante)
	-  Por nota de avaliação do cliente e prestador (Perto do nome)

- Relatórios
  - Visita ao perfil
  - Serviços


### Nível Cliente

- Tipo (PF ou PJ)

- Suporte (Contato com a plataforma via ticket)

- Posts
 - Postagem de solicitação de serviço (Que foi feito por ele)
 - Timeline dos prestadores que ele segue
   - Comentários
   - Curtidas
   - Compartilhar
   - Favoritar

- Denuncia (Serviços e Prestadores)

- Perfil
  	- Avaliação (Nota, comentário anônimo)

- Lista de prestadores de serviços que já o atenderam

- Ranking (Por tipo de serviço e avaliação dos prestadores)

- Area de pesquisar de prestadores (Quem pesquisa é quem procura um prestador)
	- Filtros (Tipo de serviço, Nota e Geolocalização)

- Chat (Com o Prestador )
  - Por nota de avaliação do cliente e prestador (Perto do nome)
  - Botão para agenda (Quando prestador entrar em contato com o cliente, enviar um botão automático para o cliente fazer agendamento)
