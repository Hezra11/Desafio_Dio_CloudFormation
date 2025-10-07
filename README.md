# PRIMEIRO PROJETO COM AWS CLOUDFORMATION – CRIANDO BUCKET S3

Para a criação do meu primeiro bucket S3 via CloudFormation optei em criar uma strack a partir de um modelo pré-existente, fazendo o upload de um template JSON, que está disponível nesse repositório na pasta assets.

Sob o nome de *“MyfirstS3Bucket”*, segui para o passo de criação e revisão da configuração, adiei fornecer alguma política, usando apenas a política do IAM, por se tratar do primeiro projeto.

Concluí a criação do bucket aguardando a finalização, que demorou alguns segundos apenas, a page é bem intuitiva, basta seguir a conclusão de cada etapa, resultando no *‘CREATE_COMPLETE’*, mensagem que mostra a criação bem sucedida.

Verifiquei o status do provisionamento na aba ‘eventos’, com a criação bem-sucedida. Já na aba "Recursos", ficou disponível o link direto para o console do S3, se acessar direto o S3 pelo menu principal o bucket criado já estará disponível.

Se depois quiser excluir o bucket criado, basta acessar o bucket e clicar na opção excluir, o bucket e tudo que há nele será excluído com muita facilidade.

Então, esse foi meu primeiro S3 via CloudFormation.
