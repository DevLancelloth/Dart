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
- [6. Testes e Debugging](#6-testes-e-debugging)
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
  <h3>Fundamentos da Linguagem</h3>
</div>

### 🎯 Playground Interativo

> Experimente Dart diretamente no seu navegador usando o [DartPad](https://dartpad.dev/)!

<details open>
<summary><b>👨‍💻 Seu Primeiro Programa</b></summary>

```dart
void main() {
  print('Olá, Dart! 🎯');
  
  // Experimente mudar o texto acima e clique em Run!
}
```

</details>

### 📚 Tipos de Dados

<div align="center">
  <table>
    <tr>
      <th align="center">Tipo</th>
      <th align="center">Exemplo</th>
      <th align="center">Descrição</th>
    </tr>
    <tr>
      <td align="center"><code>int</code></td>
      <td align="center"><code>42</code></td>
      <td>Números inteiros</td>
    </tr>
    <tr>
      <td align="center"><code>double</code></td>
      <td align="center"><code>3.14</code></td>
      <td>Números decimais</td>
    </tr>
    <tr>
      <td align="center"><code>String</code></td>
      <td align="center"><code>'texto'</code></td>
      <td>Textos</td>
    </tr>
    <tr>
      <td align="center"><code>bool</code></td>
      <td align="center"><code>true</code></td>
      <td>Valores lógicos</td>
    </tr>
    <tr>
      <td align="center"><code>List</code></td>
      <td align="center"><code>[1, 2, 3]</code></td>
      <td>Listas ordenadas</td>
    </tr>
    <tr>
      <td align="center"><code>Map</code></td>
      <td align="center"><code>{'chave': valor}</code></td>
      <td>Pares chave-valor</td>
    </tr>
  </table>
</div>

### 🔥 Recursos Modernos

<details>
<summary><b>Null Safety</b></summary>

```dart
// Variável que pode ser nula
String? nome;

// Variável que não pode ser nula
String nomeCompleto = 'João Silva';

// Operador de coalescência nula
String resultado = nome ?? 'Nome padrão';

// Operador de acesso seguro
int? tamanho = nome?.length;
```

#### Por que usar Null Safety?
- ✅ Previne erros em tempo de execução
- 🔍 Código mais seguro e previsível
- 🚀 Melhor performance
- 💡 Detecção de erros em tempo de compilação

</details>

<details>
<summary><b>Async/Await</b></summary>

```dart
Future<String> buscarDados() async {
  // Simulando uma requisição
  await Future.delayed(Duration(seconds: 2));
  return 'Dados carregados!';
}

void main() async {
  print('Carregando...');
  String resultado = await buscarDados();
  print(resultado);
}
```

#### Casos de Uso
- 🌐 Requisições HTTP
- 📁 Operações com arquivos
- 🔄 Processamento em background
- 📱 Animações e UI

</details>

### 🎨 Exemplos Práticos

<details>
<summary><b>Manipulação de Listas</b></summary>

```dart
void main() {
  // Criando uma lista
  var numeros = [1, 2, 3, 4, 5];
  
  // Map - transformando dados
  var dobro = numeros.map((n) => n * 2);
  
  // Filter - filtrando dados
  var pares = numeros.where((n) => n % 2 == 0);
  
  // Reduce - reduzindo a um valor
  var soma = numeros.reduce((a, b) => a + b);
  
  print('Original: $numeros');
  print('Dobro: $dobro');
  print('Pares: $pares');
  print('Soma: $soma');
}
```

</details>

<details>
<summary><b>Programação Funcional</b></summary>

```dart
// High-order functions
void executar(int Function(int) funcao, int valor) {
  print(funcao(valor));
}

// Arrow functions
var quadrado = (int x) => x * x;
var cubo = (int x) => x * x * x;

void main() {
  executar(quadrado, 5); // 25
  executar(cubo, 3);    // 27
}
```

</details>

### 🛠️ Ferramentas de Desenvolvimento

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://code.visualstudio.com/">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Desktop%20Computer.png" width="40"/><br>
          <strong>VS Code</strong>
          <br/>
          <sub>Editor Recomendado</sub>
        </a>
      </td>
      <td align="center">
        <a href="https://dart.dev/tools/dart-devtools">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="40"/><br>
          <strong>DevTools</strong>
          <br/>
          <sub>Debugging & Profiling</sub>
        </a>
      </td>
      <td align="center">
        <a href="https://pub.dev">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Package.png" width="40"/><br>
          <strong>Pub.dev</strong>
          <br/>
          <sub>Gerenciador de Pacotes</sub>
        </a>
      </td>
    </tr>
  </table>
</div>

### 📱 Frameworks e Bibliotecas Populares

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://flutter.dev">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Mobile%20Phone.png" width="40"/><br>
          <strong>Flutter</strong>
          <br/>
          <sub>UI Framework</sub>
        </a>
      </td>
      <td align="center">
        <a href="https://aqueduct.io">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Server.png" width="40"/><br>
          <strong>Aqueduct</strong>
          <br/>
          <sub>Server-side Framework</sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/dart-lang/angular">
          <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Globe%20with%20Meridians.png" width="40"/><br>
          <strong>AngularDart</strong>
          <br/>
          <sub>Web Framework</sub>
        </a>
      </td>
    </tr>
  </table>
</div>

## 4. Programação Orientada a Objetos

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Puzzle%20Piece.png" alt="POO" width="50"/>
  <h3>Construindo com Classes e Objetos</h3>
</div>

### 🏗️ Conceitos Fundamentais

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Building%20Construction.png" width="40"/><br>
        <strong>Classes</strong>
        <br/>
        <sub>Modelos para objetos</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Link.png" width="40"/><br>
        <strong>Herança</strong>
        <br/>
        <sub>Reutilização de código</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Shield.png" width="40"/><br>
        <strong>Encapsulamento</strong>
        <br/>
        <sub>Proteção de dados</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Magic%20Wand.png" width="40"/><br>
        <strong>Polimorfismo</strong>
        <br/>
        <sub>Múltiplas formas</sub>
      </td>
    </tr>
  </table>
</div>

### 📚 Exemplos Práticos

<details>
<summary><b>🏭 Padrão Factory</b></summary>

```dart
abstract class Animal {
  void fazerSom();
  
  // Factory Constructor
  factory Animal.criar(String tipo) {
    switch (tipo) {
      case 'cachorro':
        return Cachorro();
      case 'gato':
        return Gato();
      default:
        throw ArgumentError('Tipo de animal não suportado');
    }
  }
}

class Cachorro implements Animal {
  @override
  void fazerSom() => print('Au au! 🐕');
}

class Gato implements Animal {
  @override
  void fazerSom() => print('Miau! 🐱');
}

void main() {
  final cachorro = Animal.criar('cachorro');
  final gato = Animal.criar('gato');
  
  cachorro.fazerSom(); // Au au! 🐕
  gato.fazerSom();     // Miau! 🐱
}
```

</details>

<details>
<summary><b>🎯 Padrão Singleton</b></summary>

```dart
class ConfiguracaoApp {
  // Instância única
  static final ConfiguracaoApp _instance = ConfiguracaoApp._internal();
  
  // Construtor factory
  factory ConfiguracaoApp() {
    return _instance;
  }
  
  // Construtor privado
  ConfiguracaoApp._internal();
  
  // Configurações
  String tema = 'claro';
  String idioma = 'pt_BR';
  
  void alterarTema(String novoTema) {
    tema = novoTema;
    print('Tema alterado para: $tema');
  }
}

void main() {
  final config1 = ConfiguracaoApp();
  final config2 = ConfiguracaoApp();
  
  print(identical(config1, config2)); // true - mesma instância!
  
  config1.alterarTema('escuro');
  print(config2.tema); // 'escuro' - compartilham estado
}
```

</details>

<details>
<summary><b>🔄 Padrão Observer</b></summary>

```dart
// Interface para observadores
abstract class Observer {
  void update(String mensagem);
}

// Classe observável
class NotificadorEventos {
  final List<Observer> _observadores = [];
  
  void adicionarObservador(Observer observador) {
    _observadores.add(observador);
  }
  
  void removerObservador(Observer observador) {
    _observadores.remove(observador);
  }
  
  void notificarTodos(String mensagem) {
    for (var observador in _observadores) {
      observador.update(mensagem);
    }
  }
}

// Implementações de observadores
class EmailObserver implements Observer {
  @override
  void update(String mensagem) {
    print('📧 Email enviado: $mensagem');
  }
}

class SMSObserver implements Observer {
  @override
  void update(String mensagem) {
    print('📱 SMS enviado: $mensagem');
  }
}

void main() {
  final notificador = NotificadorEventos();
  
  final emailObs = EmailObserver();
  final smsObs = SMSObserver();
  
  notificador.adicionarObservador(emailObs);
  notificador.adicionarObservador(smsObs);
  
  notificador.notificarTodos('Nova atualização disponível!');
}
```

</details>

### 🎨 Design Patterns em Dart

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Factory.png" width="40"/><br>
        <strong>Criacionais</strong>
        <br/>
        <sub>Factory, Builder, Singleton</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" width="40"/><br>
        <strong>Estruturais</strong>
        <br/>
        <sub>Adapter, Bridge, Composite</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Crystal%20Ball.png" width="40"/><br>
        <strong>Comportamentais</strong>
        <br/>
        <sub>Observer, Strategy, State</sub>
      </td>
    </tr>
  </table>
</div>

### 🚀 Melhores Práticas

> 💡 Dicas para escrever código orientado a objetos de qualidade

1. **SOLID Principles**
   - Single Responsibility (Responsabilidade Única)
   - Open/Closed (Aberto/Fechado)
   - Liskov Substitution (Substituição de Liskov)
   - Interface Segregation (Segregação de Interface)
   - Dependency Inversion (Inversão de Dependência)

2. **Clean Code**
   - Nomes significativos
   - Funções pequenas e focadas
   - Comentários apenas quando necessário
   - Formatação consistente
   - Tratamento de erros adequado

3. **Code Review Checklist**
   - ✅ Código segue padrões SOLID
   - ✅ Testes unitários implementados
   - ✅ Documentação atualizada
   - ✅ Tratamento de erros adequado
   - ✅ Performance otimizada

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

## 6. Testes e Debugging

<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Microscope.png" alt="Test" width="50"/>
  <h3>Qualidade e Confiabilidade</h3>
</div>

### 🧪 Tipos de Testes

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Test%20Tube.png" width="40"/><br>
        <strong>Unitários</strong>
        <br/>
        <sub>Testando componentes isolados</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Puzzle%20Piece.png" width="40"/><br>
        <strong>Integração</strong>
        <br/>
        <sub>Testando interações</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Globe%20with%20Meridians.png" width="40"/><br>
        <strong>E2E</strong>
        <br/>
        <sub>Testando o sistema completo</sub>
      </td>
    </tr>
  </table>
</div>

### 📝 Exemplos de Testes

<details>
<summary><b>✨ Testes Unitários</b></summary>

```dart
import 'package:test/test.dart';

class Calculadora {
  int somar(int a, int b) => a + b;
  int subtrair(int a, int b) => a - b;
  int multiplicar(int a, int b) => a * b;
  double dividir(int a, int b) {
    if (b == 0) throw ArgumentError('Divisão por zero!');
    return a / b;
  }
}

void main() {
  group('Calculadora', () {
    late Calculadora calc;
    
    setUp(() {
      calc = Calculadora();
    });
    
    test('soma dois números corretamente', () {
      expect(calc.somar(2, 2), equals(4));
      expect(calc.somar(-1, 1), equals(0));
      expect(calc.somar(0, 0), equals(0));
    });
    
    test('subtrai dois números corretamente', () {
      expect(calc.subtrair(5, 3), equals(2));
      expect(calc.subtrair(2, 4), equals(-2));
    });
    
    test('multiplica dois números corretamente', () {
      expect(calc.multiplicar(3, 4), equals(12));
      expect(calc.multiplicar(-2, 3), equals(-6));
    });
    
    test('divide dois números corretamente', () {
      expect(calc.dividir(6, 2), equals(3.0));
      expect(calc.dividir(5, 2), equals(2.5));
    });
    
    test('lança erro ao dividir por zero', () {
      expect(() => calc.dividir(5, 0), throwsArgumentError);
    });
  });
}
```

</details>

<details>
<summary><b>🔄 Testes de Integração</b></summary>

```dart
import 'package:test/test.dart';

class Usuario {
  final String nome;
  final int idade;
  
  Usuario(this.nome, this.idade);
}

class BancoDados {
  Future<void> salvar(Usuario usuario) async {
    // Simula salvamento no banco
    await Future.delayed(Duration(milliseconds: 100));
  }
  
  Future<Usuario> buscar(String nome) async {
    // Simula busca no banco
    await Future.delayed(Duration(milliseconds: 100));
    return Usuario(nome, 25);
  }
}

class ServicoUsuario {
  final BancoDados db;
  
  ServicoUsuario(this.db);
  
  Future<Usuario> criarUsuario(String nome, int idade) async {
    final usuario = Usuario(nome, idade);
    await db.salvar(usuario);
    return usuario;
  }
}

void main() {
  group('ServicoUsuario', () {
    late BancoDados db;
    late ServicoUsuario servico;
    
    setUp(() {
      db = BancoDados();
      servico = ServicoUsuario(db);
    });
    
    test('cria e salva usuário corretamente', () async {
      final usuario = await servico.criarUsuario('João', 30);
      expect(usuario.nome, equals('João'));
      expect(usuario.idade, equals(30));
      
      // Verifica se foi salvo
      final usuarioSalvo = await db.buscar('João');
      expect(usuarioSalvo.nome, equals('João'));
    });
  });
}
```

</details>

### 🐛 Debugging

<details>
<summary><b>Técnicas de Debug</b></summary>

```dart
// 1. Print Debugging
void debugInfo(String message) {
  print('🐛 DEBUG: $message');
}

// 2. Assert Statements
void processarIdade(int idade) {
  assert(idade >= 0, 'Idade não pode ser negativa');
  // ... processamento
}

// 3. Try-Catch com Stack Trace
void funcaoPerigosa() {
  try {
    // código que pode falhar
    throw Exception('Algo deu errado!');
  } catch (e, stackTrace) {
    print('❌ Erro: $e');
    print('📍 Stack Trace:\n$stackTrace');
  }
}

// 4. Logging Estruturado
enum LogLevel { info, warning, error }

void log(LogLevel level, String message) {
  final timestamp = DateTime.now();
  final emoji = {
    LogLevel.info: 'ℹ️',
    LogLevel.warning: '⚠️',
    LogLevel.error: '🚨',
  }[level];
  
  print('[$timestamp] $emoji $message');
}
```

</details>

### 🔍 DevTools

> O Dart DevTools oferece ferramentas poderosas para debugging e profiling

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Magnifying%20Glass%20Tilted%20Left.png" width="40"/><br>
        <strong>Debugger</strong>
        <br/>
        <sub>Inspeção de código</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Chart%20Increasing.png" width="40"/><br>
        <strong>Performance</strong>
        <br/>
        <sub>Análise de desempenho</sub>
      </td>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Memory%20Card.png" width="40"/><br>
        <strong>Memory</strong>
        <br/>
        <sub>Análise de memória</sub>
      </td>
    </tr>
  </table>
</div>

### 📊 Cobertura de Testes

```bash
# Executar testes com cobertura
dart test --coverage=coverage

# Gerar relatório HTML
dart pub global activate coverage
dart pub global run coverage:format_coverage --lcov --in=coverage --out=coverage.lcov --packages=.packages --report-on=lib
```

<div align="center">
  <table>
    <tr>
      <th>Métrica</th>
      <th>Alvo</th>
      <th>Status</th>
    </tr>
    <tr>
      <td>Cobertura de Linha</td>
      <td>80%</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Cobertura de Branch</td>
      <td>75%</td>
      <td>✅</td>
    </tr>
    <tr>
      <td>Cobertura de Função</td>
      <td>90%</td>
      <td>✅</td>
    </tr>
  </table>
</div>

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
