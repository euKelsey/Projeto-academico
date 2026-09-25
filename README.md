# 🎓 Meu Campus

Aplicativo acadêmico desenvolvido em **Flutter** como projeto da disciplina de **Computação Móvel**.

O projeto apresenta uma interface simples para consulta de informações acadêmicas, permitindo ao estudante visualizar dados da próxima aula, acessar informações de uma disciplina e consultar avisos da turma.

---

## 📱 Sobre o projeto

O **Meu Campus** foi desenvolvido com o objetivo de praticar a construção de interfaces para aplicativos utilizando Flutter e Dart.

A aplicação possui uma tela inicial com informações acadêmicas e permite a navegação entre diferentes componentes do aplicativo.

### Funcionalidades

- Exibição da próxima aula;
- Consulta das informações da disciplina;
- Visualização de avisos da turma;
- Navegação entre telas;
- Exibição de informações através de modal;
- Utilização de imagem armazenada nos assets do projeto.

---

## 🖥️ Tela Inicial

Na tela inicial, o estudante encontra:

- imagem do campus;
- mensagem de boas-vindas;
- informações sobre a próxima aula;
- botão para acessar a disciplina;
- botão para visualizar avisos.

A próxima aula apresentada atualmente é:

**Computação Móvel**  
📅 Hoje  
🕐 19h  
📍 Sala 517

---

## 📚 Disciplina

Ao selecionar **Ver disciplina**, o aplicativo abre uma nova tela contendo informações da disciplina de Computação Móvel.

São apresentadas informações como:

- Disciplina: Computação Móvel;
- Tema: Construção de interfaces com Flutter;
- Professor: Felipe;
- Dia: terça-feira;
- Horário: 19h;
- Sala: 517.

O usuário também pode retornar à tela inicial através do botão **Voltar ao início**.

---

## 📢 Avisos

O botão **Ver aviso** abre um `ModalBottomSheet` com um aviso direcionado à turma.

O aviso utilizado atualmente no projeto é:

> Traga seu notebook para a próxima aula.

O modal possui também um botão para fechá-lo e retornar à tela principal.

---

## 🛠️ Tecnologias utilizadas

- **Flutter**
- **Dart**
- **Material Design**
- **Git**
- **GitHub**

---

## 📂 Estrutura principal do projeto

```text
Projeto-academico/
│
├── assets/
│   └── images/
│       └── campus.jpg
│
├── lib/
│   ├── main.dart
│   ├── tela_disciplina.dart
│   └── aviso_modal.dart
│
├── test/
│
├── android/
├── ios/
├── linux/
├── macos/
├── web/
├── windows/
│
├── pubspec.yaml
├── pubspec.lock
├── analysis_options.yaml
└── README.md
```

### `main.dart`

Arquivo principal da aplicação.

Responsável por:

- iniciar o aplicativo através do `runApp`;
- configurar o `MaterialApp`;
- criar a tela inicial;
- exibir a imagem do campus;
- apresentar as informações da próxima aula;
- realizar a navegação para a tela da disciplina;
- abrir o modal de avisos.

### `tela_disciplina.dart`

Responsável pela tela de detalhes da disciplina.

Apresenta informações como professor, dia, horário e sala da aula.

### `aviso_modal.dart`

Responsável pelo conteúdo exibido no modal de avisos.

Utiliza um `ModalBottomSheet` para apresentar informações ao estudante sem precisar abrir uma nova tela.

### `assets/images/campus.jpg`

Imagem utilizada na parte superior da tela inicial.

O diretório de imagens está configurado no arquivo `pubspec.yaml`.

---

## ▶️ Como executar o projeto

É necessário possuir o **Flutter** instalado e configurado.

Clone o repositório:

```bash
git clone https://github.com/euKelsey/Projeto-academico.git
```

Entre na pasta do projeto:

```bash
cd Projeto-academico
```

Baixe as dependências:

```bash
flutter pub get
```

Execute o aplicativo:

```bash
flutter run
```

---

## 📦 Dependências

O projeto utiliza principalmente os recursos nativos do Flutter.

Entre as dependências configuradas estão:

```yaml
flutter:
  sdk: flutter

cupertino_icons: ^1.0.8
```

---

## 🎯 Objetivo acadêmico

Este projeto tem finalidade acadêmica e foi desenvolvido para aplicar conceitos de desenvolvimento mobile, incluindo:

- construção de interfaces;
- organização de widgets;
- navegação entre telas;
- utilização de imagens;
- utilização de componentes do Material Design;
- exibição de modal;
- organização de um projeto Flutter.

---

## 👨‍💻 Desenvolvimento

Projeto desenvolvido como atividade acadêmica utilizando **Flutter e Dart**.