# Revisão — idiomas e identidade visual da política VaiVolta

- Estado: validada por pedido direto do usuário em 2026-10-09, na conversa de publicação do Gravando.
- Escopo: adicionar inglês e espanhol com navegação visível; preservar português e as URLs index.html/privacy-policy.html; aplicar cores primárias do VaiVolta.
- Fonte de conteúdo: política portuguesa vigente neste repositório. Traduções mantêm regras de dados comerciais locais, backup Android, exportação voluntária, assinaturas Google Play, ausência de anúncios e análise própria, retenção, segurança, público, mudanças e contato. Nenhuma transferência das regras de gravação/AdMob do Gravando.
- Fonte visual: `/Users/letras/AndroidStudioProjects/VaiVolta/app/src/main/java/br/com/vaivolta/core/designsystem/theme/VaiVoltaColor.kt`, Material primary `#FFC94D`, accent `#FFB01F`, textos `#101014`. Cores de link adaptadas para contraste sobre branco.
- Critérios: três idiomas completos sem scripts, links locais válidos, URLs anteriores preservadas, sem overflow em 390 e 1200 px; links/textos com contraste mínimo de 4,5:1; verificar build Pages e resposta pública.
- Plano: gerar traduções e HTML estático com navegação; validar conteúdo e apresentação; commit/push em main; verificar publicação.
- Sem alteração no app Android ou nas práticas de tratamento. Edição/idiomas atualizam a data da política para 2026-10-09.

## Resultados

HTMLs PT/EN/ES conferidos: onze seções por idioma, links locais válidos, ausência de scripts e `privacy-policy.html` idêntico a `index.html`. Navegação dos idiomas verificada no navegador. Layout conferido em 390×844 e 1200×900, sem overflow horizontal. Contraste: links 7,09:1; texto sobre primary 12,40:1; texto secundário 6,75:1. Conteúdo português preservado; traduções mantêm as mesmas onze seções. Publicação será verificada após o push.
