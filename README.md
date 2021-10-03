# Wedding image gallery using Blazor

* Blazor WebAssembly 3.2.0.
* ASP.NET Core 3.1 backend.
* Custom folder for loading images.
* Image popup using [Lightbox](https://lokeshdhakar.com/projects/lightbox2/).
* On-demand thumbnail generation using [ImageSharp](https://github.com/SixLabors/ImageSharp).
* Localization using Microsoft.Extensions.Localization.
* Localization setting persistence using [Blazored.LocalStorage](https://github.com/Blazored/LocalStorage).

How to setup:
1. Create folders: 
  - /Server/wwwroot
  - /Server/is-cache
2. Create /Server/keys.json: <br>
```
{
  "ImageFolder": "<image folder path>",
  "Password": "<password>",
  "GalleryNamesEn": [ "MyGallery", "My gallery" ] ,
  "WebRootPath": "<path to server directory>"
}
 ``` 