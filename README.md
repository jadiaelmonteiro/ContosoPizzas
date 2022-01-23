# API Web do ASP.NET executada no .NET Core. A API Web

## Descrição do Projeto
<p align="center">Esse projeto cria, lê, atualiza e exclui pizzas de um cache na memória explorando a criação de um serviço RESTful multiplataforma usando controladores da 
API Web do ASP.NET Core com .NET e C#. Este Projeto usa a CLI (interface de linha de comando) do .NET e o Visual Studio Code para desenvolvimento local...

fonte: https://docs.microsoft.com/pt-br/learn/paths/build-dotnet-applications-csharp/</p>

<h4 align="center"> 
	🚧 Concluído...  🚧
</h4>

### 🎲 Rodando

```bash
# Clone este repositório:
$ git clone <https://github.com/jadiaelmonteiro/ContosoPizzas.git>

# Abra o CLI do .NET no Visual Studio Code:
$ dotnet run

# Abra o terminal httprepl o novo terminal integrado do Visual Studio Code selecionando Terminal > Novo Terminal no menu principal:
$ httprepl https://localhost:{PORT}

# Navegue até o ponto de extremidade Pizza executando o seguinte comando:
$ cd Pizza

# Execute o seguinte comando para ver as ações na API de Pizza:
$ ls

# Faça uma solicitação POST para adicionar uma nova pizza a HttpRepl usando o seguinte comando:
$ post -c "{"name":"Calabresa", "isGlutenFree":false}"

# Para atualizar a nova pizza Calabresa para uma pizza Calabresa com Bacon com uma solicitação PUT com o seguinte comando:
$ put 3 -c  "{"id": 3, "name":"Calabresa com bacon", "isGlutenFree":false}"

# Para verificar se a pizza foi atualizada, podemos executar novamente a ação GET com o seguinte comando:
$ get 3

# Nossa API também pode excluir a pizza recém-criada com a ação DELETE executando o seguinte comando:
$ delete 3

# Para verificar se a pizza foi removida, podemos executar novamente a ação GET com o seguinte comando:
$ get

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [RESTful]
- [API Web do ASP.NET Core]
- [.NET]
- [C#]
