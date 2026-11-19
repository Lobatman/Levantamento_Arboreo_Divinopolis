# Guia Fotográfico de Árvores de Divinópolis-MG

**Autor:** Victor Lobato dos Santos, biólogo.

Guia de campo para identificar as árvores encontradas em calçadas e canteiros centrais de Divinópolis-MG. Foi feito para apoiar um **censo da arborização viária**, em que cada árvore das vias é registrada.

**Acesse online (funciona no celular):** https://lobatman.github.io/Levantamento_Arboreo_Divinopolis/

> **Uso não comercial.** Este material foi feito para **pesquisa, ensino e uso técnico-científico**. Ele não é um produto comercial e não pode ser vendido nem usado para fins comerciais. Veja a seção [Licença](#licença).

## Conteúdo

| Seção | O que traz |
|---|---|
| Chave visual | Você marca o que observa na árvore e o guia mostra as espécies compatíveis. Os critérios são: tipo de folha, posição das folhas no ramo, sinais marcantes (látex, espinhos, cheiro, tronco, glândulas, anéis), cor da flor e origem. |
| Fichas das espécies | 68 espécies ou grupos. Cada ficha tem fotos sem flor, com flor e com fruto, as características que identificam a espécie, as espécies com que ela costuma ser confundida e alertas de manejo. |
| Tabela de espécies | Pode ser ordenada pelo cabeçalho e copiada em CSV para planilhas. |
| Calendário de floração | Épocas aproximadas de floração no Sudeste do Brasil. |
| Como ler a folha | Ilustrações dos tipos de folha e um roteiro de identificação em campo. |
| Protocolo do censo | Variáveis da ficha de campo e boas práticas. |
| Referências | Bibliografia usada. |

## Versões para celular e computador

O guia escolhe a versão sozinho pela largura da tela. Também é possível escolher no seletor **Versão** do cabeçalho, e a escolha fica salva no aparelho.

| Versão | Como fica | Link direto |
|---|---|---|
| Celular | Texto maior, botões grandes para o toque, fichas em uma coluna e uma barra fixa “Ver espécies” que leva da chave aos resultados | [?versao=celular](https://lobatman.github.io/Levantamento_Arboreo_Divinopolis/?versao=celular) |
| Computador | Chave de identificação em duas colunas e fichas em até três colunas | [?versao=computador](https://lobatman.github.io/Levantamento_Arboreo_Divinopolis/?versao=computador) |
| Automática | Usa a versão celular em telas de até 760 px de largura e a de computador nas maiores | [?versao=auto](https://lobatman.github.io/Levantamento_Arboreo_Divinopolis/?versao=auto) |

## Como usar em campo

1. Abra o link no navegador do celular e use **Adicionar à tela inicial** para ter um atalho.
2. As fotos precisam de internet. Em locais com sinal fraco, abra o guia antes de sair e mantenha a aba aberta.
3. Na chave visual, marque só as características de que você tem certeza.
4. Quando a identificação for incerta, registre a árvore como morfoespécie, fotografe, colete uma amostra e confirme depois com bibliografia ou com um especialista.

## Limitações

- A lista reúne as espécies citadas para a Regional Oeste de MG (Arcos, Divinópolis, Formiga, Itaúna e Pará de Minas), as mais frequentes em inventários viários mineiros e as nativas da região usadas em plantios urbanos. Espere encontrar espécies fora da lista.
- As épocas de floração são aproximadas e variam entre anos e entre indivíduos.
- As fotos vêm de identificações da comunidade do iNaturalist e podem conter erros pontuais.
- Este guia **não substitui** a identificação por especialista nem a consulta a herbários, especialmente para espécies protegidas. O ipê-amarelo e o pequizeiro são imunes de corte em Minas Gerais pela Lei Estadual 20.308/2012.

## Estrutura do repositório

```
index.html    guia completo (HTML, CSS e JavaScript em um único arquivo)
fotos_web/    198 fotos comprimidas (folha/planta, flor, fruto)
README.md     este arquivo
LICENSE       termos de uso
```

O guia é um arquivo HTML estático e não precisa de instalação. Para usar sem internet no computador, baixe o repositório e abra o `index.html` com a pasta `fotos_web/` ao lado.

## Principais referências

- Diagnóstico da arborização viária sob a rede elétrica na Regional Oeste de Minas Gerais. *Pesquisa Florestal Brasileira* (Embrapa).
- LORENZI, H. *Árvores brasileiras*. Vols. 1–3. Instituto Plantarum.
- LORENZI, H. et al. *Árvores exóticas no Brasil*. Instituto Plantarum, 2003.
- GONÇALVES, E. G.; LORENZI, H. *Morfologia vegetal*. 2. ed. Instituto Plantarum, 2011.
- CEMIG. *Manual de arborização*. CEMIG / Fundação Biodiversitas, 2011.
- Flora e Funga do Brasil, Jardim Botânico do Rio de Janeiro.

A lista completa, com links, está na seção **Referências** do guia.

## Licença

O guia (textos, tabela, chave de identificação, ilustrações e código) está licenciado sob a **[Creative Commons Atribuição-NãoComercial 4.0 Internacional (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.pt_BR)**. Veja o arquivo [LICENSE](LICENSE).

**É permitido**, com crédito ao autor:
- usar em pesquisa científica, trabalhos acadêmicos, ensino e extensão;
- usar como apoio técnico em levantamentos e estudos;
- copiar, adaptar e redistribuir para esses mesmos fins não comerciais.

**Não é permitido:**
- vender o guia ou versões adaptadas dele;
- incorporá-lo a produtos, serviços ou materiais comercializados;
- usá-lo em qualquer finalidade cuja vantagem principal seja comercial ou financeira.

### Fotos

As fotos em `fotos_web/` **não são do autor do guia**. Elas vêm de observações de grau de pesquisa do [iNaturalist](https://www.inaturalist.org) e continuam com as licenças escolhidas por seus autores: CC0, CC BY, CC BY-SA ou CC BY-NC. A autoria, a licença e o link de cada foto aparecem no guia ao ampliar a imagem. Para reutilizar uma foto, siga a licença dela.

## Como citar

> SANTOS, Victor Lobato dos. *Guia Fotográfico de Árvores de Divinópolis-MG: guia de campo para censo da arborização viária*. 2026. Disponível em: https://lobatman.github.io/Levantamento_Arboreo_Divinopolis/. Licença CC BY-NC 4.0.
