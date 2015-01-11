# build-github-pages-for-polymer-web-components

### Alteração feita na versão original encontrada nem Polymer/tools do Git Hub 

### Tive que mudar o protocolo de git para https

    # git clone git@github.com:$org/$repo.git --single-branch
    git clone https://github.com/$org/$repo.git --single-branch


##### Para publicar a documentação do componente e o respectivo DEMO execute um comando como no exemplo abaixo onde publico para o componente soma-tabs

    rm -rf soma-tabs ; tools/bin/gp.sh joao-parana soma-tabs


