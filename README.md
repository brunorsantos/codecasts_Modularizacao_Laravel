# codecasts_Modularizacao_Laravel

## Criando nosso dominio

Com um projeto com estrutura padrão do laravel, criar um pasta 'core' e mover todos os arquivo com excessão das models para ele.

  - Criar diretório App\core
  - Mover diretórios em App para App\core (com exceção das models)

Deve ser dar replace em todas as rereferências feitas para app de forma a direcionar para a nova pasta core.

- Executar replace em Core alterando a string 'App\' para 'App\Core\'


Os locais 'bootstrap\app.php', 'config\app.php', 'app\core\providers\RootServiceProvider.php' ainda devem ser alterados para a aplicacao nao quebrar são

- Alterar em bootsrap\app.php os 3 registros de singleton
- Alterar em config\app.php os aplications service providers
- Alterar em app\core\providers\RootServiceProvider.php a funcão map.




