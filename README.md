Este repositório contém um projeto para simular um circuito e código no TinkerCAD que faz o LED interno de um Arduino piscar a cada 1000 milissegundos (1 segundo). O código utiliza a função digitalWrite para alternar o estado do LED entre ligado e desligado, com um intervalo de 1 segundo entre cada mudança. Este exemplo é ideal para iniciantes que desejam aprender a programar o Arduino e entender os conceitos básicos de controle de hardware com software.


<div align="center">
    <img src="assets/ledinterno1.png" alt="Imagem do Arduino 1" width="1000"/>
    <br>
    <sup>Imagem do Arduino 1 - Fonte: TinkerCAD</sup>
</div>

<div align="center">
    <img src="assets/ledinterno2.jpg" alt="Imagem do Arduino 2" width="1000"/>
    <br>
    <sup>Imagem do Arduino 2 - Fonte: TinkerCAD</sup>
</div>

``` C
// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Espera por 1000 milissegundos (s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Espera por 1000 milissegundos (s)
}
```

<div align="center">
    <img src="assets/codigo.jpg" alt="Imagem do Código" width="1000"/>
    <br>
    <sup>Imagem do Código- Fonte: TinkerCAD</sup>
</div>