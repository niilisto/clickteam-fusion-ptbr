<div align="center">

<img width="768" height="512" alt="Clickteam Fusion 2.5 — Tradução pt-br" src="https://github.com/user-attachments/assets/1a984d96-6a8b-4339-8e9a-3abbc982a85c"/>

<h1>Clickteam Fusion 2.5+</h1>
<h3>Tradução para Português do Brasil</h3>

![Build](https://img.shields.io/badge/build-296.9-blue?style=flat-square)
![Idioma](https://img.shields.io/badge/idioma-pt--br-green?style=flat-square)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=flat-square)

</div>

---

Tradução da interface do **Clickteam Fusion 2.5+** (build 296.9) para **Português do Brasil**.

> Já existe uma tradução feita pelo [@gui8515](https://github.com/gui8515), porém ela apresenta alguns problemas de compatibilidade com a versão atual do Fusion. Portanto, esta é uma versão própria e atualizada.

---

## Sumário

- [Instalação](#instalação)
- [Módulos traduzidos](#módulos-traduzidos)
- [Como contribuir](#como-contribuir)
- [Observações](#observações)
- [To-do](#to-do)

---

## Instalação

1. Baixe ou clone este repositório.
2. Copie a pasta `pt-br` para o diretório de idiomas do Fusion:
   ```
   C:\Program Files (x86)\Steam\steamapps\common\Clickteam Fusion 2.5\Languages\
   ```
3. Abra o Clickteam Fusion 2.5, vá em **Edit → Preferences → General** e selecione **Portuguese (Brazil)**.
4. Reinicie o programa para aplicar a tradução.

---

## Módulos traduzidos

A pasta `Modules/` contém os arquivos de localização de cada extensão e objeto do Fusion 2.5:

| Categoria | Exemplos |
|---|---|
| Objetos nativos | `mmfs2.txt`, `mmf2u.txt` |
| Física (Box2D) | `Box2DBase.txt`, `Box2DPlatform.txt`, `Box2DJoint.txt` |
| Mobile | `iOS.txt`, `Android.json`, `HTML5.txt` |
| Controles e utilitários | `kcArray.txt`, `kcIni.txt`, `kcList.txt`, `kcEdit.txt` |
| Outros plugins oficiais | e muitos mais… |

---

## Como contribuir

1. Faça um **fork** do repositório.
2. Localize o arquivo `.txt` do módulo desejado em `Modules/`.
3. Edite os textos mantendo as **chaves originais** intactas.
4. Abra um **pull request** descrevendo as alterações.

---

## Observações

> [!IMPORTANT]
> - Não altere os identificadores (chaves) dos strings — apenas os valores traduzidos.
> - Mantenha placeholders como `%s`, `%d`, `%1`, `%2`, etc. nas mesmas posições do original.
> - Salve todos os arquivos com codificação **UTF-8**.

---

## Apoie o projeto

Se este projeto foi útil para você, considere fazer uma doação via PayPal:

<div align="center">

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-0070ba?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?business=marcogaspar92%40gmail.com)

</div>

---

## To-do

- [ ] Revisão semântica do `mmf2u.txt`.
