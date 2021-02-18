# Controle de repositórios

A discussão sobre ferramentas de restrição de acesso veio à tona em algumas conversas. Por isso, resolvi explorar algumas ferramentas que podem simplificar o uso da plataforma GitHub como ferramenta de aprendizado à distância.

## Objetivos do uso da plataforma
É importante estabelecer o escopo de uso da plataforma listando quais objetivos você quer alcançar. Cada pergunta respondida abaixo determinará que ferramentas e configurações você deverá utilizar.

Como uma ferramenta baseada em Git, o GitHub oferece maneiras de interação com o conteúdo disponibilizado em seus repositórios. Quando um usuário não possui acesso de colaborador a repositórios feitos por outros usuários, essa interação acontece por pull requests. Se a permissão de colaborador é concedida, usuários podem editar o conteúdo diretamente, sem que necessariamente isso passe por uma revisão de pares.

**Não conceda privilégios de acesso de colaboradores a pesssoas em que você não confia**. Se você deseja manter edições diretas restritas mas quer conceder acesso de leitura ao conteúdo publicado, a única saída é ter um **repositório público**.

Caso queira usar um repositório do GitHub como ferramenta de gerenciamento de tickets, a única maneira de permitir a interação por issues sem conceder privilégios ao repositório também é deixá-lo público.

Não é possível bloquear pull requests em repositórios públicos. Prepare-se para a possibilidade deste repositório ser descoberto por spammers e trolls, especialmente na época de eventos como Hacktoberfest.

Há, no entanto, a possibilidade de [limitar as interações em um repositório temporariamente](https://docs.github.com/en/github/building-a-strong-community/limiting-interactions-in-your-repository) por três parâmetros:
* Interações de usuários recentes
* Interações de usuários que nunca contribuíram com o repositório
* Interações de usuários que não são listados como colaboradores

Você pode acessar as ferramentas de moderação clicando em **Settings** > **Moderation settings** no repositório que deseja controlar.
