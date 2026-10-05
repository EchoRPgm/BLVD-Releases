# VTFEdit — releases

Downloads do **VTFEdit 3**, editor de texturas (VTF) e materiais (VMT) para jogos e mods da Source Engine, baseado no
VTFEdit Reloaded e na VTFLib. Este repositório contém apenas as versões publicadas.

<!-- downloads:start -->
## Última versão: [v3.0.0-preview.3](https://github.com/EchoRPgm/VTFEdit-Releases/releases/tag/v3.0.0-preview.3)

| Download | |
|---|---|
| [VTFEdit-win-x64.zip](https://github.com/EchoRPgm/VTFEdit-Releases/releases/download/v3.0.0-preview.3/VTFEdit-win-x64.zip) | **Recomendado.** Windows 10/11 x64, sem instalar nada. |
| [VTFEdit-win-x64-fx.zip](https://github.com/EchoRPgm/VTFEdit-Releases/releases/download/v3.0.0-preview.3/VTFEdit-win-x64-fx.zip) | Menor; exige o .NET 8 Desktop Runtime. |
| [SHA256SUMS.txt](https://github.com/EchoRPgm/VTFEdit-Releases/releases/download/v3.0.0-preview.3/SHA256SUMS.txt) | Checksums. |
<!-- downloads:end -->

Todas as versões: [Releases](https://github.com/EchoRPgm/VTFEdit-Releases/releases).

## Instalação

1. Baixe `VTFEdit-win-x64.zip` (roda sem instalar nada) ou `VTFEdit-win-x64-fx.zip` (menor; exige o
   [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0)).
2. Confira o download, se quiser, com o `SHA256SUMS.txt` da mesma release:
   `Get-FileHash .\VTFEdit-win-x64.zip -Algorithm SHA256`.
3. Extraia numa pasta e abra o `VTFEdit.exe`.

O VTFEdit avisa quando há uma versão nova (Settings › Updates).

## O que ele faz

- Visualiza VTF (canais, transparência, frames, faces, mipmaps, animação, HDR) em abas; edita propriedades, flags e
  recursos; exporta e cola imagens com alpha.
- Edições rápidas: girar, espelhar, redimensionar, inverter o verde de normal maps, regenerar mipmaps.
- Editor de VMT com validação e formulário com prévia.
- Converte imagens e pastas em VTF + VMT, inclusive observando uma pasta e reconvertendo ao salvar.
- Integração com o Explorer: *Open with VTFEdit*, *Convert to VTF* e miniaturas de .vtf.

## Problemas e sugestões

Abra uma [issue](https://github.com/EchoRPgm/VTFEdit-Releases/issues) com a versão (Settings › About) e os passos para
reproduzir.

## Licença e código-fonte

VTFEdit é distribuído sob a [GNU GPL versão 2](GPL.txt) e a VTFLib sob a [GNU LGPL versão 2.1](LGPL.txt).
Créditos: Neil "Jed" Jedrzejewski e Ryan Gregg (VTFLib e VTFEdit originais), Sky-rym (VTFEdit Reloaded) e
colaboradores.

Conforme a seção 3(b) da GPL v2, o código-fonte correspondente a cada versão publicada aqui pode ser solicitado
abrindo uma issue neste repositório, por no mínimo três anos a partir da publicação daquela versão, sem custo além do
de envio.
