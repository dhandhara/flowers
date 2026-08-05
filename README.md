Segue um `README.md` profissional para acompanhar o seu projeto no GitHub.

# 🌸 HKIA Flower Tracker

Um rastreador de coleção para **Hello Kitty Island Adventure**, desenvolvido para acompanhar o progresso das flores obtidas durante o jogo.

O aplicativo permite registrar sementes base, cores e padrões de cada espécie, exibindo automaticamente o progresso geral da coleção.

## Recursos

* Registro da semente base de cada flor.
* Controle de todas as cores disponíveis.
* Controle de todos os padrões compatíveis.
* Barra de progresso geral da coleção.
* Organização por região e por eventos.
* Filtros para visualizar flores obtidas ou pendentes.
* Armazenamento automático do progresso no navegador (Local Storage).
* Interface responsiva para computador, tablet e celular.

## Como utilizar

1. Abra o aplicativo em seu navegador.
2. Escolha uma flor.
3. Marque a semente base quando obtê-la.
4. Marque as cores e padrões conforme forem desbloqueados.
5. O progresso será salvo automaticamente.

## Publicação no GitHub Pages

1. Crie um novo repositório no GitHub.
2. Faça upload de todos os arquivos do projeto.
3. Vá em **Settings → Pages**.
4. Em **Source**, selecione:

```
Deploy from a branch
```

5. Escolha:

```
Branch: main
Folder: / (root)
```

6. Clique em **Save**.

Após alguns segundos, o aplicativo estará disponível em:

```
https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/
```

## Estrutura do projeto

```text
.
├── index.html
├── favicon.ico
├── README.md
├── LICENSE
└── .nojekyll
```

## Armazenamento

O aplicativo utiliza o **Local Storage** do navegador.

Isso significa que:

* o progresso é salvo automaticamente;
* não é necessário criar uma conta;
* os dados permanecem disponíveis enquanto o armazenamento do navegador não for apagado.

## Compatibilidade

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari
* Android
* iPhone
* iPad

## Próximas funcionalidades

Versões futuras poderão incluir:

* sincronização entre dispositivos;
* login com Google;
* backup na nuvem;
* modo offline (PWA);
* calculadora de cruzamentos;
* estatísticas detalhadas;
* busca por flores;
* filtros avançados;
* imagens oficiais das flores;
* notificações de eventos.

## Licença

Este projeto é distribuído sob a licença MIT.

---

**Aviso**

Este é um projeto desenvolvido por fãs para auxiliar no gerenciamento da coleção de flores de *Hello Kitty Island Adventure*. Todos os direitos sobre o jogo, personagens e marcas pertencem aos seus respectivos proprietários.
