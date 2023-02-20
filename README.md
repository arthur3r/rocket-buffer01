## Sistema de concessionária

1. Ao jogador entrar no marker vai ser aberto um painel.
2. O jogador poderá selecionar a aba do veículo que deseja comprar (Carros, Motos, Barco, etc...)
3. O jogador poderá selecionar o veículo e cor desejada.
4. A compra do veículo será feita quando o jogador clicar no botão de Finalizar a compra.
5. Caso o jogador não queira mais finalizar a compra, clicar no botão de X no painel.
6. O veículo será estacionado no estacionamento dependendo do veículo comprado pelo jogador.


# Tasks list

[] - Criar um marker quando o resource for iniciado.
[] - Verificar se o player está logado no servidor.
[] - Verificar se o player não está em nenhum veículo.
[] - Criar o DX do resource de acordo com o design do Figma. (Supondo que já exista o design feito)
[] - Abrir o DX quando o player hitar o marker.
[] - Exibir as abas dos veículos disponíveis.
[] - Exibir os veículos da aba selecionada pelo player.
[] - Exibir um color picker para o player selecionar a cor desejada.
[] - Deixar o botão de compra desabilitado enquanto o player não selecionar nenhum veículo.
[] - Alterar a cor quando o player selecionar o veículo desejado.
[] - Retirar o dinheiro equivalente ao veículo selecionado pelo player após a compra.
[] - Criar o veículo do player em um lugar apropriado como: (estacionamento se for um carro, caso seja barcos deixa-lo na garagem para retirar no mar.)
[] - Salvar os dados do player e do veículo (NOME, ID, COR(R, G, B), ID DO PROPRIETÁRIO ) no banco de dados (SQLITE ou MYSQL).

# Admin Permissions

- createVehicle -> Givar veículos para players ou para si mesmo, pelo comando: /createvehicle colocando argumentos como: (NOME DO VEÍCULO, ID DO PROPRIETÁRIO, COR).

- deleteVehicle -> Deletar veículos dos players ou de si mesmo ,pelo comando: /deletevehicle 
colocando argumentos como: (NOME DO VEÍCULO, ID DO PROPRIETÁRIO).

### Stacks
> Lua,
> Eventos,
> Formato de Desenho.