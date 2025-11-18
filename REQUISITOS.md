# Requisitos do Sistema de Registro de Ocorrências com Patrimônio (Recopa)

## Requisitos Funcionais

**RF01**: O sistema deve permitir o registro fotográfico do patrimônio presente em salas de aula e laboratórios.
**RF02**: O sistema deve permitir o registro de ocorrências relacionadas ao patrimônio, como danos ou falta de equipamentos.
**RF03**: Cada registro de ocorrência deve incluir informações detalhadas, como data e hora, localização, descrição do problema (opcional), e a foto do patrimônio (obrigatória).
**RF04**: O sistema deve permitir a visualização de um histórico de ocorrências registradas.
**RF05**: O sistema deve permitir a edição e exclusão de registros de ocorrências.
**RF06**: O sistema deve permitir a categorização das ocorrências por tipo de patrimônio (ex: computadores, projetores, móveis).
**RF07**: O sistema deve permitir a exportação dos registros de ocorrências em formatos comuns (ex: CSV, PDF).
**RF08**: O sistema deve permitir a autenticação de usuários para garantir a segurança dos dados registrados.
**RF09**: O sistema deve ser acessível via dispositivos móveis (smartphones e tablets).
**RF10**: O sistema deve permitir o envio de notificações para os responsáveis quando uma nova ocorrência for registrada.
**RF11**: O sistema deve permitir a sincronização dos dados registrados com um servidor central para backup e análise posterior.
**RF12**: O sistema deve identificar a localização (geolocalização) onde a ocorrência foi registrada, se o dispositivo permitir.
**RF13**: O sistema deve identificar rostos de pessoas nas fotos e aplicar um desfoque automático para proteger a privacidade.
**RF14**: O sistema deve permitir a configuração de níveis de acesso para diferentes tipos de usuários (ex: administrador, usuário comum).
**RF15**: O sistema deve permitir a pesquisa de ocorrências por diferentes critérios (data, tipo de patrimônio, localização).
**RF16**: O sistema deve permitir o upload de múltiplas fotos para um único registro de ocorrência.
**RF17**: O sistema deve fornecer feedback visual ao usuário após o registro de uma ocorrência, confirmando o sucesso da operação.
**RF18**: O sistema deve efetuar a leitura de códigos de barras ou QR codes presentes nos patrimônios para facilitar a identificação dos mesmos durante o registro de ocorrências.

## Requisitos Não Funcionais

**RNF01**: O sistema deve ser desenvolvido utilizando tecnologias que garantam compatibilidade com os principais sistemas operacionais móveis (Android e iOS).
**RNF02**: O sistema deve garantir a segurança dos dados armazenados, incluindo criptografia das informações sensíveis.
**RNF03**: O sistema deve ser responsivo e oferecer uma interface amigável para o usuário.
**RNF04**: O sistema deve ser intuitivo, permitindo que usuários com pouca experiência tecnológica possam utilizá-lo facilmente.
**RNF05**: O sistema deve ter armazenamento local para permitir o uso offline, com sincronização automática quando a conexão for restabelecida.
**RNF06**: O sistema deve armazenar os dados de forma eficiente para minimizar o uso de espaço no dispositivo móvel.
**RNF07**: O sistema deve ser escalável para suportar um número crescente de usuários e registros de ocorrências.
**RNF08**: O sistema deve ser testado em diferentes dispositivos móveis para garantir a compatibilidade e desempenho adequado.
**RNF09**: O sistema deve ser documentado adequadamente para facilitar futuras manutenções e atualizações.
**RNF10**: O sistema deve ser acessível para pessoas com deficiências, seguindo as diretrizes de acessibilidade digital.
**RNF11**: O sistema deve ter um tempo de resposta rápido, garantindo que as operações sejam concluídas em menos de 2 segundos na maioria dos casos.
**RNF12**: O sistema deve ser desenvolvido com práticas de desenvolvimento sustentável, minimizando o consumo de recursos do dispositivo móvel.
**RNF13**: O sistema deve ser compatível com futuras atualizações do sistema operacional móvel, garantindo a longevidade do aplicativo.
**RNF14**: O sistema deve incluir mecanismos de backup automático para evitar perda de dados.
**RNF15**: O sistema deve ser capaz de lidar com falhas de rede de forma graciosa, informando o usuário e tentando reconectar automaticamente.
**RNF16**: O sistema deve ser projetado para suportar múltiplos idiomas, facilitando o uso por usuários de diferentes regiões.
**RNF17**: O sistema deve ser otimizado para minimizar o consumo de bateria do dispositivo móvel durante o uso.