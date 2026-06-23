# Problema
## Descrição
A falta de visibilidade e a obsolescência tecnológica dos sistemas core (desenvolvidos em COBOL/JCL) geram gargalos críticos de manutenção. Precisamos de uma solução capaz de realizar a engenharia reversa desses programas para gerar uma documentação clara e diagramada automaticamente, além de atuar como um motor de modernização, viabilizando a reescrita inteligente desse código legado para linguagens de programação modernas (como C#, Java, Golang, Ruby, etc.).

## Contexto Atual
Atualmente, a instituição sofre com um alto grau de dependência: apenas 3 desenvolvedores dominam o ambiente COBOL. A documentação dos sistemas é escassa ou praticamente nula, resultando em milhares de reais gastos com manutenção e evolução engessadas. A simples inclusão de uma condição em um programa exige aguardar a disponibilidade de um desses três desenvolvedores para que a atividade entre no backlog.

Do ponto de vista de engenharia, já possuímos processos modernos em outras áreas: utilizamos uma esteira de CI/CD no Azure DevOps, versionamento via Git do próprio Azure e a IDE IDzEE para desenvolvimento. O abismo tecnológico está estritamente no legado não documentado.

# Impactos
- Dependência Crítica (Risco de Key Person): Ficar refém de um microgrupo de desenvolvedores especialistas em COBOL, uma linguagem antiga que sofre com a escassez de profissionais e baixa adesão por novos talentos no mercado.

- Estagnação do Negócio (Time-to-Market): A lentidão para alterar os sistemas core freia a agilidade da instituição, prejudicando a competitividade frente a concorrentes mais ágeis e digitalizados.

- Fricção no Crescimento e Onboarding: Novos colaboradores não possuem uma jornada de entrada fluida. Como o COBOL não é amplamente ensinado e o sistema interno não possui documentação, o tempo para que um novo engenheiro gere valor é insustentável.

# Evidências
- Curva de Aprendizado Longa: A ausência de documentação eficiente e o desconhecimento geral sobre a arquitetura Mainframe/JCL tornam a compreensão das regras de negócio atuais um processo exaustivo e demorado.

- Débito Técnico Evolutivo: A evolução do ecossistema fica altamente comprometida pela tecnologia subjacente, impedindo uma transição orgânica e segura para arquiteturas mais modernas e escaláveis.

# Objetivo
## Objetivo Principal
Criar uma plataforma que elimine a barreira do código legado, documentando as regras de negócio de forma automatizada e convertendo os programas originais para linguagens de programação modernas.

## Objetivos Específicos

- Documentação Viva e Visual: Documentar códigos, scripts, fluxos e malhas de forma simples, utilizando texto, imagens e diagramas. Essa documentação deve ser "viva", ou seja, atualizada automaticamente sempre que o programa fonte sofrer alterações.

- Transição Tecnológica: Garantir a capacidade de reescrever e traduzir o programa legado para linguagens de programação mais modernas e com amplo suporte da comunidade, como C# (ambiente .NET), Java, Golang e Ruby.

# Critérios de Sucesso
- Geração de Documentação Viva: Capacidade comprovada da plataforma de gerar e manter atualizada a documentação visual e textual dos programas legados, sem intervenção manual.

- Conversão de Código Bem-sucedida: Capacidade de reescrever e compilar os programas mapeados para qualquer uma das linguagens de programação modernas previamente definidas no escopo (C#, Java, Golang, Ruby, etc.), mantendo a integridade da regra de negócio original.

# Público-Alvo
## Perfil Principal
Profissionais de tecnologia em geral (Desenvolvedores, Analistas de Sistemas, Tech Leads, Arquitetos de Software e QAs).

## Características da Solução

- Usabilidade sem Fricção: Deve ser uma ferramenta web com interface intuitiva, focada em fácil configuração e rápida adoção pelos times de engenharia.

- Democratização do Conhecimento: A documentação e os diagramas gerados devem possuir um nível de clareza tão alto que profissionais com instrução básica em tecnologia ou recém-chegados à empresa consigam compreender as regras de negócio do sistema legado.
