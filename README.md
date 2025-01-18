---

# TestingLibrary

Este repositório contém uma biblioteca Android de exemplo, criada com o objetivo de estudar e praticar a criação e publicação de bibliotecas em repositórios como o JitPack.

## Objetivo

O projeto tem como objetivo demonstrar o processo de desenvolvimento, configuração e publicação de bibliotecas Android, e é uma referência para quem deseja entender o fluxo de criação de uma biblioteca compartilhável via JitPack.

## Instalação

Para utilizar a biblioteca em seu projeto Android, adicione o repositório JitPack e a dependência no arquivo `build.gradle` do seu projeto:

1. Adicione o repositório JitPack no `sett.gradle` do projeto:
   ```kotlin
   repositories {
       maven { url 'https://jitpack.io' }
   }
   ```

2. Adicione a dependência no `build.gradle` do módulo onde deseja usar a biblioteca:
   ```kotlin
   dependencies {
       implementation 'com.github.MarceloLuiz12:TestingLibrary:1:0'
   }
   ```

## Exemplo de Uso

Exemplo de como usar a biblioteca:

```kotlin
import com.example.mlplibrary.Point
import com.example.mlplibrary.calculateDistanceTo

Point(1.0, 2.0).calculateDistanceTo(Point(3.0, 4.0))
```

---
