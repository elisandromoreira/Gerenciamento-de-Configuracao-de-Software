# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.1] - 2020-07-27

### Security

- Páginas 404 com urls de produto único não podem mais ser exploradas usando o Redirecionamento aberto
- Risco de loop infinito no tratamento do Desconto do carrinho em circunstâncias específicas

## [2.0.0] - 2020-07-26

### Added

- Empresas e profissionais podem ter suas mini lojas, de produtos/serviços
- Empresas e profissionais podem configurar um intermediador de meios de pagamento
- Meios de pagamento integrados: Paypal, Pagseguro, Pagarme, Stripe e Cielo.
- Checkout Transparente: Cliente não é redirecionado para a página da intermediadora.
- Cupom de descontos
- Módulo de Afiliados

- Sistema de chat online integrago via API da Twilio
- Chatbot para atendimento automatizado
- Mensagens recebidas, ou trocadas via chat são enviadas para o email da empresa/profissional

* Sistema de Frontend Aberto: Agora é possível criar frontends customizados para a plataforma.

### Changed

- Alteração no padrão da API de REST para GRAPHQL, como forma de otimizar a performance da aplicação
- Alteração da Arquitetura Monolítica para Microserviços

### Removed

- Removido Suporte ao PHP 5.6 e inferior.
- Empresários e Profissionais não podem mais incluir suas próprias configurações de SEO
- Removido Botão de contato vi WhatsApp
- Removido formulário para contato com empresas/profissionais

## [1.4.0] - 2020-07-02

### Added

- Botão Flutuante de contato via whatsapp na página da empresa

### Removed

- Usuários do tipo clientes não podem mais cadastrar empresas / profissionais

## [1.3.0] - 2020-06-30

### Added

- Adicionado selos especiais de QUALIDADE às empresas/profissionais melhores avaliadas e às empresas com mais fãs - O selo é concedido a 1 unica empresa/profissional por critério em cada categoria
- As empresas/profissionais que possuem o selo de qualidade aparecem em posição de destaque em suas categorias. Exemplo: Na categoria Professor Universitário aparece em destaque: "GLAUCIO SCHEIBEL"

## [1.2.1] - 2020-06-26

### Fixed

- Distâncias sendo exibidas em milhas ao invés de quilometros para empresas localizadas no Brasil
- Contadores de comentários aparecendo zerados na página individual da empresa, apesar de aparecerem corretamente na listagem de busca

## [1.2.0] - 2020-06-24

### Added

- Podem ser configuradas unidades de medidas no padrão americano.
- Empresários e Profissionais podem incluir suas próprias configurações de SEO, como palavras chaves, tags e títulos.
- Contadores de comentários e avaliações

### Changed

- Interface de usuário padrão alterada para permitir uma melhor experiencia do usuário e observar padrões de acessibilidade

## [1.1.1] - 2020-06-21

- Erro na página da empresa com avaliações e comentários vazios
- Erro que impedia usuário de deixar de ser fã das empresas.

## [1.1.0] - 2020-06-20

### Added

- Clientes podem tornarem-se fãs de empresas, profissionais, produtos ou serviços clicando no botão favoritar
- Buscas podem ser ordenadas por: proximidade, melhores avaliações, mais fãs...

## [1.0.2] - 2020-06-17

### Fixed

- Erros de Tradução.
- Corrigido erro de importação de arquivos csv, o qual não identificava corretamente as colunas da tabela.
- Corrigido o bug que corrigia o bug que mostrava o presídio quando o usuário buscava pelo termo políticos: Aparentemente tem mesmo alguns políticos no presídio

## [1.0.1] - 2020-06-16

### Fixed

- Campo de busca não estava aparecendo quando o google maps estava em modo full screen
- Corrigido bug que mostrava o presídio quando o usuário buscava pelo termo políticos

## [1.0.0] - 2020-06-15

### Added

- Versão Pública Inicial do Guia Comercial Lançada.
- Adicionados Pacotes Premium que permitem exibir com destaque empresas, profissionais, produtos e serviços
- Produtos e serviços podem ser importados via arquivo csv
- Adicionados Filtros por Bairro, Cidade, Estado e País
- Adicionado Pixel do Facebook para remarketing
- Adicionado Google analytics para empresas/profissionais avaliarem desempenho de suas páginas
- Adicionado formulário para contato com empresas/profissionais
- Adicionada localização via Google Maps.
- Geolocalização e indicação de anunciantes por proximidade
- Traduções adicionadas: en_US, es_ES, RU, FR, DE.

## [0.6.0] - 2020-06-08

### Added

- Empresas podem adicionar galerias de fotos
- Podem ser adicionadas fotos para cada produto ou serviço

## [0.5.0] - 2020-06-05

### Added

- Usuário do tipo cliente pode adicionar um cadastro simples de empresas ou profissionais que não estiverem cadastrados
- Empresários e Profissionais podem reinvindicar a propriedade da página da sua empresa no guia, quando a mesma for criada por um cliente

## [0.4.0] - 2020-06-03

### Added

- Usuários podem compartilhar nas midias sociais suas experiências com empresas, profissionais, produtos e serviços

## [0.3.0] - 2020-06-01

### Added

- Usuários do tipo cliente podem avaliar e/ou adicionar comentários sobre as empresas
- Usuários do tipo cliente podem avaliar e/ou adicionar comentários sobre produtos e/ou serviços

## [0.2.0] - 2020-05-31

### Added

- Adicionado Filtro por ramo de Atividade
- Empresários podem cadastrar filiais para suas empresas
- Empresários/Prestadores de Serviços podem cadastrar produtos e/ou serviços

## [0.1.0] - 2020-05-28

### Added

- Versão inicial de pré lançamento do GUIA COMERCIAL com usabilidade e documentação básicas.
- Adicionado Cadastro de Usuários
- É possível escolher entre os seguintes tipos de Usuários: clientes ou Empresários/Prestadores de Serviços
- Adicionado cadastro de Empresas
