<div align="center">
  
  # Guia de Aprendizado Dart 📚
  
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Rocket.png" alt="Rocket" width="100"/>
  
  <p align="center">
    <a href="https://dart.dev">
      <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/>
    </a>
    <a href="https://flutter.dev">
      <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
    </a>
    <a href="https://pub.dev">
      <img src="https://img.shields.io/badge/Pub.dev-Package%20Manager-blue?style=for-the-badge" alt="Pub.dev"/>
    </a>
    <img src="https://img.shields.io/badge/Versão-1.0.0-green?style=for-the-badge" alt="Version"/>
    <img src="https://img.shields.io/badge/Licença-MIT-red?style=for-the-badge" alt="License"/>
  </p>

  <p><em>Um guia completo e interativo para aprender Dart</em></p>

  <br/>
  
  <div align="center">
    <a href="#1-introdução-ao-dart">Começar</a> • 
    <a href="https://dart.dev/guides">Documentação</a> • 
    <a href="https://dart.dev/community">Comunidade</a> •
    <a href="#5-boas-práticas">Boas Práticas</a> •
    <a href="#7-recursos-adicionais">Recursos</a>
  </div>
</div>

<br/>

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Open%20Book.png" width="60"/><br>
        <strong>Aprenda</strong>
        <br/>
        Conceitos básicos e avançados
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" width="60"/><br>
        <strong>Pratique</strong>
        <br/>
        Exemplos e exercícios
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Puzzle%20Piece.png" width="60"/><br>
        <strong>Construa</strong>
        <br/>
        Projetos reais
      </td>
    </tr>
  </table>
</div>

<details>
<summary>📋 Tabela de Conteúdos</summary>

- [1. Introdução ao Dart](#1-introdução-ao-dart)
- [2. Configuração do Ambiente](#2-configuração-do-ambiente)
- [3. Conceitos Básicos](#3-conceitos-básicos)
- [4. Programação Orientada a Objetos](#4-programação-orientada-a-objetos)
- [5. Boas Práticas](#5-boas-práticas)
- [6. Testes](#6-testes)
- [7. Recursos Adicionais](#7-recursos-adicionais)

</details>

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" alt="Laptop" width="100"/>
</div>

### ✨ Características principais:

<details open>
<summary><b>Clique para expandir/recolher</b></summary>

- 🎯 Linguagem orientada a objetos
- ⚡ Tipagem forte e dinâmica
- 🔄 Hot Reload para desenvolvimento rápido
- 🌐 Multiplataforma (Web, Mobile, Desktop)
- 📦 Rico ecossistema de pacotes
- 🗑️ Garbage collection automático
- ⚙️ Compilação AOT e JIT
- 🔍 Null safety

</details>

## 1. Introdução ao Dart

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Rocket.png" alt="Rocket" width="25" height="25"/>
  <h3><strong>Vamos começar nossa jornada com Dart!</strong></h3>
</div>

> 🎯 Dart é uma linguagem de programação desenvolvida pelo Google, otimizada para criar aplicativos bonitos para qualquer plataforma!

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" alt="Laptop" width="100"/>
</div>

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/High%20Voltage.png" width="30"/><br>
        <strong>Rápido</strong>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Shield.png" width="30"/><br>
        <strong>Seguro</strong>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Flexed%20Biceps.png" width="30"/><br>
        <strong>Produtivo</strong>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Globe%20Showing%20Americas.png" width="30"/><br>
        <strong>Multiplataforma</strong>
      </td>
    </tr>
  </table>
</div>

## 2. Configuração do Ambiente

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" alt="Gear" width="50"/>
</div>

### Instalação do SDK

<details>
<summary>🖥️ Escolha seu sistema operacional</summary>

#### Windows
```bash
choco install dart-sdk
```

#### macOS
```bash
brew install dart
```

#### Linux
```bash
sudo apt-get install dart
```

</details>

### 🛠️ IDEs Recomendadas

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Desktop%20Computer.png" width="30"/><br>
        VS Code + Dart
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Mobile%20Phone.png" width="30"/><br>
        Android Studio
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Light%20Bulb.png" width="30"/><br>
        IntelliJ IDEA
      </td>
    </tr>
  </table>
</div>

## 3. Conceitos Básicos

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Books.png" alt="Books" width="50"/>
</div>

### 📝 Variáveis e Tipos

<details open>
<summary><b>Tipos Básicos e Declarações</b></summary>

```dart
// Declaração de variáveis
var nome = 'João';           // Inferência de tipo
String sobrenome = 'Silva';  // Tipo explícito
dynamic valor = 42;          // Tipo dinâmico
final idade = 25;            // Valor imutável
const PI = 3.14159;          // Constante em tempo de compilação
late String descricao;       // Inicialização tardia

// Tipos básicos
int numero = 42;
double decimal = 3.14;
String texto = 'Olá';
bool verdadeiro = true;
List<int> numeros = [1, 2, 3];
Set<String> conjunto = {'a', 'b', 'c'};
Map<String, dynamic> mapa = {
  'nome': 'João',
  'idade': 25
};

// Null safety
String? podeSerNulo;        // Pode ser nulo
String naoPodeSerNulo = ''; // Não pode ser nulo
```

</details>

### 📏 Estruturas de Controle

<details>
<summary><b>Controle de Fluxo</b></summary>

```dart
// If-else
if (idade >= 18) {
  print('Maior de idade');
} else {
  print('Menor de idade');
}

// For
for (var i = 0; i < 5; i++) {
  print(i);
}

// While
while (condicao) {
  // código
}

// Switch
switch (valor) {
  case 1:
    print('Um');
    break;
  default:
    print('Outro');
}
```

</details>

## 4. Programação Orientada a Objetos

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Puzzle%20Piece.png" alt="POO" width="50"/>
</div>

<details open>
<summary><b>Classes e Objetos</b></summary>

```dart
// Classes abstratas
abstract class Animal {
  void fazerSom();
}

// Herança
class Cachorro extends Animal {
  @override
  void fazerSom() {
    print('Au au!');
  }
}

// Interfaces
class Voador {
  void voar() {}
}

// Mixins
mixin Nadador {
  void nadar() {
    print('Nadando...');
  }
}

// Classe com herança e mixin
class Pato extends Animal with Nadador implements Voador {
  @override
  void fazerSom() {
    print('Quack!');
  }
  
  @override
  void voar() {
    print('Voando...');
  }
}

// Construtor factory (Singleton)
class Logger {
  static final Logger _instance = Logger._internal();
  
  factory Logger() {
    return _instance;
  }
  
  Logger._internal();
}
```

</details>

## 5. Boas Práticas

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Light%20Bulb.png" alt="Light Bulb" width="60"/>
  <h3>Código limpo, resultados extraordinários!</h3>
</div>

### 📏 Convenções de Código

> 💡 Siga estas convenções para manter seu código limpo e legível

- `camelCase` para nomes de variáveis e funções
- `PascalCase` para nomes de classes
- `snake_case` para nomes de arquivos
- `_` (underscore) para identificadores privados

### 🛡️ Null Safety

<details>
<summary><b>Exemplos de Null Safety</b></summary>

```dart
// Boas práticas com null safety
String? nullableString;
String nonNullableString = 'valor';

// Operador de coalescência nula
String result = nullableString ?? 'valor padrão';

// Operador de acesso seguro
String? upper = nullableString?.toUpperCase();

// Assertion operator
String value = nullableString!; // Use com cautela!
```

</details>

### 📦 Gerenciamento de Dependências

<details>
<summary><b>Configuração do pubspec.yaml</b></summary>

```yaml
name: meu_projeto
description: Descrição do projeto
version: 1.0.0

dependencies:
  http: ^0.13.0
  path: ^1.8.0

dev_dependencies:
  test: ^1.16.0
```

</details>

## 6. Testes

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Microscope.png" alt="Test" width="50"/>
</div>

<details>
<summary><b>Exemplos de Testes</b></summary>

```dart
import 'package:test/test.dart';

void main() {
  test('Soma dois números', () {
    expect(soma(2, 2), equals(4));
  });
  
  group('Testes de string', () {
    test('Converte para maiúsculo', () {
      expect('hello'.toUpperCase(), equals('HELLO'));
    });
    
    test('Verifica comprimento', () {
      expect('dart'.length, equals(4));
    });
  });
}
```

</details>

## 7. Recursos Adicionais

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Books.png" alt="Resources" width="60"/>
  <h3>Expanda seus horizontes!</h3>
</div>

### 📚 Documentação e Ferramentas

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://dart.dev/tools/dart-devtools">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="40"/><br>
          <strong>DevTools</strong>
        </a>
      </td>
      <td align="center">
        <a href="https://pub.dev">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Package.png" width="40"/><br>
          <strong>Pub.dev</strong>
        </a>
      </td>
      <td align="center">
        <a href="https://dart.dev/codelabs/dart-cheatsheet">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Scroll.png" width="40"/><br>
          <strong>Cheatsheet</strong>
        </a>
      </td>
    </tr>
  </table>
</div>

### 👥 Comunidade

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://discord.gg/Qt6DgfS">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Speech%20Balloon.png" width="40"/><br>
          <strong>Discord</strong>
        </a>
      </td>
      <td align="center">
        <a href="https://stackoverflow.com/questions/tagged/dart">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Stack%20of%20Books.png" width="40"/><br>
          <strong>Stack Overflow</strong>
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 💪 Como Contribuir

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Handshake.png" alt="Handshake" width="60"/>
  <h3>Junte-se a nós!</h3>
</div>

1. 🍴 Faça um fork do projeto
2. 🔧 Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push para a branch (`git push origin feature/AmazingFeature`)
5. 🔄 Abra um Pull Request

---

<div align="center">
  <br/>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" alt="Check" width="30"/>
  <h3>Continue explorando e praticando!</h3>
  
  <a href="https://dart.dev/guides">
    <img src="https://img.shields.io/badge/Documentação%20Oficial-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Docs"/>
  </a>
  
  <br/><br/>
  
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Star.png" alt="Star" width="24"/>
  Se este guia foi útil, considere dar uma estrela!
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Star.png" alt="Star" width="24"/>

  <br/><br/>
  
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Heart.png" alt="Heart" width="20"/>
  <sub>
    Feito com amor pela comunidade Dart
    <br/>
    <a href="https://github.com/dart-lang">GitHub</a> •
    <a href="https://twitter.com/dart_lang">Twitter</a> •
    <a href="https://discord.gg/Qt6DgfS">Discord</a>
  </sub>
  
  <br/><br/>
  <sub>
    <strong>© 2024 Dart Community</strong><br/>
    Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
  </sub>
</div>
