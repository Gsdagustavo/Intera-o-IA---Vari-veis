• Quais as boas práticas em dart declarando variáveis? 
R: 
Aqui estão as boas práticas ao declarar variáveis em Dart:

Escolha o tipo de variável adequado – Use var para valores mutáveis, final para valores que não mudam após a atribuição e const para constantes conhecidas em tempo de compilação.

Declare tipos explicitamente quando necessário – Embora Dart tenha inferência de tipo, especificar o tipo pode melhorar a clareza e evitar erros inesperados.

Use late apenas quando necessário – Essa palavra-chave deve ser usada apenas quando a variável será inicializada posteriormente, mas antes do primeiro uso.

Prefira const a final quando possível – Variáveis const são alocadas em tempo de compilação, o que melhora a performance em comparação com final, que é inicializado em tempo de execução.

Dê nomes descritivos às variáveis – Escolha nomes claros e significativos para facilitar a leitura e manutenção do código.

Evite o uso desnecessário de dynamic – O tipo dynamic desativa a verificação de tipo e pode levar a erros inesperados, então só deve ser usado quando realmente necessário.

Use ? para valores opcionais – Se uma variável pode ser nula, indique isso explicitamente usando ? para aproveitar os recursos de null safety do Dart.

Evite criar variáveis desnecessárias – Sempre que possível, elimine variáveis que não agregam valor ao código e substitua por expressões diretas para melhorar a eficiência.

Seguir essas boas práticas garante um código mais limpo, eficiente e seguro.
