# ShowSyncRemote

Sincronização e supervisão de shows ao vivo entre cidades: a máquina **Origem** comanda e as
máquinas **Seguidoras** repetem, com confirmação de cada comando. Funciona com **Resolume Arena**,
**PowerPoint**, **PDF-to-PPT** e **Adobe Reader**, pela rede local ou pela **ZeroTier**.

![Painel da Central do Show](docs/painel-central.png)

Site oficial, tutoriais e vídeos: **https://showsync.pages.dev**

> Este repositório guarda só os **downloads** (espelho do site). O código-fonte não é público.

## Baixar

Abra a [release mais recente](../../releases/latest) e escolha um dos arquivos:

| Arquivo | Para quem |
| :--- | :--- |
| `ShowSyncRemote_..._Setup.exe` | **Recomendado.** Instala no Windows, com atalho no menu Iniciar. |
| `ShowSyncRemote_..._ASSINADO.exe` | Executável único, sem instalação. |
| `ShowSyncRemote_..._portable_ASSINADO.zip` | Versão portátil: descompacte e rode de uma pasta ou pendrive. |

São **os mesmos arquivos** do site, com o mesmo SHA-256 (está na descrição de cada release).
Use o GitHub quando o download pelo site estiver lento ou bloqueado na sua rede.

**Use a mesma versão em todas as máquinas do show.** O aplicativo avisa quando sai uma versão
nova (ele consulta o site oficial; nada é baixado nem instalado sozinho).

## Requisitos

- Windows 10 ou 11, 64 bits
- Microsoft Edge WebView2 (já vem no Windows 11 e na maioria dos Windows 10 atualizados)

## Conferir o arquivo baixado

No PowerShell, na pasta do download:

```powershell
Get-FileHash .\ShowSyncRemote_v1.16.0__build_1039_Setup.exe
```

O resultado tem que ser igual ao SHA-256 publicado na release e no site.

## Assinatura e antivírus

Os pacotes são assinados por **Mizin Produções Audiovisuais** com certificado **autoassinado**.
Isso não dá confiança pública automática no Windows: o SmartScreen pode avisar na primeira
execução. **Não desative o antivírus.** Se houver detecção de ameaça, interrompa a execução e
informe o diagnóstico.

## Contato

Mizin Produções Audiovisuais · https://showsync.pages.dev

Software proprietário. Todos os direitos reservados.
