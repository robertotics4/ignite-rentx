# Cadastro de carro

**RF**
[x] Deve ser possível cadastrar um novo carro.

**RN**
[x] Não deve ser possível cadastrar um carro com uma placa já existente.
[x] O carro deve ser cadastrado, por padrão, com disponibilidade.
[x] O usuário responsável pelo cadastro deve ter perfil de administrador.

# Listagem de carros

**RF**
[x] Deve ser possível listar todos os carros disponíveis.
[x] Deve ser possível listar todos os carros disponíveis pelo nome da categoria.
[x] Deve ser possível listar todos os carros disponíveis pelo nome da marca.
[x] Deve ser possível listar todos os carros disponíveis pelo nome do carro.

**RN**
[x] O usuário não precisa estar logado no sistema.

# Cadastro de especificação no carro

**RF**
[x] Deve ser possível cadastrar uma especificação para um carro.

**RN**
[x] Não deve ser possível cadastrar uma especificação para um carro não cadastrado.
[x] Não deve ser possível cadastrar já existente para o mesmo carro.
[x] O usuário responsável pelo cadastro deve ter perfil de administrador.

# Cadastro de imagens do carro

**RF**
[x] Deve ser possível cadastrar a imagem do carro.
[x] Deve ser possível listar todos os carros.

**RNF**
[x] Utilizar o multer para upload dos arquivos.

**RN**
[x] O usuário deve poder cadastrar mais de uma imagem para o mesmo carro.
[x] O usuário responsável pelo cadastro deve ter perfil de administrador.

# Aluguel de carro

**RF**
[x] Deve ser possível cadastrar um aluguel.

**RN**
[x] O aluguel deve ter duração mínima de 24 horas.
[x] Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo usuário.
[x] Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo carro.
[x] O usuário deve estar logado na aplicação

