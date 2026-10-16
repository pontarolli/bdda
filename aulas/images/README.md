# Ilustrações e diagramas

Pasta para as imagens usadas nas aulas (`.png`, `.jpg`, `.svg`, `.gif`...).

## Como usar nos slides

Nos arquivos `.qmd` desta mesma pasta (`aulas/`), a referência é relativa ao
arquivo da aula. Exemplo, uma aula chamando uma figura em `aulas/images/`:

```markdown
![Diagrama de exemplo](images/nome-da-figura.png)
```

Prefira **SVG** para diagramas (ficam nítidos em qualquer zoom) e PNG para
capturas de tela.

## Organização sugerida

Para muitas figuras, agrupe por aula:

```markdown
![Diagrama de VMs](images/aula-21/diagrama-vms.png)
```

> Observação: a imagem precisa existir no repositório (é conteúdo, não é
> ignorada pelo `.gitignore`).
