# Factory Method (Método fábrica ou Construtor virtual)
- O Factory Method é um padrão criacional de projeto que fornece uma interface para criar objetos em uma superclasse, mas permite que as subclasses alterem o tipo de objetos que serão criados.
- O Factory Method define um método, que deve ser usado para criar objetos em vez da chamada direta ao construtor (operador new). As subclasses podem substituir esse método para alterar a classe de objetos que serão criados.
 
*Exemplo de Uso:*
- O padrão Factory Method é amplamente utilizado no código Java. É muito útil quando você precisa fornecer um alto nível de flexibilidade para seu código.

*Identificação:*
- Os métodos fábrica podem ser reconhecidos por métodos de criação, que criam objetos de classes concretas, mas os retornam como objetos de tipo ou interface abstrata.

# Produção de elementos da GUI de plataforma cruzada
- Neste exemplo, os botões desempenham uma função de produto e os diálogos atuam como criadores.
- Diferentes tipos de caixas de diálogo requerem seus próprios tipos de elementos. É por isso que criamos uma subclasse para cada tipo de diálogo e substituímos seus métodos fábrica.
- Agora, cada tipo de diálogo instanciará as classes de botão apropriadas. O diálogo base funciona com produtos usando sua interface comum, é por isso que seu código permanece funcional após todas as alterações.

