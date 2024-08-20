# Challenge Decodificador de Texto - ONE | Alura
O projeto envolve a criação de um decodificador de texto,  desenvolvido como parte de um desafio do programa Oracle Next Education em colaboração com a Alura. O projeto visa criar uma aplicação capaz de criptografar e descriptografar mensagens de texto, oferecendo uma oportunidade prática para aplicar conhecimentos técnicos em uma situação próxima à realidade profissional.

* Criptografia por Substituição de Vogais

  * Letra "e" é substituída por "enter"
  * Letra "i" é substituída por "imes"
  * Letra "a" é substituída por "ai"
  * Letra "o" é substituída por "ober"
  * Letra "u" é substituída por "ufat"
 
* Botões Funcionais
  * <b>Criptografar</b>: Criptografa o texto inserido no campo de entrada. Após a criptografia, o texto é transferido para o campo de saída.
  * <b>Descriptografar</b>: Descriptografa o texto inserido no campo de entrada. Após a descriptografia, o texto é transferido para o campo de saída.
  * <b>Copiar</b>: Copia o conteúdo do campo de saída para a área de transferência.

 
# 🛠️ Ferramentas Utilizadas
* JavaScript: Utilizado para implementar a lógica de criptografia e descriptografia, manipulando e validando o texto inserido pelo usuário.

* HTML: Estrutura a interface do usuário, incluindo os campos de entrada e saída de texto, bem como os botões de ação.

* CSS: Responsável pela estilização da aplicação, garantindo uma interface visualmente agradável e responsiva.

* Git: Utilizado para controle de versão, permitindo acompanhar o desenvolvimento do projeto e gerenciar alterações no código.
* Visual Studio Code: Editor de código escolhido para escrever e depurar o código-fonte, aproveitando suas funcionalidades como extensão de plugins e integração com Git.

# 💡Funcionalidade
O codificador de texto é projetado para trabalhar exclusivamente com letras minúsculas, números e espaços, excluindo acentos e caracteres especiais.

* Filtragem de Entrada: O sistema permite apenas letras minúsculas, números e espaços. Qualquer caractere diferente, como acentos e símbolos especiais, é removido automaticamente.

* Remoção de Acentos: Quando o texto é digitado, ele é normalizado para decompor caracteres acentuados. Por exemplo, "é" é transformado em "e" sem acento. Em seguida, os acentos são removidos, resultando apenas nas letras básicas.

* Remoção de Caracteres Especiais: Após a remoção dos acentos, todos os caracteres que não sejam letras, números ou espaços são eliminados. Isso remove pontuações e símbolos não permitidos.

* Atualização do Campo de Texto: O texto limpo, agora livre de acentos e caracteres especiais, é exibido no campo de texto. Apenas letras minúsculas, números e espaços são permitidos.

* Criptografia: Após a limpeza e normalização do texto, ele é criptografado usando um algoritmo específico. O texto criptografado é então exibido no campo apropriado. A criptografia garante que o texto original seja transformado em uma forma segura e ilegível. 

* Colar e Descriptografar: Usuários podem colar texto no campo que já foi criptografado anteriormente. O sistema aplica as mesmas regras de filtragem para garantir que o texto colado esteja em conformidade com os requisitos, permitindo uma descriptografia correta.

# 📲 Acesso à Aplicação

* Clique no seguinte link da aplicação para abrir a aplicação no seu navegador: <a href= "colocar meu link >Challenge Decodificador</a>

* Inserção de Texto: No campo de entrada, digite o texto que deseja criptografar ou descriptografar. Certifique-se de usar apenas letras minúsculas, números e espaços, pois caracteres especiais e acentos serão removidos automaticamente.
  
* Criptografar Texto: Clique no botão Encrypt (Criptografar). O texto inserido será criptografado e o resultado será exibido no campo de saída. 

* Descriptografar Texto: Se você tiver um texto criptografado, cole-o no campo de entrada e clique no botão Decrypt (Descriptografar). O texto será descriptografado e o resultado será mostrado no campo de saída. 

* Copiar Texto: Após a criptografia ou descriptografia, clique no botão Copy (Copiar) para copiar o texto do campo de saída para a área de transferência. 

* Verificação e Ajustes: Verifique o texto no campo de saída. Caso o texto não esteja no formato esperado, ajuste o texto no campo de entrada e repita o processo de criptografia ou descriptografia conforme necessário.
# Observações

* Nessa primeira experiência confesso que o JavaScript foi a minha maior dificuldade.

* Trabalhar com o CSS e o HTML é bem agradável, excetuando a parte de responsividade.# decodificador_texto
