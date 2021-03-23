# conversor-de-bases
Esse algoritmo recebe como entrada um valor em decimal e retorna o seu valor em outra base. Como ocorre esse processo?
-Através de uma função de callback "Converte()" que é acionada no click do botão "coverter", essa função recebe os valores que o usuário inseriu na box e o valor da base.
-Com esses valores em mãos, basta realizar o método das divisões consecutivas que se baseia em dividir o número pela base até que o resultado seja 0. 
O resto dessas divisões vão ser armazenados em uma Array("resultado").
-Porém na base hexadecimal(16) existe alguns casos específicos em que números são representados por letras, então foi criado uma condicional para
verificar se a base é a 16, que chama uma função "Hexadecimal" passando a Array como parâmetro para substituir tais números po letras.
-Por fim, a Array é invertida e concatenada sem as vírgulas entre os elementos para que fique mais apresentável ao usuário e é printada dentro da box "output"
