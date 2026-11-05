# Dra. Carolina Mendes, Nutricionista

Nova versão da página da nutricionista Carolina Mendes Alves (CRN 3 16089), especialista no climatério e na menopausa. Atendimento on-line e presencial em Salto, SP.
Versão 2 (05/11/2026): abertura com foto em arco, programas em cartões que empilham, passo a passo animado, avaliações em esteira e mapa do consultório.
HTML, CSS e JavaScript puros, sem build. Todos os botões de agendamento abrem o WhatsApp.

## Estrutura

```
index.html                 página completa (estilos e scripts dentro do arquivo)
img/carol-hero.jpg         foto da abertura (jaleco e adipômetro)
img/carol-retrato.jpg      foto principal da seção "Sobre" (de óculos)
img/carol-sobre.jpg        foto menor da seção "Sobre" (gerada por IA, com autorização)
img/carol-perfil.jpg       miniatura (foto de perfil do Instagram)
img/marca-branco.png       logo do topo sobre o fundo azul
img/marca-azul.png         logo do topo depois de rolar a página
img/marca-simbolo.png      símbolo do logo (marca d'água)
img/slogan-branco.png      slogan "Transformando seu mundo com saúde e bem estar"
img/logo-branco.png        logo completo do rodapé
img/favicon.png            ícone da aba
img/apple-touch-icon.png   ícone ao salvar na tela do celular
vercel.json                configuração da Vercel (URLs limpas)
```

## Publicar

1. Crie um repositório no GitHub (ex.: `Carolina_Mendes`) e envie os arquivos desta pasta para a raiz dele.
   Importante: **arraste a pasta `img` inteira** para a área de upload. O botão "choose your files" não envia pastas.
2. Na Vercel, clique em **Add New → Project**, importe o repositório e mantenha:
   - Project Name: `nutri-carolinamendes`
   - Framework Preset: **Other**
   - Build Command: vazio
   - Output Directory: vazio (raiz)
3. Clique em **Deploy**. O site fica em https://nutri-carolinamendes.vercel.app/ e cada novo commit publica a atualização sozinho.

## Imagens

Ao trocar uma imagem mantendo o mesmo nome, aumente o número `?v=1` nos links do `index.html` (por exemplo `?v=2`) para os navegadores baixarem a versão nova.

## Editar conteúdo

- Número do WhatsApp: variável `numero` no fim do `index.html` e o número exibido no menu e na seção de contato (hoje (11) 91125-4148, o do Linktree).
- Mensagens automáticas: atributo `data-wa` de cada botão.
- Cores: variáveis no início do `<style>` (`--marinho`, `--noite`, `--laranja`, `--folha`, `--musgo`, `--papel`).
- A pasta `referencias-ia/` é só referência interna: **não suba para o GitHub**.
- Se o endereço final do site mudar, atualize `og:url`, `og:image` e `canonical` no `<head>`.
