## Diagrama UML para criar as classes do IPhone-Dio.

```mermaid
classDiagram
    class IPhoneDio {
    }

    class ReprodutorMusical {
        +void tocar()
        +void pausar()
        +void selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +void ligar(String numero)
        +void atender()
        +void iniciarCorreioVoz()
    }

    class NavegadorNaInternet {
        +void exibirPagina(String url)
        +void adicionarNovaAba()
        +void atualizarPagina()
    }

    IPhoneDio <|-- ReprodutorMusical
    IPhoneDio <|-- AparelhoTelefonico
    IPhoneDio <|-- NavegadorNaInternet
```
