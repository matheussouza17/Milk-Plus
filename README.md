# Milk-Plus


Este projeto tem por objetivo gerenciar a vaca leiteira, construindo um aplicativo onde irá coletar,  armazenar suas informações, realizar o acompanhamento da alimentação, vacinação, gestação, produção de leite e gerenciar fluxo de caixa.

Foi realizado para o projeto todo o levantamento de requisitos com produtores de leites reais.

O aplicativo irá realizar o cadastro do produtor apenas se ele concordar com os termos da LGPD. O produtor poderá incluir um ou mais funcionários nos quais eles poderão cadastrar, consultar, editar e excluir uma vaca, alimentação, gestação, ordenha e vacina. Somente o produtor poderá gerenciar o caixa. Para o cadastro da vaca será gerado um número de identificação único, com informações do status da vaca, facilitando o controle delas se está produzindo ou não, ou se já não faz parte de sua produção.
Na opção de alimentação, será informado a identificação da vaca (brinco), onde poderá incluir 1 ou mais alimentação, preenchendo a data, hora e a quantidade de alimento ingerido. Na tela aparecerá um valor calculado pelo sistema, caso o produtor ou funcionário opte por uma outra quantidade é necessário alterar os valores no sistema. A ordenha será realizada com identificação da vaca, onde será alimentada e ordenhada, contabilizando a produção do leite, o dia e a duração do processo. 
A gestação será cadastrada para evitar que a vaca seja ordenada e sua alimentação seja adequada para esse período, pois o leite nessa fase não é próprio para consumo. Será inserida a data inicial da gestão e após ter o parto, será cadastrada a data final. A vacinação será realizada com a identificação da vaca e a informação do lote, nome e a data da aplicação da vacina, assim mantendo a saúde em estado adequado para produção. No controle do caixa será lançado de forma simples as receitas e despesas, inserindo o valor, descrição, e o Nome do fornecedor/Pagador, mostrando o saldo total.

A implementação foi realizada em Outsystems, e presente no repositório contém o arquivo oap para consulta do mesmo.
