# tortoise Scripts

Para utilizar a gama de Scripts nesse repositório existem algumas considerações a serem feitas.

** você precisa utilizar o instalador tegg
** você precisa de um diretório chamado Scripts, e dentro dele três diretórios (src, symlinks, changelog)

por enquanto o tegg não gera essa estrutura automaticamente, mas temos esse objetivo.

o diretório src/ é onde ficarão as pastas com os seus programas e os seus devidos arquivos.

o diretório symlinks/ irá guardar os links simbólicos, eles serão carregados no Path para que você não precise utilizar ./nome_do_script.sh e possa chamar cada script em qualquer lugar do sistema.

o diretório changelog serve apenas para guardar os arquivos de changelog em um único lugar, porém isso é opcional e serve apenas para o acesso e leitura mais fácil desses arquivos.

quando criar esses diretórios, você precisa gerar os links simbólicos e carregar a pasta symlinks no Path.

export "PATH=$PATH:$HOME/scripts/symlinks"

após isso basta chamar o script que deseja pelo nome em qualquer lugar e ele estará pronto.