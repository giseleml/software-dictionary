# software-dictionary
A collection of short explanations of usual software development concepts


# MVC (Model-View-Controller)
Padrão de arquitetura de software que separa as camadas de uma aplicação em diferentes níveis. 
Este padrão define a divisão de uma aplicação em três componentes:
Modelo, Visão e Controle. 
Seu objetivo é facilitar a compreensão e manutenção do software. 
> Camadas:
- Visão: visual da aplicação, ou seja, as telas que serão exibidas para o usuário. Nessa camada apenas recursos visuais devem ser implementados, como janelas, botões e mensagens.
- Controle: intermediário entre Modelo e Visão; Realiza o processamento de dados informados pelo usuário, repassando-os para as outras camadas.
- Modelo: essência das regras de negócio, envolve classes do sistema e acesso aos dados. É responsaveil pela modelagem e acesso ao banco de dados.

# MVP (Minimum Viable Product)
Conjunto de testes primários para validar a viabilidade do projeto; Experimentações práticas que são desenvolvidas
levando o produto à um grupo seleto de clientes, não sendo o produto final ainda. Este produto possui o mínimo de 
recursos possíveis, desde que eles mantenham sua função de solucionar o problema para o qual foi criado; Não pode ser
funcionalidades soltas, juntas elas devem configurar o produto mesmo sendo protótipo.
Seu objetivo é conhecer na prática a reação do mercado, a compreensão do cliente sobre o produto e se ele de fato
soluciona o problema do seu consumidor.
