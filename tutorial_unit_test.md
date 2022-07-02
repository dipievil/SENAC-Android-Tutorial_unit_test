# Tutorial de Teste Unitário no Android

## Descrição

Para criar um teste unitário com JUnit no Android você só precia criar uma classe de testes baseada na sua classe de negócio (ou criar ou teste antes da classe com TDD).

## Classe de negócio de exemplo

Nossa função de exemplo realiza um cálculo de área multiplicando base vezes altura.

```kotlin
    fun CalculateArea(base:Double, altura: Double): Double{
        return base * height;
    }
```

Ao clicar com o botão o botão direito sobre o nome da função elecione "Generate..." ou digite *alt+insert*.

!(./img/tela1.png "Menu botão direito")
