# bugereats001
Mapeamento de cenários

### language: pt-br

## Funcionalidade: Home

  **Eu** como usuário 
	
  **Quero** criar um cadastro
	
  **Para** poder ter acesso a aplicação
  

## Esquema do Cenário: home “estado”

	Dado que um usuário logado

	Quando acessar a página home

	Então irá ter acesso a aplicação


Exemplos:

**|          estado           |**

|          logado           |

|          não logado       |


## Funcionalidade: Cadastro

**Eu** como usuário 

**Quero** criar um cadastro

**Para** poder realizar as funcionalidades da aplicação


Cenário: cadastro

	Dado que sou um usuário ainda não cadastrado

	Quando eu preencher o formulário de cadastro

	        E eu clicar no botão cadastrar
	
	Então serei redirecionado para a tela inicial

	        E já estarei logado
	

## Funcionalidade: Login

**Eu** como usuário 

**Quero** realizar o login

**Para** poder acessar as funcionalidades da Buger Eats


Cenário: Login

	Dado que um usuário já cadastrado 

	        E não logado
	
	Quando preencher o formulário de login

	        E clicar no login
	
	Então serei redirecionado para a tela inicial

