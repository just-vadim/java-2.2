# Отчёт о тестировании программы начисления бонуса новым клиентам

## Краткое описание

04.08.2020 - было проведено функцональное тестирование программы начисления бонуса новым клиентам.

На тестирование затрачено: 20m

В результате тестирования выявлены следующие дефекты:
* [Некорректный результат работы программы начисления бонуса новым клиентам #1](https://github.com/just-vadim/java-2.2/issues/1)

## Описание процесса тестирования

Код программы:
```java
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

Тестирование производилось в следующем окружении:
* ОС: Windows 10 Pro 1909 18363.959 x64
* Java: openjdk version "11.0.8" 2020-07-14;
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10);
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* IDE: IntelliJ IDEA Community Edition 2020.2
