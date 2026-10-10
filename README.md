<img src="brand/logo.png" alt="BLVD" width="96" align="right">

# BLVD — releases

Downloads do **BLVD**, editor de texturas (VTF) e materiais (VMT) para jogos e mods da Source Engine, com conversor
de modelos para props do Garry's Mod. Este repositório contém apenas as versões publicadas.

<!-- downloads:start -->
## Última versão: [v1.2.0](https://github.com/EchoRPgm/BLVD-Releases/releases/tag/v1.2.0)

| Download | |
|---|---|
| [BLVD-win-x64.zip](https://github.com/EchoRPgm/BLVD-Releases/releases/download/v1.2.0/BLVD-win-x64.zip) | **Recomendado.** Windows 10/11 x64, sem instalar nada. |
| [BLVD-win-x64-fx.zip](https://github.com/EchoRPgm/BLVD-Releases/releases/download/v1.2.0/BLVD-win-x64-fx.zip) | Menor; exige o .NET 8 Desktop Runtime. |
| [SHA256SUMS.txt](https://github.com/EchoRPgm/BLVD-Releases/releases/download/v1.2.0/SHA256SUMS.txt) | Checksums. |
<!-- downloads:end -->

Todas as versões: [Releases](https://github.com/EchoRPgm/BLVD-Releases/releases).

## Instalação

1. Baixe `BLVD-win-x64.zip` (roda sem instalar nada) ou `BLVD-win-x64-fx.zip` (menor; exige o
   [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0)).
2. Confira o download, se quiser, com o `SHA256SUMS.txt` da mesma release:
   `Get-FileHash .\BLVD-win-x64.zip -Algorithm SHA256`.
3. Extraia numa pasta e abra o `BLVD.exe`.

O BLVD avisa quando há uma versão nova (Settings › Updates).

## O que ele faz

- Visualiza VTF (canais, transparência, frames, faces, mipmaps, animação, HDR) em abas; edita propriedades, flags e
  recursos; exporta e cola imagens com alpha.
- Edições rápidas: girar, espelhar, redimensionar, inverter o verde de normal maps, regenerar mipmaps.
- Editor de VMT com validação e formulário com prévia.
- Converte imagens e pastas em VTF + VMT, inclusive observando uma pasta e reconvertendo ao salvar.
- Integração com o Explorer: *Open with BLVD*, *Convert to VTF* e miniaturas de .vtf.

## Problemas e sugestões

Abra uma [issue](https://github.com/EchoRPgm/BLVD-Releases/issues) com a versão (Settings › About) e os passos para
reproduzir.

## Licença e código-fonte

BLVD é distribuído sob a [GNU GPL versão 2](GPL.txt) e a BLVDLib sob a [GNU LGPL versão 2.1](LGPL.txt).
Créditos: BLVDLib, BLVDThumbnail e BLVDCmd derivam do VTFLib, VTFEdit e VTFCmd de Neil "Jed" Jedrzejewski e
Ryan Gregg, com contribuições de misyltoad, Sky-rym e IAmKnotMax.

Conforme a seção 3(b) da GPL v2, o código-fonte correspondente a cada versão publicada aqui pode ser solicitado
abrindo uma issue neste repositório, por no mínimo três anos a partir da publicação daquela versão, sem custo além do
de envio.
