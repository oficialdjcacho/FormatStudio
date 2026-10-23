# Componentes y licencias

Format Studio es una aplicación independiente bajo licencia MIT. Los componentes incluidos conservan sus respectivas licencias.

## FFmpeg / FFprobe 9.0.2

Distribución Windows x64 essentials de Gyan Doshi, enlazada por el proyecto FFmpeg. Los ejecutables se distribuyen sin modificaciones y se invocan como procesos separados.

- Proyecto: https://ffmpeg.org/
- Distribuidor: https://www.gyan.dev/ffmpeg/builds/
- Binarios: https://github.com/GyanD/codexffmpeg/releases/tag/9.0.2
- Código fuente FFmpeg de esta versión: https://github.com/FFmpeg/FFmpeg/tree/946fcce07b
- Archivo de fuentes: https://github.com/FFmpeg/FFmpeg/archive/946fcce07b.zip
- Licencia de la compilación: GNU GPL versión 3. Texto completo en `licenses/FFmpeg-GPL-3.0.txt`.
- Configuración y versiones de las bibliotecas: `licenses/FFmpeg-build-information.txt`.

SHA-256:

```text
3256173F3F8BFFD7DF12227C68ADF68025EDB1832273A9530688A7BB1ED8EDEC  tools/ffmpeg.exe
F0D36ECBBDD3BCFAC3EFA078C96C7271C2E68B3810595552AC3B7F17E9A65C52  tools/ffprobe.exe
```

FFmpeg incluye bibliotecas de terceros enumeradas en sus datos de compilación. Sus licencias y fuentes conservan los términos de sus titulares; el uso del programa no cambia esos términos. El código de FFmpeg y sus bibliotecas no es propiedad de Format Studio.

## Microsoft .NET 8.0.32

Runtime .NET y Windows Desktop Runtime x64 distribuidos junto con la aplicación; obtenidos de los paquetes oficiales de Microsoft en NuGet.org. Sus licencias y avisos se incluyen en `licenses/`.

- Runtime: https://github.com/dotnet/runtime/tree/v8.0.32
- Windows Forms: https://github.com/dotnet/winforms/tree/v8.0.32
- WPF: https://github.com/dotnet/wpf/tree/v8.0.32
- Licencias: https://github.com/dotnet/runtime/blob/v8.0.32/LICENSE.TXT

Los hashes verifican la identidad de los archivos; no constituyen una garantía absoluta frente a vulnerabilidades.

## PDFsharp-GDI 6.2.4 y PdfPig 0.1.14

Bibliotecas administradas obtenidas de paquetes oficiales en NuGet.org e incorporadas en el ejecutable propio.

- PDFsharp: https://github.com/empira/PDFsharp/tree/v6.2.4 — MIT, texto en `licenses/PDFsharp-MIT.txt`; aviso de BigGustave en `licenses/PDFsharp-BigGustave-LICENSE.txt`.
- PdfPig: https://github.com/UglyToad/PdfPig/tree/v0.1.14 — Apache-2.0, texto en `licenses/PdfPig-Apache-2.0.txt`.
- Dependencias Microsoft: DependencyInjection.Abstractions 8.0.2, Logging.Abstractions 8.0.3 y System.Security.Cryptography.Pkcs 8.0.2. Licencias y avisos en `licenses/`.

ISO9660 es código propio. El reproductor utiliza funciones PCM de `winmm.dll` del directorio de sistema de Windows; esta DLL no se redistribuye.

## Descargador opcional

El paquete principal no incluye descargador. La descarga independiente incorpora [yt-dlp 2026.10.21](https://github.com/yt-dlp/yt-dlp/releases/tag/2026.10.21), ejecutable oficial Windows x64, sin modificaciones. Conserva sus avisos y los de sus componentes en `licenses/yt-dlp-LICENSE.txt` y `licenses/yt-dlp-THIRD-PARTY-LICENSES.txt`. Fuentes y materiales de compilación en el proyecto oficial de esa versión.

SHA-256 de `tools/yt-dlp.exe`: `33121D192D706E62F684A06F80918E3F3A8BA52AC3A65213B6951C39C7D9F555`. Esta utilidad utiliza red al descargar medios; no es parte del flujo local del conversor.
