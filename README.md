# Atividade 1.
 Primeira atividade no Git e GitHub, que fala e explica características e um pouco de história dos dois.

 Iremos começar pelo Git, mas afinal, o que é isso, quais são suas funcionalidades, recursos e comandos?

O Git é um sistema de controle de versão de distribuição desenvolvido por Linus Torvalds em 2005. Surgiu da necessidade de realizar o gerenciamento do desenvolvimento de kernel do Linux de forma eficiente, já que os sistemas de controle de versão disponíveis na época não atendiam às demandas da comunidade de desenvolvedores.

A história do Git remonta a uma crise no desenvolvimento do kernel do Linux em 2005, quando a relação entre a comunidade de desenvolvedores do kernel e a equipe do BitKeeper, o sistema de controle de versão usado na época, se deteriorou. Como resultado, a licença gratuita para o projeto do kernel do Linux foi revogada, levando Torvalds a criar sua própria solução.

-Git foi projetado com as seguintes características em mente : 

Distribuído: Cada desenvolvedor tem uma cópia completa do repositório, permitindo um desenvolvimento descentralizado e offline.
Velocidade: É notavelmente rápido, mesmo em projetos de grande escala, devido ao seu design eficiente.
Integridade dos Dados: Usa um sistema de hash criptográfico para garantir que os dados do repositório permaneçam seguros e intactos.
Branching e Merging Eficientes: Oferece suporte a ramificações leves e mesclagens rápidas, facilitando o desenvolvimento paralelo e a colaboração.
Flexibilidade: É altamente adaptável e pode ser usado para uma ampla variedade de projetos, desde pequenos projetos individuais até grandes projetos corporativos.

Desde sua criação em 2005, o Git se tornou o sistema de controle de versão mais amplamente utilizado no mundo do desenvolvimento de software, alimentando projetos de código aberto e corporativos em todo o mundo. Sua popularidade é atribuída à sua robustez, flexibilidade e à vasta gama de recursos que oferece para simplificar o gerenciamento de código-fonte.

O Git é um sistema de controle de versão distribuído amplamente utilizado na indústria de desenvolvimento de software. Ele oferece uma série de funções, recursos e comandos para facilitar o gerenciamento de código-fonte.

Uma das principais funções do Git é o controle de versão, que permite acompanhar todas as alterações feitas nos arquivos ao longo do tempo, mantendo um histórico completo. Isso facilita o rastreamento de alterações, permitindo a identificação de quem fez quais alterações e quando foram feitas.

Além disso, o Git suporta o trabalho em equipe, permitindo que vários desenvolvedores contribuam para o mesmo projeto de forma simultânea. Isso é possível graças ao suporte integrado para ramificação e mesclagem. Os desenvolvedores podem criar branches para desenvolver novas funcionalidades ou correções de bugs sem interferir no código principal, e posteriormente mesclar essas alterações de volta para o branch principal.

Outro recurso importante do Git é sua capacidade de desfazer alterações. Se um desenvolvedor comete um erro ou decide descartar uma determinada alteração, é possível desfazer as alterações indesejadas ou restaurar versões anteriores dos arquivos.

O Git também oferece uma série de comandos úteis para realizar operações comuns de controle de versão. Por exemplo, o comando 'git init inicia um repositório Git em um diretório, enquanto o comando 'git clone clona um repositório Git existente para a sua máquina local. O comando 'git add adiciona arquivos modificados ou novos ao índice (staging area), enquanto o comando 'git commit registra as alterações no repositório, adicionando uma mensagem descritiva. Outros comandos úteis incluem 'git push para enviar commits locais para o repositório remoto, 'git pull para atualizar o repositório local com as alterações do repositório remoto, 'git branch para listar, criar ou excluir branches, 'git merge para mesclar as alterações de um branch para outro, entre outros.


*Agora vou falar sobre o Github:


A história do GitHub é fascinante e reflete a evolução da colaboração em desenvolvimento de software na era digital. Fundado em 2008 por Tom Preston-Werner, Chris Wanstrath e PJ Hyett, o GitHub teve origens humildes como uma ferramenta interna para os desenvolvedores do Ruby on Rails. Na época, os fundadores perceberam a necessidade de uma plataforma que simplificasse e tornasse mais eficiente a colaboração em projetos de código aberto. Eles viram que o Git, um sistema de controle de versão distribuído desenvolvido por Linus Torvalds, era uma excelente base para essa plataforma, pois permitia que os desenvolvedores trabalhassem em conjunto de forma descentralizada. Assim, o GitHub nasceu como uma plataforma que combinava o Git com uma interface web amigável e recursos sociais, como issues e pull requests, que facilitavam a colaboração entre os desenvolvedores. Rapidamente, ganhou popularidade entre a comunidade de desenvolvimento de software de código aberto e começou a atrair projetos de todos os tamanhos e de diversas áreas.

À medida que o GitHub crescia, também se tornava um centro vital para a comunidade de desenvolvimento de software, com milhões de desenvolvedores em todo o mundo usando a plataforma para hospedar, colaborar e contribuir para projetos de código aberto. A plataforma se destacava não apenas pela sua funcionalidade técnica, mas também pela sua cultura e comunidade vibrante.

Em 2018, a Microsoft adquiriu o GitHub por US$ 7,5 bilhões, o que gerou alguma apreensão na comunidade sobre o futuro da plataforma. No entanto, a Microsoft se comprometeu a manter o GitHub como uma plataforma aberta e independente, e desde então tem investido em melhorias e novos recursos.

Hoje, o GitHub é uma parte essencial do ecossistema de desenvolvimento de software, usado por empresas, organizações e desenvolvedores individuais em todo o mundo. Sua história é um testemunho do poder da colaboração e do código aberto na construção de tecnologia e comunidades fortes. O GitHub oferece uma ampla gama de recursos e funcionalidades para facilitar o desenvolvimento de software em equipe. Repositórios, issues, pull requests (PR), forks e branches são algumas das principais funcionalidades que permitem aos desenvolvedores trabalhar de forma colaborativa e eficiente.

As issues são utilizadas para rastrear tarefas, bugs ou melhorias em um projeto, enquanto os pull requests facilitam o processo de revisão de código, permitindo que outros colaboradores analisem e comentem sobre as alterações propostas antes da mesclagem no código principal. Além disso, o GitHub oferece suporte para forks, que são cópias de um repositório existente que podem ser modificadas sem afetar o repositório original, e integração contínua (CI) para automatizar testes e builds. Outros recursos incluem GitHub Pages para hospedar websites diretamente do GitHub e GitHub Actions para automatizar fluxos de trabalho.



*Agora um breve passo a passo de como postar seu projeto online:

Primeiro, certifique-se de ter o Git instalado em seu sistema. Se ainda não o tiver, você pode baixá-lo e instalá-lo a partir do site oficial do Git. Em seguida, crie uma conta no GitHub se ainda não tiver uma. É gratuito e fácil de configurar. Depois de criar sua conta, faça login no GitHub.

Agora, configure o Git com seu nome de usuário e endereço de e-mail usando os seguintes comandos no terminal:
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"

Com o Git configurado, crie um novo repositório no GitHub clicando no botão "New" em sua página inicial. Dê um nome ao seu repositório, adicione uma descrição opcional e escolha se deseja que seja público ou privado. Clique em "Create repository" para criar o repositório.

No terminal, navegue até o diretório onde está seu projeto e clone o repositório recém-criado usando o comando:
git clone URL_DO_REPOSITÓRIO

Mova os arquivos do seu projeto para o diretório clonado e adicione-os ao índice do Git com o comando:
git add .

Faça um commit das suas alterações com uma mensagem descritiva usando o comando:
git commit -m "Mensagem descritiva do commit"

Por fim, envie suas alterações para o repositório remoto no GitHub com o comando:
git push origin NOME_DO_BRANCH

Substitua NOME_DO_BRANCH pelo nome do branch em que está trabalhando, geralmente "master" ou "main".


