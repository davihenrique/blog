---
title: Padrões que Resistem ao Tempo
date: 2026-04-13 01:18:00 -0300
categories: [OffTopic]
tags: [zip, fat32, formatos, história, tecnologia]
---

## Introdução

Dias atrás, pensava em algumas tecnologias que sobrevivem ao tempo, mesmo tendo alternativas modernas, elas continuam sendo utilizadas. Acredito que isso ocorre porque elas solucionam de uma maneira tão eficiente um problema que fica difícil serem substituídas de forma rápida.

---

## ZIP — 1989

Criado por Phil Katz em 1989, o `.zip` resolve uma coisa só: **empacotar arquivos**.

E resolve tão bem que hoje ele está escondido dentro de vários outros formatos:

- `.docx` e `.xlsx` — documentos do Office
- `.jar` — pacotes Java
- `.apk` — aplicativos Android
- `.epub` — livros digitais

Todos são arquivos ZIP por baixo dos panos.

A especificação é aberta, qualquer um pode implementar, e está em todo lugar. Não tem motivo para sair.

---

## FAT32 — 1996

O FAT32 tem um superpoder: **todo dispositivo do planeta sabe lê-lo**.

Windows, Linux, macOS, câmeras, videogames, televisões. Todos entendem FAT32.

Por isso ele ainda domina pen drives e cartões SD. Não é o mais eficiente nem o mais moderno, mas quando você precisa que um arquivo funcione em qualquer lugar sem instalar nada, o FAT32 ainda é a aposta mais segura.

---

## PDF — 1993

A proposta do PDF é simples: **o documento deve ter a mesma aparência em qualquer máquina**.

Isso era um problema sério em 1993 e continua sendo hoje.

Em 2008 virou padrão ISO, saindo do controle exclusivo da Adobe. Governos, bancos e cartórios ao redor do mundo exigem PDF para documentação oficial — e nenhum outro formato oferece a mesma garantia de fidelidade visual em qualquer lugar.

---

## JPEG — 1992

O JPEG usa uma sacada interessante: ele **descarta partes da imagem que o olho humano mal percebe**, reduzindo o tamanho do arquivo drasticamente sem parecer muito pior.

Formatos mais novos como WebP e AVIF fazem isso ainda melhor.

---

## SMTP — 1982

Com mais de 40 anos, o SMTP ainda é o protocolo que **move todo e-mail do planeta**.

Ele foi estendido ao longo do tempo com autenticação, criptografia e mecanismos anti-spam, mas o núcleo é o mesmo.

O e-mail sobreviveu ao ICQ, ao MSN, ao Google Wave e a inúmeras outras tentativas de substituição. O SMTP sobreviveu junto.

---

## SSH — 1995

O SSH nasceu depois que a rede da universidade do seu criador foi atacada e **senhas foram roubadas em texto puro**.

A solução foi criar um protocolo que criptografasse a conexão de ponta a ponta.

Trinta anos depois, ainda é a forma padrão de acessar servidores remotamente — e está por trás de toda autenticação do GitHub via chave.

---

## SQLite — 2000

Nasceu para ser usado em navios de guerra, onde ter um servidor de banco de dados dedicado era inviável.

A solução foi um banco SQL completo em uma única biblioteca, sem servidor, com tudo em um único arquivo.

Hoje é provavelmente é um dos bancos mais utilizados.

---

O padrão que aparece em todas essas tecnologias é o mesmo:

Elas resolvem um problema fundamental de forma boa o suficiente, têm especificação aberta, e chegaram a um nível de adoção onde **substituí-las custa mais do que conviver com suas limitações**.
