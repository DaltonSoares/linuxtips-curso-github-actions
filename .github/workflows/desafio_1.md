DESAFIO 1:
    Crie no repositorio uma branch nova chamada desafio-um, ela tera todo o conteudo da branch main.
    Crie um workflow e ele NAO deve iniciar automaticamente (workflow_dispatch).
    Quando for executar manualmente deve ter um campo para colocar um INPUT que sera o nome e a tag de uma imagem do docker.
    Faca um docker pull da imagem.
    Proximo comando execute um docker images pra mostrar que a imagem disponivel.

    Tem um workflow compartilhado do proprio docker que e o scout-cli. Sera usado como um actions dentro do workflow para mostrar um relatorio das vulnerabilidades.

