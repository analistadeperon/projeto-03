# projeto-03
<div id="app"></div>


<img class="img-responsive" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRCbmq7BclYTZQSgi9khk1gYL0yJiAzhNDpZw&usqp=CAU">
<html>
    <head>
        <meta charset="UTF-8">
        <link rel="stylesheet" href="../../assets/css/exemplo.css">
        <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
        <link href="https://fonts.googleapis.com/css?family=Oswald:200" rel="stylesheet">
        <title>Usuários</title>
    </head>
    <body>
        <div class="container-table">
            <div class="content">
                <div id="formulario" class="formulario">
                    <div>
                        <form action="createUser.php" method="post">
                            <div id="title">
                                <h1 id="title-form">Cadastro de novo Usuário</h1>
                                <a class="close"><i class="fa fa-times-circle" aria-hidden="true"></i></a>
                            </div>
                            <div class="container-form">
                                <div class="input_div">
                                    <input class="input_form" type="text" name="name" placeholder="Digite seu Nome"
                                    value="" required>
                                </div>
                                <div class="input_div">
                                    <input class="input_form" type="text" name="email" placeholder="Digite seu Email"
                                    value="" required>
                                </div>
                                <div class="input_div">
                                    <input class="input_form" type="text" name="login" placeholder="Digite seu Login"
                                    value="" required>
                                </div>
                                <div class="input_div">
                                    <input class="input_form" type="password" name="password" placeholder="Digite sua Senha" required>
                                </div>
                                 <div class="input_div">
                                    <input class="input_form" type="text" name="telefone" placeholder="Digite seu Telefone"
                                    value="" required>
                                </div>
                                 <div class="input_div">
                                    <input class="input_form" type="text" name="city" placeholder="Digite sua Cidade"
                                    value="" required>
                                </div>
                                 <div class="input_div">
                                    <input class="input_form" type="text" name="state" placeholder="Digite seu Estado"
                                    value="" required>
                                </div>
                                 <div class="input_div">
                                    Sexo:
                                    <input type="radio" name="masc"
                                    value="Masculino" required> Masculino
                                    <input type="radio" name="fem"
                                    value="Feminino" required> Feminino
                                </div>
                            </div>
                            <button class="send-buttons" name="action" value="create"> enviar </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    <div class="container-table">
            <button id="form-button" class="add_table">
                Adicionar Usuário <i class="fa fa-plus" aria-hidden="true"></i>
            </button>
            
            <div class="content">
              <head>
    <meta charset="UTF-8" />
    <title></title>
    <link href='https://fonts.googleapis.com/css?family=Open Sans' rel='stylesheet'>
    <link rel="stylesheet" type="text/css" href="estilo.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
</head>

<body onload="carregar()">
    <header>
        <div class="barra">
            <i class="material-icons mysize" id="info">info</i>
            <h1>Cadastro de Clientes</h1>
            <i class="material-icons mysize2" id="voltar">arrow_back</i>
        </div>
    </header>
        
    <main>
        <div class="home">  
            <form>
                <div class="input-container">
                  <div class="container-pesquisar">
                    <i class="material-icons" id="search">search</i>
                    <input id="pesquisar" type="text" placeholder="Para pesquisar digite o nome do Cliente"/>
                  </div>
                    <ul id="load">
                            <li></li>
                    </ul>
                </div>
            </form>
            <div class="float">
                    <a class="material-icons" id="add">add_circle</a>
            </div>
        </div>
           
        <id="container-cadastro" class="cadastro">
          <form>
                <div class="input-container2">
                    <label for="nome">Nome</label>
                    <input type="text" placeholder="Digite o nome do cliente" id="nome">
                </div>
                  
                <div class="input-container2">
                    <label for="cpf">CPF</label>
                    <input type="number" placeholder="Digite o CPF do cliente" id="cpf">
                </div>
                    
                <div class="input-container2">
                    <div class="styled-select">
                    <label for="sexo">Sexo</label>
                    <select name="" id="sexo" >
                        <option value="" disabled selected>Selecione o sexo</option>
                        <option value="femi">Feminino</option>
                        <option value="masc">Masculino</option>
                        <option value="mt">Outro</option>
                    </select>
                    </div>
                </div>
                    
                <div class="input-container2">
                    <label for="email">E-mail</label>
                    <input type="email" placeholder="Digite o e-mail do cliente" id="email">
                </div>
                 <div class="input-container2">
                    <label for="cpf">CPF</label>
                    <input type="cpf" placeholder="Digite o cpf do cliente" id="cpf">
                </div>

                <div class="input-container2">
                    <label for="telefone">Telefone</label>
                    <input type="phone" placeholder="Digite o Telefone do cliente" id="telefone">
                </div>
                  
                <div class="input-container2">
                    <label for="nascimento">Data de Nascimento</label>
                    <input type="date" placeholder="Digite a data de nascimento" id="nascimento">
                </div>
                <div class="collapse navbar-collapse navbar-ex1-collapse">
				<ul class="nav navbar-nav">
					<li><a href="clientes.html">Clientes</a></li>
					<li><a href="notas-fiscais.html">Notas Fiscais</a></li>
					<li><a href="contas-receber.html">Contas a Receber</a></li>
					<li><a href="bancos.html">Bancos</a></li>
					<li class="active"><a href="contas-bancarias.html">Contas Bancárias</a></li>
					<li><a href="condicoes-pagamento.html">Condições de Pagamento</a></li>
					<li><a href="agencias.html">Agências</a></li>
					<li><a href="funcionarios.html">Funcionários</a></li>
				</ul>
				<ul class="nav navbar-nav navbar-right">
					<li><a href="login.html"><i class="fa fa-sign-out"></i> Sair</a></li>
				</ul>
                <div class="input-container2">
                    <div class="styled-select">
                    <label for="estado">Estado</label>
                    <select name="" id="estado" >
                        <option value="" disabled selected>Selecione o estado</option>
                        <option value="ac">AC</option>
                        <option value="al">AL</option>
                        <option value="ap">AP</option>
                        <option value="am">AM</option>
                        <option value="ba">BA</option>
                        <option value="ce">CE</option>
                        <option value="df">DF</option>
                        <option value="es">ES</option>
                        <option value="go">GO</option>
                        <option value="ma">MA</option>
                        <option value="mt">MT</option>
                        <option value="ms">MS</option>
                        <option value="mg">MG</option>
                        <option value="pa">PA</option>
                        <option value="pb">PB</option>
                        <option value="pr">PR</option>
                        <option value="pe">PE</option>
                        <option value="pi">PI</option>
                        <option value="rj">RJ</option>
                        <option value="rn">RN</option>
                        <option value="rs">RS</option>
                        <option value="ro">RO</option>
                        <option value="rr">RR</option>
                        <option value="sc">SC</option>
                        <option value="sp">SP</option>
                        <option value="se">SE</option>
                        <option value="to">TO</option>
                    </select>
                    </div>
                </div>
          
                <div class="input-container2">
                    <label for="nome">Cidade</label>
                    <input type="text" placeholder="Digite o nome do cliente" id="cidade">
                </div>
          </form>
          
            <div class="button-container-button">
                <i class="btn-salvar" aria-hidden="true"></i>
                <input type="button" value="Salvar" id="btnsalvar">
                <i class="btn-remover" aria-hidden="true"></i>
                <input type="button" value="Remover" id="btnremover">
            </div>
              
        </div>
    </main>

<script type="text/javascript" src="javascript.js"></script>  


