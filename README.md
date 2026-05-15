# EYC

EYC, JavaScript'e transpile eden bir programlama dilidir.

## Kurulum

VSCode extension'ını kurmak için:

1. `eyc_vscode_extension.vsix` dosyasını indirin
2. VSCode'da Extensions menüsünü açın
3. `...` menüsünden "Install from VSIX" seçin
4. Dosyayı seçin ve kurulumu tamamlayın

## Kullanım

### EYC -> JavaScript

| EYC | JavaScript |
|-----|------------|
| `@id` | `document.getElementById("{id}")` |
| `${x}` | `window.{x}` |
| `muted` | `const` |
| `adopt` | `appendChild` |
| `is` | `==` |
| `or` | `\|\|` |
| `and` | `&&` |
| `not` | `!` |

**NOT:** index.html oluşturulduğunda @root.adopt() ile div'e obje koyabilirsiniz.

### EYC'den JavaScript'e Transpile

1. `.eyc` uzantılı bir dosya oluşturun
2. Dosyaya sağ tıklayın ve "EYC: Transpile to JavaScript" seçin
3. Otomatik olarak aynı isimli `.js` dosyası oluşturulur

### HTML Oluşturma

1. `.js` dosyasına sağ tıklayın
2. "EYC: Generate index.html" seçin
3. JS dosyanızı yükleyen `index.html` oluşturulur

## Build

Extension'ı yeniden derlemek için:

```batch
build_extension.bat
```

## Lisans

MIT License

## Yapan

Efkan Işık
--------------
FELLOS-STUDIOS
