
# Studying Git

### Git fetch 
Baixa os HEADs com nomes ou tags de um ou mais repositórios (caso você tenha outro remote além do ```origin``` configurado), junto com os objetos necessários para completá-los. Basicamente ele atualiza as referências locais com relações às remotas, mas não faz o merge com o branch local.

### Git pull
Incorpora mudanças de um repositório remoto para o branch local. É equivalente a ```git fetch``` seguido de ```git merge FETCH_HEAD```

De modo simplório, o ```git fetch``` buscas as diferenças em relação ao ramo atual, mas não altera nada nesse branch. Já ```git pull``` faz o ```git fetch``` e faz o merge das diferenças.
