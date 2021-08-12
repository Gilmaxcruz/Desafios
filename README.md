# TFOQ - Tá Faltando O Que?

<h3>Descrição do projeto</h3>
<p>
Nesse projeto foi desenvolvido um ambiente de movimentação e criação de Mantimentos.
No mesmo será possivel fazer entradas e saídas dos mantimentos e cadastrar seu contexto confome o solicitado.
O projeto tem como base padrão ASP Net MVC sendo estruturado e desenvolvido para modulação de camadas respeitando os requisitos que acompanha esse modelo de desenvolvimento sendo o padrão para grande escala de desenvolvimento sobre projetos.
</p>

<h3>Como funciona</h3>
<p>
Para utilização do mesmo será necessário que o usuário cadastre a unidade de medida, marca, categorias, tipo de mantimento e mantimento.
Os cadastros são auto intuitivos, não sendo necessário explicar como cadastrar cada parte, por finalização será possível movimentar o mantimento cadastrado de forma simples.
Será necessário que compile a aplicação no visual Studio e que execute o novo migration e faça o update para criar o banco.
A listagem dos mantimentos contará com sua linha de exibição sublinhada de vermelho, se caso o estoque esteja zerado ou negativo.
</p>

<p> O projeto contêm tudo para ser executado no próprio repositório, para melhor entendimento existe o SQL de criação do migration e uma imagem para visualização do modelo relacional do banco. Ao Executar o programa, peço que execute o mesmo em modo de produção. O projeto contempla 3 ambientes de execução sendo eles de Development,Production e Staging. Cada um pode ser configurado com o nome do banco que for configurado, se criado o banco de acordo com o Sql.
</p>
  
<h3>Lista de bibliotecas de terceiros utilizadas:</h3>
<ul>
<li>AutoMapper.Extensions.Microsoft.DependencyInjection</li>
<li>FluentValidation.AspNetCore</li>
<li>Microsoft.EntityFrameworkCore</li>
<li>Microsoft.EntityFrameworkCore.Design</li>
<li>Microsoft.EntityFrameworkCore.Relational</li>
<li>Microsoft.EntityFrameworkCore.SqlServer</li>
<li>Microsoft.EntityFrameworkCore.SqlServer.Design</li>
<li>Microsoft.EntityFrameworkCore.Tools</li>
<li>Microsoft.VisualStudio.Web.CodeGeneration.Design</li>
<li>X.PagedList.Mvc.Core</li>
</ul>

<h3>Pontos a serem melhoradas:</h3>
<ol>
<li>implementação dos Services.</li>
<li>Implementação de tratamento de erros.</li>
<li>Utilização de Secret.</li>
<li>Utilização de serviço para mapeamentos de erros durante a utilização do usuário.</li>
<li>O projeto pode ser muito implementado na questão de crescimento das regras de negócio.</li>
<li>Geração de relatório dos mantimentos, assim o usuário consegue em mãos ter os mantimentos para fazer sua formação de pedidos de compra </li>
<li>Podemos fazer inúmeras melhorias de segurança com a utilizar de jwt, por enquanto apenas foi implementado visivelmente na tela inicial.</li>
<li>Interessante a implementação de authorization, bem como implementação de Open ID.</li>
</ol>

<h3>Requisitos obrigatórios entregues.</h3>
<li>Uma aplicação real e simples sem autenticação.</li>
<li>Deve ser possível visualizar todas os tipos mantimentos cadastrados com opção de buscar com filtros.</li>
<li>Deve ser possível cadastrar um novo tipo mantimento.</li>
<li>Deve ser possível alterar um tipo mantimento.</li>
<li>Deve ser possível remover tipos de mantimentos.</li>
<li>Deve ser possível visualizar todos os mantimentos cadastrados com opção de buscar com filtros.</li>
<li>Deve ser possível cadastrar um novo mantimento.</li>
<li>Deve ser possível alterar um mantimento.</li>
<hr></hr>
<p> Em caso de dúvidas, envie um email para 
  <a href="gilmaxsoaresdacruz@gmail.com">gilmaxsoaresdacruz@gmail.com</a>.
</p>
<p>
  <strong>
    Até breve
  </strong>
</p>
