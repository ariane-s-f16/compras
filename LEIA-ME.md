# Compras

📋 **Sobre o Projeto**  
O **Compras** é um aplicativo multiplataforma criado com .NET MAUI (Multi-platform App UI), permitindo que os usuários organizem suas listas de compras de maneira prática e eficiente. Ele é compatível com dispositivos Android, iOS, Windows e macOS, utilizando uma única base de código.

🚀 **Tecnologias Empregadas**  
- **Linguagem Principal:** C# (.NET 7.0)  
- **Framework:** .NET MAUI  
- **Banco de Dados:** SQLite  
- **Arquitetura:** MVVM (Model-View-ViewModel)  

⚙️ **Principais Funcionalidades**  
- Criaar e gerenciar várias listas de compras  
- Adição, edição e exclusão de itens  
- Marcação de itens como comprados  
- Cálculo automático do valor total da compra  
- Interface amigável e responsiva  
- Funcionamento offline

📱 **Plataformas Suportadas**  
- **Android:** 7.0 ou superior  
- **iOS:** 14.0 ou superior  
- **Windows:** 10/11  
- **macOS:** 11.0 ou superior  


### Estrutura do Projeto

A estrutura do projeto está organizada da seguinte maneira:

```
MauiAppMinhasCompras/
├── Models/              # Classes de modelo de dados
├── ViewModels/          # Classes de ViewModel (MVVM)
├── Views/               # Páginas XAML da interface
├── Services/            # Serviços de manipulação de dados
├── Resources/           # Recursos gráficos e de estilo
└── Platforms/           # Código específico para cada plataforma
```

- **Models**: Contém as classes que representam os dados da aplicação, como `Item` e `ListaDeCompras`.
- **ViewModels**: São responsáveis pela lógica de negócios e pela interação com a interface do usuário.
- **Views**: Páginas XAML que definem o layout e a interface do aplicativo.
- **Services**: Contém os serviços para acessar, salvar e excluir dados das listas de compras.
- **Resources**: Armazena imagens, ícones e estilos de layout.
- **Platforms**: Código específico para cada plataforma (Android, iOS, Windows, macOS).

---
Detalhes da Implementação
O aplicativo implementa o padrão MVVM (Model-View-ViewModel) para o desenvolvimento de software, proporcionando uma estrutura organizada que promove a manutenibilidade, a reutilização de código e a testabilidade. O SQLite é utilizado como banco de dados local para armazenar as listas de compras e seus itens.

A interface é construída com XAML, aproveitando os recursos do .NET MAUI para criar uma experiência de usuário consistente em todas as plataformas suportadas.


### Licença

Este projeto é licenciado sob a **Licença MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

### Agradecimentos

Agradecemos aos colaboradores e à comunidade .NET MAUI por todo o apoio e contribuição para a realização deste projeto.

---

Caso tenha dúvidas ou sugestões, sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**!
