# Nebula Tech — projeto acadêmico de HTML e CSS

Site fictício de tecnologia gamer, desenvolvido para reunir as quatro etapas do exercício em **uma única página**, sem remover nenhum elemento das etapas anteriores.

## Conteúdo por etapa

- **Parte 1:** cabeçalho (logo, informação 1 e 2), menu, conteúdo principal (imagem e texto) e rodapé (links úteis, fale conosco, redes sociais).
- **Parte 2:** três cards de serviços, organizados em três colunas no desktop e uma coluna no celular, e seção de chamada para ação com botão.
- **Parte 3:** localização demonstrativa com `display: grid`, duas colunas no desktop e uma no celular, incorporando um mapa OpenStreetMap.
- **Parte final:** perguntas frequentes em `<details>` e `<summary>`, sem JavaScript.

## Responsividade

- **Desktop (>900px):** imagem ao lado do texto, três cards de serviços em linha e localização em duas colunas.
- **Tablet (651–900px):** fontes ajustadas, textos centralizados, imagem abaixo do texto e cards distribuídos em três colunas.
- **Smartphone (até 650px):** logo menor; as duas informações do cabeçalho desaparecem; cards e mapa/endereço passam a uma coluna.

## Como abrir

Abra `index.html` em um navegador. Nenhuma compilação ou dependência de JavaScript é necessária. Fontes e mapa usam serviços externos, mas o restante funciona offline.

## Publicar no GitHub

1. Crie um repositório **público**, por exemplo, `nebula-tech`.
2. Na pasta do projeto, execute:

```bash
git init
git add .
git commit -m "feat: site responsivo completo - Nebula Tech"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/nebula-tech.git
git push -u origin main
```

3. Nos comentários da atividade, cole a URL do repositório público.

**Aviso:** Nebula Tech, o e-mail de contato e o endereço são demonstrações fictícias. Substitua-os por dados reais caso adapte o projeto para uso comercial. O mapa marca apenas uma área aproximada de Videira/SC, não um estabelecimento real.