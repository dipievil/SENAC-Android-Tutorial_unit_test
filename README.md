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

Ao clicar com o botão o botão direito sobre o nome da função e selecione "Generate..." ou digite *alt+insert*.

![Menu Botão Direito](/img/tela1.png)

No menu Generate, selecione *Test...*. Dessa forma uma janela abrirá com as opções de geração de modelos de métodos de teste.

![Create Test](/img/tela2.png)

Automaticamente será selecionado o JUnit5. Em *Class name* no nome da classe defina como será chamada a classe de teste. O *Destination package* deve ser o mesmo da classe de negócio.

Em *Generate test methods* for selecione o método que deseja testar.

![Choose Destination Directory](/img/tela3.png)

Na janela Choose Destination Directory você define a pasta onde será salvo a classe de teste. Em seguida a classe de teste será gerado pelo Android Studio.

```Kotlin
internal class GeoFormTest {

    @org.junit.jupiter.api.Test
    fun calculateArea() {
    }
}
```

Caso não tenha as referência ao JUnit incluida utilizando a *lâmpada vermelha*.

![Add reference menu](/img/tela4.png)

