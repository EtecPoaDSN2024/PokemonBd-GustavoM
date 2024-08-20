# Projetando Pokemon BD - I DSN

![pokemon](https://t.ctcdn.com.br/IZbPIPMfS8TzOqMQJthZUo4cTMg=/1024x576/smart/i515431.jpeg)

Exemplo de 1 pokemon : https://wiki.otpokemon.com/index.php/Abra

Primeiramente, cada Pokémon deve ser identificado por um número único chamado ID_Pokemon, e cada um deve ter um nome exclusivo. Além disso, é necessário registrar o[ tipo primário](https://pokemon.fandom.com/pt-br/wiki/Tipo) do Pokémon, bem como suas [habilidades](https://wiki.otpokemon.com/index.php/Habilidades_dos_Pokemon) especial. O nível de evolução do Pokémon deve ser registrado, assim como a altura e o peso do Pokémon.

Além disso, é importante guardar os [tipos](https://pokemon.fandom.com/pt-br/wiki/Tipo) de Pokémon. Cada tipo deve ter um identificador único chamado ID_Tipo, um nome e uma descrição que explica as características do tipo.

Para as  [habilidades](https://wiki.otpokemon.com/index.php/Habilidades_dos_Pokemon), cada uma deve ter um identificador único chamado ID_Habilidade, um nome e uma descrição detalhada.

Os treinadores devem ser identificados por um número único chamado ID_Treinador e devem ter um nome, idade e endereço completo.

O banco de dados deve permitir registrar quais Pokémon pertencem a quais treinadores. Para isso, deve-se associar o ID_Treinador com o ID_Pokemon e registrar a data em que o Pokémon foi capturado pelo treinador. Um Pokémon pode ter apenas 1 treinador.

Cada batalha deve ser registrada com um identificador único denominado ID_Batalha, e deve incluir a data da batalha. A batalha deve registrar o ID_Treinador e o ID_Pokemon usados por cada treinador. O resultado da batalha deve ser indicado por um texto que especifica o vencedor ou se houve um empate.
