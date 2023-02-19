<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*Lista de Chamada Universitário*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#autores)
- [Descrição do projeto](#descrição-do-projeto)
- [Diagrama de casos de uso](#diagrama-de-casos-de-uso)
- [Descrição dos casos de uso](#descrição-dos-casos-de-uso)
- [Protótipos de tela](#protótipos-de-tela)
- [Modelo de domínio](#modelo-de-domínio)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-implantação)
- [Referências](#referências)


# Autores

* Eduardo Trova
* Kaue Pacco
* Mateus Ciancio


# Descrição do projeto

*Agora falando da funcionalidade do software, haverá uma lista a esquerda, que será composta pelo nome dos alunos, com checkboxes clicáveis para marcar se a pessoa está presente ou não, no canto inferior esquerdo, está a data da chamada, que o utilizador do software poderá selecionar para alterar alguma outra chamada. Logo acima, há a lista do canto direito, que é responsável por puxar quais alunos estão com atestado naquele dia, assim, deixando-o isento da falta, e acima desta, está o campo de busca, para facilitar caso algum nome específico precise ser conferido. Depois de todos os ajustes feitos, o usuário do software pressiona no botão enviar, podendo depois alterar esse envio se necessário.*

# Diagrama de casos de uso

*![Main](https://user-images.githubusercontent.com/100205866/219978259-00f263c9-6c6b-4ad0-9c62-8274fd23b783.png)*

# Descrição dos casos de uso

*
Caso de uso - Selecionar classe

Identificador 

CSU01 

Nome 

Selecionar classe 

Atores 

Professor 

Sumário 

O professor referente à aula seleciona a respectiva classe para ter acesso aos alunos daquela mesma. 

Complexidade 

Baixa 

Regras de Negócio 

N/D 

Pré-condições 

N/D 

Pós-condição 

Aparecerão apenas os alunos referentes à classe inserida 

Pontos de Inclusão 

N/D 

Pontos de Extensão 

N/D 

  

Fluxo Principal 

Ações do Ator 

Ações do Sistema 

1. O Professor insere o número da classe correspondente. 

  

  

2. O Sistema mostra uma mensagem de carregamento 

  

3. O Sistema valida se há uma classe com o correspondente ao número inserido 

  

4. O Sistema informa os alunos daquela classe. 

 

Fluxo de Exceção 1: 3a. O Sistema não valida uma classe correspondete 

Ações do Ator 

Ações do Sistema 

  

1. O Sistema exibe uma mensagem de erro 

  

2. O Sistema volta para a tela de inserção de classe 

3. O Professor seleciona uma classe existente. 

  

  

4. Volta ao passo 4 do Fluxo Principal. 

 *

# Protótipos de tela

*![SISTEMA DE FREQUÊNCIA](https://user-images.githubusercontent.com/100205866/219977541-e74ac436-0d00-4ea0-b457-e6ded6d1932d.png)*

# Modelo de domínio

*&lt;Modelo de domínio&gt;*

# Decisões de arquitetura

*&lt;Decisões de arquitetura&gt;*

# Diagrama de implantação

*&lt;Diagrama de implantação&gt;*

# Referências

*&lt;Lista de referências&gt;*
