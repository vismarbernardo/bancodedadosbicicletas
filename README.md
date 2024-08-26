Sistema de Empréstimo de Bicicletas
Este projeto é um sistema simples de gerenciamento de empréstimo de bicicletas em uma praça pública, implementado com um banco de dados relacional. O objetivo do sistema é permitir que usuários registrem empréstimos e devoluções de bicicletas em diferentes estações, além de monitorar o status das bicicletas e o histórico de manutenção.

Funcionalidades
Cadastro de Usuários: Registro de usuários com informações como nome, e-mail, telefone e data de nascimento.
Gerenciamento de Bicicletas: Controle de bicicletas disponíveis, seu status (disponível, em manutenção ou indisponível) e a data de aquisição.
Controle de Estações: Administração dos pontos de retirada e devolução das bicicletas.
Empréstimos e Devoluções: Registro de empréstimos realizados por usuários, incluindo a estação de retirada e, posteriormente, a estação de devolução.
Histórico de Manutenção: Registro de todas as manutenções realizadas em cada bicicleta, com a descrição dos reparos.
Estrutura do Banco de Dados
O banco de dados é composto pelas seguintes tabelas:

Usuarios: Armazena informações dos usuários do sistema.
Bicicletas: Armazena os dados das bicicletas disponíveis para empréstimo.
Estacoes: Armazena as diferentes estações de bicicletas disponíveis no sistema.
Emprestimos: Registra os empréstimos realizados pelos usuários e acompanha o status de cada empréstimo.
HistoricoManutencao: Armazena os registros de manutenção das bicicletas, permitindo rastrear o histórico de reparos.
