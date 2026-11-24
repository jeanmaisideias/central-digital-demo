# Central Digital — demonstração white label

Portal de pós-entrega para construtoras: documentos, plantas, manual, garantias, manutenção preventiva, fornecedores, contatos e emergências — com acesso separado para **morador** e **síndico/administradora**.

> **Todos os dados são fictícios.** A "Construtora Nível A", os empreendimentos, as pessoas, os fornecedores, os telefones e os documentos foram criados apenas para apresentação a prospects. Nenhum documento tem valor técnico ou legal.

## O que a demonstração mostra

| Área | Conteúdo fictício incluído |
|---|---|
| Empreendimentos | 6 prédios: 3 com demonstração completa (Vértice 412, Maré Alta Residence, Solaris 88) e 3 "em ativação" |
| Unidades | 168 unidades em 5 tipologias (studio a 3 suítes), com situação, histórico e filtros |
| Plantas | Arquitetônico, água fria, sanitário, estrutural e elétrico geradas por tipologia (SVG) |
| Documentos | 13 documentos por prédio (manual de 12 páginas, memorial, convenção, regulamento, habite-se, ART, laudo, AVCB…) + projeto consolidado por tipologia |
| Fornecedores | 15 empresas em 11 categorias, com responsável, telefone, e-mail, itens fornecidos e garantia |
| Condomínio | Síndico, administradora, portaria, SAC e assistência técnica da construtora |
| Manutenção | 20 rotinas com última/próxima execução e alertas |
| Painel do síndico | Indicadores de unidades, documentos, chamados e manutenções |

## Estrutura

```
index.html                 portal (HTML/CSS/JS, sem dependências)
assets/                    logo, capa e fachadas
docs/<empreendimento>/     PDFs fictícios
```

Toda a marca e os dados ficam no objeto `DATA` dentro do `index.html`. Trocar a construtora ou incluir um empreendimento é uma alteração de dados, não de código.

## Publicar

GitHub Pages: *Settings → Pages → Deploy from branch → `main` / root*. Também funciona no Netlify ou no Cloudflare Pages arrastando a pasta.

## Créditos de imagem

Fachadas da Maré Alta e do Solaris 88: fotos gratuitas do [Pexels](https://www.pexels.com/) (licença Pexels, uso comercial livre). Fachada do Vértice 412 e capa: imagens próprias, editadas para a versão white label.

---
Desenvolvido por [Mais Ideias MKT 360](https://linktr.ee/maisideiasmkt).
