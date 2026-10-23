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
