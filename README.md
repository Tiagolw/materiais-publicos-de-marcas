# Materiais públicos de marcas

Ícones e logos das marcas, hospedados aqui só para serem lidos por endereço fixo pelos sistemas de cada empresa (favicon da guia, logo da topbar). Tudo o que está aqui já aparece em tela para qualquer pessoa que abre um sistema, e é por isso que o repositório é público: um favicon não pode ser privado, o navegador o busca sem autenticação.

## Regras

- Só entra o que é, por natureza, a face pública da marca: ícone e logo. Manual de marca, fontes, arquivos-fonte e qualquer material interno ficam fora daqui.
- Uma pasta por empresa: `menezes-niebuhr/`, `dalla-valle/`. Empresa nova, pasta nova.
- Endereço fixo é contrato: depois de referenciado por um sistema, um arquivo não muda de pasta nem de nome. Ícone novo entra como arquivo novo (ou etiqueta nova, para quem usa CDN), e o sistema troca o endereço quando publicar.
- Cada empresa detém os direitos sobre os próprios arquivos; o uso fora dos sistemas dela depende de autorização.

## Endereços

Direto (raw, sem cache longo):

- `https://raw.githubusercontent.com/Tiagolw/materiais-publicos-de-marcas/main/<empresa>/<arquivo>`

Por CDN com etiqueta (cache longo, imutável por etiqueta):

- `https://cdn.jsdelivr.net/gh/Tiagolw/materiais-publicos-de-marcas@<etiqueta>/<empresa>/<arquivo>`

## Histórico

- Este repositório chamava-se `favicons` até 2026-09-11 e tinha os arquivos da Menezes Niebuhr na raiz. O GitHub redireciona os endereços antigos, e os arquivos da raiz continuam lá até o último sistema apontar para `menezes-niebuhr/`.
- Os arquivos da Dalla Valle vieram do repositório `dalla-valle-marca` em 2026-09-11; o painel de obras apontou para cá na versão 10, no mesmo dia, e aquele repositório foi apagado.
